# SCY
Security stuff

## VPN

Provider, e.g.:
- https://black.riseup.net/
- https://dl.bitmask.net/linux/#debian-packages

Install Bitmask  
https://dl.bitmask.net/en/signature-verification
```
wget     https://dl.bitmask.net/client/linux/stable/Bitmask-linux64-latest.tar.gz && xm
wget -O- dl.bitmask.net/apt.key | gpg --import
gpg --verify Bitmask-linux64-latest.tar.gz.asc
```
