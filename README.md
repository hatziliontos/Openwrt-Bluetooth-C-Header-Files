# Openwrt-Bluetooth-C-Header-Files

Header files from 5.50 Bluez source code. They are useful for python 2.7 pybluez in Openwrt. pybluez contains c files which reference (#include) bluetooth header files. Try to pip install pybluez and you will likely get compilation errors, that is because compiler is trying to make bluetooth.so library for python but can't find bluetooth header files. Successful pybluez installation done on DLINK DIR 505 with OpenWrt 19.07.4, r11208-ce6496d796.
