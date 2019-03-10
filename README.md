# raspberryPi
uboot(The Universal Bootloader)

minimum set of bootstrapping:

bootcode.bin, start.elf, kernel7.img, bcm2710-rpi-3-b.dtb, overlays (folder)

U-Boot (The Universal Bootloader) is a popular, feature rich, open source bootloader for embedded systems. It is licenced under the GNU General Public Licence version 2.

While its primary purpose is to boot an operating system, such as Linux, it also provides many useful tools for developing and debugging embedded systems.

This includes support for many common file-systems including FAT, ext3, ext4, NFS etc and interfaces such as USB, Ethernet (IP), MMC and even Asynchronous Serial (Kermit/xmodem/ymodem). This allows the developer to load new images and file-systems from a variety of sources for testing and/or reflashing.

It also includes an environment variable engine allowing for easy configuration.
(refer to: https://www.beyondlogic.org/compiling-u-boot-with-device-tree-support-for-the-raspberry-pi/)
