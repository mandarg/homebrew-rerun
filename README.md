# homebrew-rerun
Brew tap for the `rerun` utility


## Installation  ##

Example:

```
$ brew install mandarg/rerun/rerun
==> Tapping mandarg/rerun
Cloning into '/usr/local/Homebrew/Library/Taps/mandarg/homebrew-rerun'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (5/5), done.
Unpacking objects: 100% (6/6), done.
remote: Total 6 (delta 0), reused 4 (delta 0), pack-reused 0
Tapped 1 formula (31 files, 14.7KB).
==> Installing rerun from mandarg/rerun
==> Installing dependencies for mandarg/rerun/rerun: readline, python@2
==> Installing mandarg/rerun/rerun dependency: readline
==> Downloading https://homebrew.bintray.com/bottles/readline-7.0.5.el_capitan.bottle.tar.gz
######################################################################## 100.0%
==> Pouring readline-7.0.5.el_capitan.bottle.tar.gz
==> Caveats
This formula is keg-only, which means it was not symlinked into /usr/local,
because macOS provides the BSD libedit library, which shadows libreadline.
In order to prevent conflicts when programs look for libreadline we are
defaulting this GNU Readline installation to keg-only.

For compilers to find this software you may need to set:
    LDFLAGS:  -L/usr/local/opt/readline/lib
    CPPFLAGS: -I/usr/local/opt/readline/include

==> Summary
🍺  /usr/local/Cellar/readline/7.0.5: 46 files, 1.5MB
==> Installing mandarg/rerun/rerun dependency: python@2
==> Downloading https://homebrew.bintray.com/bottles/python@2-2.7.15_1.el_capitan.bottle.tar.gz
######################################################################## 100.0%
==> Pouring python@2-2.7.15_1.el_capitan.bottle.tar.gz
==> /usr/local/Cellar/python@2/2.7.15_1/bin/python -s setup.py --no-user-cfg install --force --verbose --single-version-externally
==> /usr/local/Cellar/python@2/2.7.15_1/bin/python -s setup.py --no-user-cfg install --force --verbose --single-version-externally
==> /usr/local/Cellar/python@2/2.7.15_1/bin/python -s setup.py --no-user-cfg install --force --verbose --single-version-externally
==> Caveats
Pip and setuptools have been installed. To update them
  pip install --upgrade pip setuptools

You can install Python packages with
  pip install <package>

They will install into the site-package directory
  /usr/local/lib/python2.7/site-packages

See: https://docs.brew.sh/Homebrew-and-Python
==> Summary
🍺  /usr/local/Cellar/python@2/2.7.15_1: 4,679 files, 82.9MB
==> Installing mandarg/rerun/rerun
==> Downloading https://github.com/mandarg/rerun/archive/v0.1.0.tar.gz
==> Downloading from https://codeload.github.com/mandarg/rerun/tar.gz/v0.1.0
######################################################################## 100.0%
🍺  /usr/local/Cellar/rerun/0.1.0: 5 files, 6.7KB, built in 3 seconds

```
