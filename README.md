# PKGBUILDs

- [Nocturn](https://aur.archlinux.org/packages/nocturn/)

## Usage

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
