# Byrbt-Autoseed
An Autoseed used to reseed TV-series in Byrbt

## How it Works
![How it Works](image/How%20it%20work.png)

## Based Environment
#### Ubtuntu 14.04
* Transmission
```
apt-get -y install software-properties-common
add-apt-repository -y ppa:transmissionbt/ppa
apt-get update
apt-get -y install transmission-cli transmission-common transmission-daemon
```
* Flexget
```
apt-get -y install python-pip
pip install flexget
```
* rtorrent + irssi-autodl
```
wget --no-check-certificate https://raw.githubusercontent.com/arakasi72/rtinst/master/rtinst.sh
bash rtinst.sh -t
```
* MySQL
```
apt-get -y install mysql-server
```
* MediaInfo
```
apt-get -y install mediainfo
```
* Python3 model
```
apt-get -y install python3-pip
pip3 install pymysql transmissionrpc requests bs4 pymediainfo
```