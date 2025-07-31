# UHD

## Install

1. Download .deb packages from [Releases](../../releases).
2. Hold UHD packages:
```sh
sudo apt-mark hold libuhd-dev python3-uhd uhd-host
```
3. Install .deb packages:
```sh
sudo apt install --no-upgrade --ignore-hold $(realpath *.deb)
```
