# libresdr-pluto
libresdr-pluto\
Libresdr pluto firmware based on [https://github.com/hz12opensource/libresdr](https://github.com/hz12opensource/libresdr)\
release filename baseclock_cpu750_ddr525.tar.gz\
Add serial number init script from [tezuka firmware](https://github.com/F5OEO/tezuka_fw).\
Work with Matlab and SDRAngel.\
\
Download fw-libre-pluto-0.38-dirty-with-serial-number.zip above,\
Extract all the file to the SD card, make sure to empy the SD card first.\
Content of your microSD should be:
* boot.bif
* BOOT.bin
* devicetree.dtb
* fsbl.elf
* system_top.bit
* u-boot.elf
* uEnv.txt
* uImage
* uramdisk.image.gz
