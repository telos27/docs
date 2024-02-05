Milk-V Duo 256M Notes

Linux test
* need an SD card
* download Linux image from Milk-V website
* use rufus or equivalent to write the image to the SD card (ISO format)
* insert SD card into the Duo
* connect to computer with USB-C cable
* red LED should turn on, then blue LED should flash
* install RNDIS driver on Windows (pseudo Ethernet over USB)
* ping 192.168.42.1 should work
* ssh root@192.168.42.1, password: milkv
* should be able to login into Linux system

SD card is mountable: mkdir /mnt/sd1; mount /dev/mmcblk0p1 /mnt/sd1
