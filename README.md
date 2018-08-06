# Arduino (True Core) - Mediatek MT2625 - Quectel BC66

A few words in the beginning:
* This is not an official product of Mediatek / Quectel
* The project is based on Quectel OpenCPU and reverse engineering
* The port  is bound to the firmware version
* and sorry for my English

Chipset Mediatek MT2625 SoC
https://www.mediatek.com/products/nbIot/mt2625
* Applications CPU: ARM Cortex-M 104 MHz 
* Modem DSP: unknown, NB / CAT1
* RAM: 4M
* FLASH: 4M
* IO: GPIO, I2C, I2S, PCM, SDIO, UART, USB...
* OS: FreeRTOS
* NET: LwIP
* SSL: mbedtls
* Clinets: HTTP/S, MQTT, COAP, LWM2M 

Module: Quectel BC66
https://www.quectel.com/product/bc66.htm
* Board: BC66-TE-B (it is shield Arduino, unfortunately...)
* API: OpenCPU, native C, EAT (Embedded AT) oriented (70 function), static lib
* My Extended API, native C/C++, more than 300 function, static lib
* Firmware: BC66NAR01A03_OCPU_BETA0426

Tools:
* Arduino IDE:
https://www.arduino.cc/
* GCC Linaro - last version
https://releases.linaro.org/components/toolchain/gcc-linaro/latest/

PC Operating system: Windows, Linux... whatever you choose... Arduino IDE + GCC
