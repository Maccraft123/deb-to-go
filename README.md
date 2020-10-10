# Deb-To-Go
This is Debian build system for Odroid Go Advance featuring mainline Linux kernel

You have to hold down "recovery" button in order to boot it, console is on internal UART header, 115200 baud rate

To build and install:
```
./make-all
sudo ./make-rootfs <target sd card, ex. /dev/sdb>
```

To edit kernel config and install kernel:
```
./conf-kernel
sudo ./install-kernel <target sd card, ex. /dev/sdb>
```
