# Bootloader for Pine64

* Contains the a pristine build of uboot 2017.03 rc2 with the boot0 appended
* Flash with sudo dd if=u-boot-with-dtb.bin of=/dev/mmcblk0 bs=1k seek=8 conv=fsync
* Instructions on how to build here http://git.denx.de/?p=u-boot.git;a=blob;f=board/sunxi/README.pine64
* Created without a partition table
