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
| D1             | Vcc (+5V) |
| D2             | GND       |
| D3             | Light     |
| D4             | Light     |
| D5             | Light     |
| D6             | Light     |
| D7             | Light     |
| D8             | Light     |
| D9             | Light     |
| D10            | Light     |
| D11            | Light     |
| D12            | Light     |
| D13            | Light     |
| D14            | Light     |

## MIDI IN

| MIDI IN Pin | Meaning |
|-------------|---------|
| m1          | NC      |
| m2          | NC      |
| m3          | NC      |
| m4          | Source  |
| m5          | Drain   |


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

| Arduino Micro      | Meaning               |
|--------------------|-----------------------|
| D0 (RX, INT)       | MIDI IN               |
| D1 (TX, INT)       | NC                    |
| D2 (I2C, INT)      | SW1/I2C               |
| D3 (I2C, INT, PWM) | SW2/I2C               |
| D4/A6              | RSV1                  |
| D5 (PWM)           | SW3                   |
| D6/A7 (PWM)        | RSV2                  |
| D7 (INT)           | DIGITAL7              |
| D8/A8              | BLANK                 |
| D9/A9 (PWM)        | XLAT                  |
| D10/A10 (PWM)      | GSCLCK                |
| D11 (PWM)          | SW4                   |
| D12/A11            | RSV3                  |
| D13 (LED, PWM)     | INDICATOR             |
| MOSI               | SOUT                  |
| SCLCK              | SCLCK                 |
| A0-A5              | NC                    |

