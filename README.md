## Jinx

![Jinx logo](/logo-small.png?raw=true "Jinx logo")

Jinx (Jinx Is Not Xbstrap) is a meta-build-system for bootstrapping operating
system distributions inspired by [xbstrap](https://github.com/managarm/xbstrap)
and Arch Linux's [PKGBUILDs](https://wiki.archlinux.org/title/PKGBUILD).

Some examples of hobby OSes using Jinx are [Vinix](https://github.com/vlang/vinix),
[Gloire](https://github.com/streaksu/Gloire), and [Jinix](https://github.com/48cf/jinix).

### Dependencies
- Linux distro (other OSes are not supported)
- POSIX compatible `/bin/sh`
- curl
- findutils (for `find` and `xargs`)
- awk
- cc (gcc or clang work)
- git
- grep
- gzip
- libarchive (for `bsdtar`)
- procps (for `free`)
- rsync
- tar
- zstd
