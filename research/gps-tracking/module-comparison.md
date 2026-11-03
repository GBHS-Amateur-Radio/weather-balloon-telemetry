# GPS Module Comparison

## Purpose

This document compares candidate GPS modules for the weather balloon payload against the requirements defined in [requirements.md](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/requirements.md).

<br>

## Candidate Modules

| Module | Max Altitude | Position Accuracy | Update Rate | Operating Temperature | Supply Voltage | Interface | Mass | Cost | Datasheet | Breakout | 
|---|---|---|---|---|---|---|---|---|---|---|
| uBLOX MAX-M10M Pico Breakout with Chip Antenna | 80,000m / 262,467ft | 1.5m | 20Hz | -40'C to +85'C | 1.8 to 3.6V | UART, I2C | 1.5g | $43.00 | [Datasheet](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/datasheets/MAX-M10M-00B_DataSheet_UBX-22028884.pdf) | N/A |
| uBLOX MAX-M10S Breakout for Active Antennas | 50,000m / 164,041ft | 1.5m | 10Hz | -40'C to +85'C | 4.5 to 30V (Max logic 5.5V) | UART, I2C | 5g max | $57.00 | [Datasheet](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/datasheets/MAX-M10S_DataSheet_UBX-20035208.pdf) | [Breakout](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/datasheets/uBLOX_MAX_Breakout_for_Active_Antennas_Datasheet.pdf) |
| SparkFun SAM-M10Q GPS Breakout| 80,000m / 262,467ft | 1.5m | Up to 20 Hz (configuration dependent) | -40'C to +85'C | 3.3V | UART, I2C | TBD | $51.50 | [Datasheet](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/datasheets/SAM-M10Q_DataSheet_UBX-22013293.pdf) | [Breakout](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/datasheets/SparkFun_u-blox_SAM-M10Q.pdf) |

<br>

## Module Evaluations

### uBLOX MAX-M10M Pico Breakout with Chip Antenna 

**Product:** [Uputronics Product Page](https://store.uputronics.com/products/ublox-max-m10m-pico-breakout-with-chip-antenna)

**Advantages**
- Very lightweight at approximately 1.5 g
- Integrated chip antenna eliminates the need for a separate antenna

**Disadvantages**
- No onboard voltage regulator
- Requires a clean 1.8–3.6 V supply

**Notes**
- Logic levels must stay within the supported voltage range (1.8–3.6 V)

  <br>

### uBLOX MAX-M10S Breakout for Active Antennas

**Product:** [Uputronics Product Page](https://store.uputronics.com/products/ublox-max-m8q-breakout-for-active-antennas?variant=48647586480462).

**Advantages**
- Supports an external active antenna
- External antenna allows greater flexibility in antenna placement

**Disadvantages**
- Requires a separate antenna
- Larger and heavier overall system than an integrated-antenna
- More components must be mounted securely in the payload

**Notes**
- The specifications of the MAX-M10S receiver itself should be distinguished from the specifications of the Uputronics breakout board

<br>

### SparkFun SAM-M10Q GPS Breakout 

**Product:** [SparkFun Product Page](https://www.sparkfun.com/sparkfun-gps-breakout-chip-antenna-sam-m10q-qwiic.html)

**Advantages**
- Integrated antenna eliminates the need for a separate antenna
- Supports up to four simultaneous GNSS constellations
- Includes a backup battery for faster hot starts

**Disadvantages**
- Larger breakout board than the MAX-M10M Pico
- Maximum update rate decreases when using multiple GNSS constellations

**Notes**
- Can receive four GNSS constellations simultaneously at up to 5 Hz, or achieve higher update rates with fewer constellations
- Requires 3.3 V power and logic

<br>

## Recommendation

**Selected Module:** SparkFun SAM-M10Q GPS Breakout 

**Reasoning:** The SAM-M10Q module has an integrated antenna, an added backup battery and simultaneous reception with four noted GNSS constellations at the expense of increased board size. Although the breakout is larger than the MAX-M10M Pico, prototyping is easier with this board because it is a part of SparkFun's development ecosystem while still meeting the primary requirements of the GPS subsystem.

<br>

## References

General GPS research and supporting documents are stored in [`references/`](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/tree/main/research/gps-tracking/references).
