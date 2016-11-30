# PKGBUILDs

- [Nocturn](https://aur.archlinux.org/packages/nocturn/)

## Memo

### Create new

```bash
$ sudo pacman -S base-devel
$ mkdir ~/abs/<package>
$ cd ~/abs/<package>
$ cp /usr/share/pacman/PKGBUILD.proto PKGBUILD
$ vim PKGBUILd
$ makepkg # test
```

### xkremap

```bash
$ cd nocturn
$ vim PKGBUILD # edit $pkgver
$ sudo pacman -S pkgbuild-introspection
$ mksrcinfo
```

### Nocturn

```bash
$ git clone ssh://aur@aur.archlinux.org/nocturn.git
$ cd nocturn
$ vim PKGBUILD # edit $pkgver and $sha1sums by `sha1sum Nocturn-linux-x64.zip`
$ sudo pacman -S pkgbuild-introspection
$ mksrcinfo
$ git add .
$ git commit -m "Nocturn v1.3.0"
$ git push origin master
```
