# LoRaWAN Feather
## Overview
An Adafruit Feather compatiable board that is LoRaWAN compatible.  Designed to work with the Semtech LoRaWAN reference implementation.  Based on the STM32L073 micro and the Dorji DRF1262T radio module (which is based on the SX1262).  The board has the following hardware features:
* LiPo battery connector and charging as warranted by the Feather spec  
* LiPo fuel gauging as expected by the LoRaWAN reference implementation  
* Implements native USB  
* Connections for I2C, SPI, UART, GPIO, Analog and DAC.  
* An efficent DC-DC buck/boost switch mode converter.  
* Includes an ARM Cortex 10pin SWD debug connector  
* Antenna footprint supports edge mount SMA, u.FL and pigtail connections
* Footprint for U8 can support a hard secure element (ATECC608 or compatible) or an I2C FRAM allowing the user to experiment with hardware encryption or be LoRaWAN 1.1 compliant
* Includes one USER button as well as RESET and BOOT buttons  
* Includes one USER LED and a CHARGE LED.

## Changelog
### REV A0
Inital release
### REV B0
* Fix STC3100 grounding
* Make R16,R17 DNP by default
* Bump Bot Silk to REVB0
### REV C0
* Make U8 footprint capable of crypto and fram device
* Minor updates to schematic
* Minor updates to doc prints
* Update bot silk to REV C0

## Open Source
All schematics, pcb files, gerbers, BOM, CPL are available in this repo.  Part numbers for LCSC and Digikey are included
