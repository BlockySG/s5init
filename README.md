# s5init (s5-init)

This is a fork of the Void Linux version of runit that is designed for non-linux, unix-like systems

Planned Changes:
1. Make it 100% free of Linux spific calls
2. Make it possible to compile without Unicode (Add the ability to use ANSI)
3. Make it possible for it to be compiled for 16-bit architectures (e.g. 80286, Motorola 68000/68010)

ORIGINAL README FILE:
```
# runit

This repository holds the version of runit that is used by Void Linux. It
incorporates patches that fix issues found by users as well as certain compiler
warnings.

The source history was obtained from <http://smarden.org/git/runit.git/>, but
the release tarballs have been pruned from this version.

The objective of this repository is not to revamp the runit code completely or
add functionality that detracts from its simplicity, but rather to provide a
canonical version of the source code and to avoid the inclusion of patches in
[void-packages](https://github.com/void-linux/void-packages). This also makes
reviewing patches much simpler. If you have an issue or patch that you feel fits
inside these objectives, please open an issue or pull request!
```
