# Pineapple I

## Description

Pineapple I is a LED driver.

## Connectors

### Front Panel

* Power -- DC Input (+12V)
* LightDrive
* Indicator/Reset

### Back Panel

* MIDI IN
* MIDI THRU+R

## LightDrive

| LightDrive Pin | Meaning   |
|----------------|-----------|
| LD1            | Vcc (+5V) |
| LD2            | GND       |
| LD3            | Light     |
| LD4            | Light     |
| LD5            | Light     |
| LD6            | Light     |
| LD7            | Light     |
| LD8            | Light     |
| LD9            | Light     |
| LD10           | Light     |
| LD11           | Light     |
| LD12           | Light     |
| LD13           | Light     |
| LD14           | Light     |

##MIDI IN

| MIDI IN Pin | Meaning |
|-------------|---------|
| m1          | NC      |
| m2          | NC      |
| m3          | NC      |
| m4          | Source  |
| m5          | Drain   |


## MIDI THRU

| MIDI THRU+R Pin  | Meaning  |
|------------------|----------|
| M1               | NC       |
| M2               | GND      |
| M3               | NC       |
| M4               | Source   |
| M5               | Drain    |
| M6               | USB Dp   |
| M7               | USB Vbus |
| M8               | USB Dn   |

## MPU Pinout

| Arduino Micro      | Meaning               |
|--------------------|-----------------------|
| D0 (RX, INT)       | MIDI IN               |
| D1 (TX, INT)       | NC                    |
| D2 (I2C, INT)      | I2C                   |
| D3 (I2C, INT, PWM) | I2C                   |
| D4/A6              | RSV1                  |
| D5 (PWM)           | RSV2                  |
| D6/A7 (PWM)        | RSV3                  |
| D7 (INT)           | DIGITAL7              |
| D8/A8              | BLANK                 |
| D9/A9 (PWM)        | XLAT                  |
| D10/A10 (PWM)      | GSCLCK                |
| D11 (PWM)          | RSV4                  |
| D12/A11            | RSV5                  |
| D13 (LED, PWM)     | INDICATOR             |
| MOSI               | SOUT                  |
| SCLCK              | SCLCK                 |
| A0-A5              | NC                    |

