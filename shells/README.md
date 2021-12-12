# Useful commands

## No password required
```
sudo visudo
sebika ALL=(ALL) NOPASSWD: ALL
```

## Fix actual linux machine wifi driver
```
sudo vim etc/NetworkManager/conf.d/default-wifi-powersave-on.conf
wifi.powersave = 2

sudo iwconfig wlp7s0 power off

sudo service network-manager restart
```
