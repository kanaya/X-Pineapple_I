# Pineapple I

## Description

Pineapple I is a PWD driver.

## Connectors

### Front Panel

* Power -- DC Input (+12V)
* LightDrive
* Indicator/Reset

### Back Panel

* MIDI IN
* MIDI THRU+R

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

## MIDI THRU+R

| MIDI THRU+R Pin  | Meaning  |
|------------------|----------|
| M1               | Relay    |
| M2               | GND      |
| M3               | Relay    |
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
| XLAT      | D7                     | D7               |
| GSCLCK    | D6 (PWM)               | D6 (PWM)         |
| SIN       | MOSI                   | D11 (MOSI, PWM)  |
| SCLCK     | SCLCK                  | D13 (SCLK)       |
| LED1      | D5 (PWM)               | D5 (PWM)         |
| LED2      | D9 (PWM)               | D9 (PWM)         |
| LED3      | D10 (PWM)              | D10 (PWM)        |
| LED4      | D11 (PWM)              | D3 (PWM, INT)    |
| Indicator | D13 (PWM)              | D2               |
| ID        | D8                     | D8               |
| Relay     | D12                    | ---              |
| Reserved  | A0-A5                  | A0-A3, A6, A7    |
