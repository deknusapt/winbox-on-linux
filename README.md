# Install and Use MikroTik WinBox on Linux Desktops
This is the simple script to install and have a WinBox in the Linux Desktop



```
git clone [https://github.com/deknusapt/winbox-on-linux.git]
cd winbox-on-linux
chmod a+x install
./install
```

You should have installed Wine on your linux before installing this.
```
sudo apt-get install wine
```

To update the winbox, download the latest from the link blow and replace it with this file : /usr/bin/winbox.exe
https://mikrotik.com/download

OR just run one of the following commands (it takes a minute to get .exe) :
```
# 64 bit
sudo wget -q https://mt.lv/winbox64 -O /usr/bin/winbox.exe
```
OR
```
# 32 bit
sudo wget -q https://mt.lv/winbox -O /usr/bin/winbox.exe

```
