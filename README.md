# Deb-To-Go
This is Debian build system for Odroid Go Advance featuring mainline Linux kernel

You have to hold down "recovery" button in order to boot it, console is on internal UART header, 115200 baud rate

Work-In-Progress, not intended for use without mouse and keyboard

UI options include:
- Retroarch(WIP)
- Kodi(TODO, needs http://www.deb-multimedia.org/)
- Plasma Bigscreen UI(TODO?)

To build and install:
```
git clone https://github.com/Maccraft123/deb-to-go.git --recursive -j2
cd deb-to-go
./make-all
sudo ./make-rootfs <target sd card, ex. /dev/sdb>
```

To edit kernel config and install kernel:
```
./conf-kernel
sudo ./install-kernel <target sd card, ex. /dev/sdb>
```
