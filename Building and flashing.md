https://www.klipper3d.org/Installation.html


# Building and flashing the micro-controller

cd ~/klipper/
make menuconfig

Firmware Configuration

1.STM32 - STM32F103
2.Bootloader offset - 20Kib bootloader
3.Communication interface - USB (on PA11/PA12)



![20221119_103802_2](https://user-images.githubusercontent.com/102475504/202937352-e162bf41-ef09-4a68-ab08-cc89cf31934a.jpg)

![20221119_103802_3](https://user-images.githubusercontent.com/102475504/202937357-9a84f0b3-95c1-49c2-b765-35fe826f2881.jpg)

![20221119_103802_4](https://user-images.githubusercontent.com/102475504/202937362-c288f573-578d-4f44-b61d-02aa8c55e65c.jpg)

![20221119_110123_7](https://user-images.githubusercontent.com/102475504/202937410-63c64eaf-4ee2-4435-9da2-e749b15b4035.jpg)

![20221119_110123_6](https://user-images.githubusercontent.com/102475504/202937371-4866ff67-8158-4091-aec5-7508f012cf9d.jpg)


download 
klipper.bin -> firmware.bin

Copy firmware.bin to the root directory of Micro-SD card, NOTE: !!if there is a "old_fw.bin" in the SD card, delete it first!!
Power off the printer and plug the Micro-SD card into socket on control board
Power on the printer, push the power button and wait about 30 seconds
(https://github.com/ZONESTAR3D/Z9/tree/main/Z9V5/Z9V5-MK1/6.%20Firmware)


Next Step is
https://www.klipper3d.org/Installation.html

