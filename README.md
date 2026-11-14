# Boat OS releases

Public downloads of **Boat OS**, the onboard software for a 32°N hub. This repository holds release files
only; the source is developed in a private repository and is MIT licensed.

Each release `boat-os-hub-vX.Y.Z` carries, for `x86_64` and `aarch64` Linux:

- `boat-os-hub-<version>-<arch>-linux.tar.gz` — the hub, the `boat-os` command, the setup app, the
  displays and `install.sh`
- `SHA256SUMS` — check the download with `sha256sum -c SHA256SUMS`

## Install

On a supported Linux computer (Ubuntu 22.04 or 24.04, including NVIDIA Jetson on Ubuntu):

```sh
tar xzf boat-os-hub-<version>-<arch>-linux.tar.gz
cd boat-os-hub-<version>-<arch>-linux
sudo ./install.sh
```

Reboot. The hub's screen opens setup. Use any phone's browser as a remote; there is no app to install.

Full instructions: https://32north.ai/install
