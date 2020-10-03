# Linux Plymount PAW OS X Like Theme

Simple plymount theme for OS X fans

[![PAW OS X Like Theme](/preview.png?raw=true)](https://www.youtube.com/watch?v=Y_FtrxaRzTcY)

How to install:

~~~~
sudo cp -R Plymount_PAW_OS_X/ /lib/plymouth/themes/

sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/Plymount_PAW_OS_X/paw-osx.plymouth 100

sudo update-alternatives --config default.plymouth
~~~~

chose Paw-OSX from list and 
~~~~
sudo update-initramfs -u
~~~~


