# Pineapple I

## Description

Pineapple I is a PWD driver.

## Connectors

### Front Panel

* Power -- DC Input (+12V)
* LightDrive

### Back Panel

* MIDI IN
* MIDI THRU

## LightDrive

| LightDrive Pin | Meaning     |
|----------------|-------------|
| D1             | Vout (+12V) |
| D2             | GND         |
| D3             | L1          |
| D4             | L2          |
| D5             | L3          |
| D6             | L4          |
| D7             | L5          |
| D8             | L6          |
| D9             | L7          |
| D10            | L8          |
| D11            | L9          |
| D12            | L10         |
| D13            | L11         |
| D14            | L12         |

## MPU Pinout

| Arduino Micro Pin      | Meaning   |
|------------------------|-----------|
| D0 (RX, INT)           | MIDI IN   |
| D1 (TX, INT)           |           |
| D2 (I2C SDA, INT)      |           |
| D3 (I2C SCL, INT, PWM) |           |
| D4                     |           |
| D5 (PWM)               | LED1      |
| D6 (PWM)               | GSCLCK    |
| D7                     | BLANK     |
| D8                     | XLAT      |
| D9 (PWM)               | LED2      |
| D10 (PWM)              | LED3      |
| D11 (PWM)              | LED4      |
| D12                    |           |
| D13 (PWM)              | Indicator |
| MOSI                   | SIN       |
| MISO                   |           |
| SCLCK                  | SCLCK     |
| SS                     |           |
