# Pineapple I

## Description

Pineapple I is a MIDI-connected 12-way LED driver.

## Overview

Pineapple I has following ports.

* MIDI IN port
* MIDI THRU+ port (which combines MIDI THRU and USB)
* LightDrive port

The LightDrive provides DC supply and drives upto 12 LEDs.

## Protocol

All MIDI signals must be sent to Ch.0. Messages to other channels are ignored.

To turn on an LED, send MIDI Note On (90H) with a velocity parameter (1 to 127) to Pineapple I. The note number 60 corresponds to the LED 0. See Table 1 for the Note-LED mapping.

To turn off an LED, send MIDI Note Off (80H) or MIDI Note On (90H) with zero velocity.

To change brightness of an LED, send MIDI Polyphonic Pressure message (A0H) with a velocity parameter (1 to 127).

Table 1. Note-LED mapping

| MIDI Note Num. | Num. LED |
|----------------|----------|
| 60 (C4)        | 0        |
| 61             | 1        |
| 62             | 2        |
| 63             | 3        |
| 64             | 4        |
| 65             | 5        |
| 66             | 6        |
| 67             | 7        |
| 68             | 8        |
| 69             | 9        |
| 70             | 10       |
| 71             | 11       |



## Hardware

### Overview of Connectors


* Power -- DC Input (+12V)
* LightDrive
* Indicator/Reset
* MIDI IN
* MIDI THRU+ (MIDI THRU + USB)

### LightDrive

| LightDrive Pin | Meaning   |
|----------------|-----------|
| LD1            | Vout      |
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

### MIDI IN

| MIDI IN Pin | Meaning |
|-------------|---------|
| m1          | NC      |
| m2          | NC      |
| m3          | NC      |
| m4          | Source  |
| m5          | Drain   |


### MIDI THRU+

| MIDI THRU+ Pin  | Meaning  |
|-----------------|----------|
| M1              | NC       |
| M2              | GND      |
| M3              | NC       |
| M4              | Source   |
| M5              | Drain    |
| M6              | USB Dp   |
| M7              | USB Vbus |
| M8              | USB Dn   |

### MPU Pinout

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

