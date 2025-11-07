# Boardoza MicroSD Breakout Board

The **Boardoza MicroSD Breakout Board** is a compact storage solution that enables microSD card interfacing via **SPI communication protocol**. This breakout board features an integrated **voltage regulator** that converts 5V input to 3.3V operation, ensuring safe and reliable communication with microSD cards while maintaining compatibility with both 3.3V and 5V microcontroller systems.

With its small form factor of **20mm x 40mm**, this module provides an easy way to add mass storage capabilities to embedded projects, data logging applications, and IoT devices. The board is optimized for high-speed data transfer and features **3.3V tolerant SPI pins** for seamless integration.

## [Click here to purchase!](https://www.ozdisan.com/p/gelistirme-kitleri-ve-aksesuarlari-617/boardoza-boardoza-microsd-1202712)

|Front Side|Back Side|
|:---:|:---:|
| ![MicroSD Front](./assets/MicroSD%20Front.png)| ![MicroSD Back](./assets/MicroSD%20Back.png)|

---

## Key Features

- **SPI Communication Interface:** Standard SPI protocol for universal microcontroller compatibility.
- **Integrated Voltage Regulation:** Converts 5V input to 3.3V operation for safe microSD card interfacing.
- **3.3V Tolerant I/O:** All SPI pins are 3.3V tolerant, protecting the microSD card from overvoltage.
- **High-Speed Data Transfer:** Optimized for fast read/write operations with microSD cards.
- **Compact Design:** Small 20mm x 40mm form factor for space-constrained applications.
- **Wide Compatibility:** Works with microSD and microSDHC cards up to 32GB.
- **Simple Integration:** Standard SPI pinout for easy connection to Arduino, ESP32, STM32, and other platforms.

---

## Technical Specifications

**Input Voltage:** 5V  
**Voltage Input Type:** 6-pin 2.50mm header  
**Operating Voltage:** 3.3V (regulated)  
**Interface:** SPI (Serial Peripheral Interface)  
**Functions:** MicroSD Card Reader/Writer Module  
**I/O Voltage Level:** 3.3V tolerant  
**Supported Cards:** MicroSD, MicroSDHC (up to 32GB)  
**Operating Temperature:** -40°C ~ +85°C  
**Board Dimensions:** 20mm x 40mm

---

## Board Pinout

### **( J1 ) SPI Communication Pins**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | MISO | Master Input Slave Output (3.3V tolerant) |
| 2 | SCK | Serial Clock (3.3V tolerant) |
| 3 | MOSI | Master Output Slave Input (3.3V tolerant) |
| 4 | CS | Chip Select (3.3V tolerant) |
| 5 | GND | Ground (0V reference) |
| 6 | +5V | Positive voltage input |

---

## Board Dimensions

<img src="./assets/MicroSD Dimension.png" alt="MicroSD Breakout Dimensions" width="450"/>

---

## Step Files

[Boardoza MicroSD.step](./assets/MicroSD%20Step.step)

---

## Datasheet

[MicroSD Breakout Board Datasheet.pdf](./assets/MicroSD%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact <support@boardoza.com>

---

## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
