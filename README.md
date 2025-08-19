
# I2CSPI01 - I2C to SPI bridge

![I2CSPI01A](/doc/img/I2CSPI01A_top_big.jpg)

The I2CSPI01 module is designed for systems where a microcontroller with only an I2C interface needs to communicate with one or more SPI peripherals. It acts as a bridge that translates I2C commands into SPI signals, allowing integration of SPI devices such as ADCs, DACs, memory chips, or sensors into an I2C-based architecture. This simplifies wiring and reduces the number of required signals.

## Features

* I2C to SPI bridge based on SC18IS602B
* Supports up to four SPI slave devices
* Unused chip-select pins configurable as GPIO
* SPI clock modes: 0, 1, 2, 3
* SPI speed configurable: 58 kHz to 1.843 MHz
* GPIOs support multiple modes: quasi-bidirectional, push-pull, input-only, open-drain
* 200-byte internal buffer
* Operates as I2C slave and SPI master
* 3.3V supply voltage

## Specifications

| Parameter    | Value                                      |
| ------------ | ------------------------------------------ |
| Power Supply | Max. 3.6 V                                 |
| Dimensions   | 40.13 x 30.00 x 16 mm                      |
| Interface    | I2C (up to 400 kHz), SPI (up to 1.843 MHz) |
| IC Used      | SC18IS602B                                 |

## Assembly Notes

* One via must be drilled due to a PCB short.
* J5 header is not functional due to PCB layout issue.

## Resources

* [SC18IS602B Datasheet](https://www.nxp.com/docs/en/data-sheet/SC18IS602B.pdf)
* [Buy from UST](https://www.ust.cz/about/)


