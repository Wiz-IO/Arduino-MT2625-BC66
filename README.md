# Arduino (True Core) - Mediatek MT2625 - Quectel BC66

A few words in the beginning:
* This is not an official product of Mediatek / Quectel
* The project is based on Quectel OpenCPU and reverse engineering
* The port  is bound to the firmware version
* I have not LTE NB/CAT network for now (in Bulgaria, comming soon...) And I can not test the network features, but they have to work
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
* Test Board for the project: BC66-TE-B (it is shield Arduino, unfortunately...)
* API: OpenCPU, native C, EAT (Embedded AT) oriented (70 function), static lib
* My Extended API, native C/C++, more than 300 function, static lib
* Firmware: BC66NAR01A03_OCPU_BETA0426

Tools:
* Arduino IDE:
https://www.arduino.cc/
* GCC Linaro - last version
https://releases.linaro.org/components/toolchain/gcc-linaro/latest/

Arduino:
 * Standart Core
 * Periphery: 
    * GPIO: 17 pins max
    * ADC: 1 pin
    * UART: 3
    * PWM: 1
    * SPI: 1
    * I2C: 1
    * USB
Libraries:
* Peripheries 
* TCP Clent Socket
* SSL/TLS
* HTTP/S Client
* MQTT
* CoAP(feature)
* LWM2M(feature)
  
  

PC Operating system: Windows, Linux... whatever you choose... Arduino IDE + GCC

# If you want to help/support - contact me
# Comming soon...
