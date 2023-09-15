# Anycubic-Kobra-Go-Klipper
Find the camera device
```
ls -al /dev/v4l/by-id
```
```
adduser klipper
usermod -a -G tty klipper
usermod -a -G dialout klipper
usermod -a -G video klipper
usermod -a -G docker klipper
adduser klipper sudo
```
