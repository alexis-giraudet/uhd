# UHD

## Install

1. Download .deb packages from [Releases](../../releases).
2. Install .deb packages:
```sh
sudo apt install --no-upgrade $(realpath *.deb)
```
2. Hold UHD packages to prevent upgrades:
```sh
sudo apt-mark hold libuhd-dev python3-uhd uhd-host
```
