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

| Meaning   | Arduino Micro          | Arduino Pro Mini |
|-----------|------------------------|------------------|
| MIDI IN   | D1 (RX, INT)           | D1 (RX)          |
| I2C SDA   | D2 (I2C SDA, INT)      | A4 (SDA)         |
| I2C SCL   | D3 (I2C SCL, INT, PWM) | A5 (SCL)         |
| BLANK     | D4                     | D4               |
| XLAT      | D12 -> D7?             | D7               |
| GSCLCK    | D5 (PWM)               | D5 (PWM)         |
| SIN       | MOSI                   | D11 (MOSI, PWM)  |
| SCLCK     | SCLCK                  | D13 (SCLK)       |
| LED1      | D6 (PWM)               | D6 (PWM)         |
| LED2      | D9 (PWM)               | D9 (PWM)         |
| LED3      | D10 (PWM)              | D10 (PWM)        |
| LED4      | D11 (PWM)              | D3 (PWM, INT)    |
| Indicator | D13 (PWM)              | D8               |
