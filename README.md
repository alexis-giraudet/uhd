# UHD

## Install

1. Download .deb packages from [Releases](../../releases).
2. Install .deb packages:
```sh
sudo dpkg -i *.deb
```
3. Hold packages:
```sh
sudo apt-mark hold libuhd-dev  libuhd3.13.1 python3-uhd uhd-host
```
5. Fix dependencies:
```sh
sudo apt-get -f install
```
