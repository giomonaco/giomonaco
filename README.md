# giomonaco
hi everybody
wget -O- http://shadowsocks.org/debian/1D27208A.gpg | sudo apt-key add -
На Debian Wheezy, Ubuntu 12.04 с libssl > 1.0.0
echo "deb http://shadowsocks.org/debian wheezy main" >> /etc/apt/sources.list
apt-get update
 apt-get install shadowsocks-libev
