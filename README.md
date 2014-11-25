# LPC1549 LQFP64 TFT with Touch Panel

## Project Start - 15.11.2014 

LPC15xx is a modern Cortex-M3 family with up to 256 kB of flash memory, 32 kB of ROM, a 4 kB EEPROM, and up to 36 kB of SRAM. The peripheral compliment includes one full-speed USB 2.0 device, two SPI interfaces, three USARTs, one Fast-mode Plus I2C-bus interface, one C_CAN module, PWM/timer with four SCTimer.

![](https://raw.github.com/GSNT/TFT-LPC15/master/LPC15.jpg)

It's not very fast (72MHz), but it's available in LQFP48, LQFP64 and LQFP100. So it's very useful to build small CAN devices.
To control or program devices a TFT board is a nice tool, so let's see if we can build one... 

### Features - 15.11.2014

	* LPC1549 LQFP64 package
	* SWD connector (-> LPC-Link2)
	* USB connector (-> ISP)
	* UART connector (-> ISP)
	* CAN transceiver (-> ISP)
	* 2.8" TFT with Touch Panel
	* RTC & Battery (CR2032)
	* 2x5 header (SPI...)

### First Version - 18.11.2014

First Version...

![](https://raw.github.com/GSNT/TFT-LPC15/master/V1_0.jpg)

### Second Version - 19.11.2014

Second Version with RTC battery...

![](https://raw.github.com/GSNT/TFT-LPC15/master/V1_1.jpg)

### PCB - 20.11.2014

The third version as PCB...

![](https://raw.github.com/GSNT/TFT-LPC15/master/PCB_1.jpg)

### Software LCD - 22.11.2014

First LCD functions...

![](https://raw.github.com/GSNT/TFT-LPC15/master/PCB_2.jpg)

...let's start with ADC to read the Touch panel...

### Software Touch Panel - 24.11.2014

Reading TP values, calibrating and storing settings in EEPROM...

![](https://raw.github.com/GSNT/TFT-LPC15/master/TP_1.jpg)

### Software Touch Panel - 25.11.2014

Using buttons and a simple menu is working without problems so far...

![](https://raw.github.com/GSNT/TFT-LPC15/master/TP_2.jpg)

