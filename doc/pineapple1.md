# Pineapple I

## Description

Pineapple I is a PWD driver.

## Connectors

### Front Panel

* Power -- DC Input (+12V)
* LightDrive

### Back Panel

* MIDI IN
* MIDI THRU/USB

## LightDrive

| LightDrive Pin | Meaning     |
|----------------|-------------|
| D1             | Vout (+12V) |
| D2             | GND         |
| D3             | LD1         |
| D4             | LD2         |
| D5             | LD3         |
| D6             | LD4         |
| D7             | LD5         |
| D8             | LD6         |
| D9             | LD7         |
| D10            | LD8         |
| D11            | LD9         |
| D12            | LD10        |
| D13            | LD11        |
| D14            | LD12        |

## MIDI THRU/USB

| MIDI OUT/USB Pin | Meaning  |
|------------------|----------|
| M1               |          |
| M2               | GND      |
| M3               |          |
| M4               | Source   |
| M5               | Drain    |
| M6               | USB Dp   |
| M7               | USB Vbus |
| M8               | USB Dn   |

## MPU Pinout

| Arduino Micro Pin      | Meaning   |
|------------------------|-----------|
| D0 (TX, INT)           |           |
| D1 (RX, INT)           | MIDI IN   |
| D2 (I2C SDA, INT)      | I2C       |
| D3 (I2C SCL, INT, PWM) | I2C       |
| D4                     | BLANK     |
| D5 (PWM)               | GSCLCK    |
| D6 (PWM)               | LED1      |
| D7 (INT)               |           |
| D8                     |           |
| D9 (PWM)               | LED2      |
| D10 (PWM)              | LED3      |
| D11 (PWM)              | LED4      |
| D12                    | XLAT      |
| D13 (PWM)              | Indicator |
| MOSI                   | SIN       |
| MISO                   |           |
| SCLCK                  | SCLCK     |
| SS                     |           |
| A0                     |           |
| A1                     |           |
| A2                     |           |
| A3                     |           |
| A4                     |           |
| A5                     |           |
