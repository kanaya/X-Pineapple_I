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
| D1 (TX, INT)       | MIDI OUT (board only) |
| D2 (I2C, INT)      | SW1                   |
| D3 (I2C, INT, PWM) | SW2                   |
| D4/A6              | BLANK                 |
| D5 (PWM)           | SW3                   |
| D6/A7 (PWM)        | GSCLCK                |
| D7 (INT)           | Alt RX                |
| D8/A8              | XLAT                  |
| D9/A9 (PWM)        | Alt TX                |
| D10/A10 (PWM)      | Reserved              |
| D11 (PWM)          | SW4                   |
| D12/A11            | Relay                 |
| D13 (LED, PWM)     | Indicator             |
| MOSI               | SOUT                  |
| SCLCK              | SCLCK                 |
| A0-A5              | Reserved              |

