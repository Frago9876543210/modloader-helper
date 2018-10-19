### How to fix error on Debian?
```bash
#Note: It will update your distribution to the test version.
echo 'deb http://ftp.debian.org/debian/ buster main' >> /etc/apt/sources.list
apt-get update
apt-get upgrade
apt-get dist-upgrade
```
