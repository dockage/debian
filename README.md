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