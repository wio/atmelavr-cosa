# AtmelAVR Cosa Framework

Atmel AVR 8-bit and 32-bit MCUs deliver a unique combination of performance, power efficiency and design flexibility. Optimized to speed time to market-and easily adapt to new ones-they are based on the industrys most code-efficient architecture for C and assembly programming.

[More Information about Atmel AVR](http://www.microchip.com/design-centers/8-bit/avr-mcus) 

Cosa is an object-oriented platform for Arduino. It replaces the Arduino and Wiring library with a large set of integrated classes that support the full range of AVR/ATmega/ATtiny internal hardware modules; all pin modes, Digital, and Analog Pins, External and Pin Change Interrupts, Analog Comparator, PWM, Watchdog, Timer0/Timer2 (RTT), Timer1 (Servo/Tone/VWI), Input Capture, UART, USI, SPI, TWI and EEPROM. Cosa supports several programming paradigms including Multi-Tasking, Event Driven Programming and UML Capsules/Actors.

[More Information about Cosa](https://github.com/mikaelpatel/cosa)

## Wio Framework 
This is a framework supported by Wio and is compatible with `atmelavr` platform. To use this framework:
* [Install wio](https://github.com/wio/wio#install)
* Create an AtmelAVR package or AtmelAVR app
```bash
wio create pkg --platform atmelavr --framework cosa
```
```bash
wio create app --platform atmelavr --framework cosa
```
