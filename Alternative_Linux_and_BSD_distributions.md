Fedict supports officially the following Linux distributions:

- Ubuntu (most recent version plus the two most recent LTS versions)
- Debian (two most recent versions)
- Red Hat / CentOS (two most recent versions)
- openSUSE (two most recent versions)
- Fedora (two most recent versions)

For older versions of the above distributions, the existing packages are
not removed, but they are also not updated; if you run an unsupported
version of any of these distributions, Fedict recommends upgrading as
soon as possible.

For other distributions, Fedict does not provide prebuilt packages nor
support. However, some unsupported distributions do provide their own
packaging of the official middleware:

- For Arch Linux, install
  [eid-mw](https://aur.archlinux.org/packages/eid-mw/) from AUR.
- For FreeBSD, install
  [security/libbeid](https://svnweb.freebsd.org/ports/head/security/libbeid/)
  from the ports system.

Maintainers of other distributions are invited to open an issue against
this project with a request to update the above list.

Having said that, as Fedict has no influence over any patches that
third-party distributors may apply to their version of the eID
middleware, no support is provided by Fedict towards using these
third-party packages. If you encounter any problems, please contact your
distribution for support.
