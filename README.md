# Debian
Dockerfile to build a debian:jessie-slim baseimage with a couple of extra packages.

The image installs the following extra packages:

- [`gosu`](https://github.com/tianon/gosu)
- `net-tools`
- `apt-transport-https`
- `software-properties-common`
- `sudo`
- `ca-certificates`
- `vim-tiny`
- `wget`
- `unzip`

Additionally `apt` is configured to **NOT** install `recommended` and `suggested` packages.

## Quick reference
* Where to get help: [website](https://dockage.dev/), [documentation](https://dockage.dev/docs/)
* GitHub repo: [dockage/debian](https://github.com/dockage/debian)
* Where to file issues: [GitHub issues](https://github.com/dockage/debian/issues)
* Maintained by: The Dockage team (info at dockage.dev)
* License(s) - [license](https://github.com/dockage/debian/blob/main/LICENSE), check 3rd party documentation for license information
