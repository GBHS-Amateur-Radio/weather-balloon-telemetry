# GPS & Tracking

The GPS & Tracking subsystem is responsible for determining the position and altitude of the high-altitude balloon payload throughout flight. Position data will be provided to the telemetry and recovery systems for tracking and recovery.

<br>

## Objectives

- Determine payload latitude, longitude, and altitude and maintain it throughout the flight
- Provide position data to the telemetry and recovery systems

<br>

## System Concept

`GNSS Satellites → SAM-M10Q → Flight Computer → Telemetry System → Ground Station`

<br>

## Development

- [x] Initial GPS research
- [x] Define subsystem requirements
- [x] Compare candidate GPS modules
- [x] Select GPS hardware
- [ ] Design subsystem integration
- [ ] Develop firmware
- [ ] Conduct ground testing
- [ ] Integrate with telemetry system
- [ ] Conduct flight testing

<br>

## Documentation

- [GPS Requirements](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/requirements.md)
- [GPS Module Comparison](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/module-comparison.md)
- [System Design](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/system-design.md)
- [Datasheets](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/tree/main/research/gps-tracking/datasheets)
- [References](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/tree/main/research/gps-tracking/references)
- [Testing](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/tree/main/research/gps-tracking/testing)
- [Firmware](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/tree/main/research/gps-tracking/firmware)

<br>

## Selected Hardware

**GPS Receiver:** SparkFun SAM-M10Q GPS Breakout

See [GPS Module Comparison](https://github.com/GBHS-Amateur-Radio/weather-balloon-telemetry/blob/main/research/gps-tracking/module-comparison.md) for the hardware evaluation and selection reasoning.

<br>

## Contributors

**GPS & Tracking Team**
- James
- Josh
