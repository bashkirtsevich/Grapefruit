# Grapefruit
![logo](https://github.com/bashkirtsevich/grapefruit-web/blob/master/static/logo.png)
Grapefruit — is a bittorrent search spyder crawler search engine, based on dht-bittorrent network.

## Installation
1. Download grapefruit installer repository
```bash
git clone https://github.com/bashkirtsevich/grapefruit.git
cd grapefruit
```
2. Install Docker (optional)
```bash
# For Centos-7
sudo ./docker-install.sh
sudo usermod -aG docker $USER
sudo reboot
```
3. Start application
```bash
./startup.sh
```

## Components
* mongodb
* nginx (_optional;_ useful as https proxy and cache)
* grapefruit-crawler
* grapefruit-web
