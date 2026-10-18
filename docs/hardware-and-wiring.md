# Smart Environment Guardian — Hardware and Wiring

**Document status:** Draft  
**Version:** 0.1

## 1. Purpose

This document records the hardware components, electrical connections, GPIO assignments, and configured thresholds for the Smart Environment Guardian project.

## 2. Hardware Components

| Component | Confirmed Model | Status |
|---|---|---|
| Microcontroller | ESP32 board — exact model TBD | Pending confirmation |
| Temperature and humidity sensor | TBD | Pending confirmation |
| Alert indicator | LED and/or buzzer — TBD | Pending confirmation |
| Power source | TBD | Pending confirmation |
| Connecting wires | TBD | Pending confirmation |

## 3. Wiring Connections

The wiring details must be completed after the hardware components are selected and checked.

| Connection | ESP32 Pin | Component Pin | Status |
|---|---|---|---|
| Sensor power | TBD | TBD | Pending |
| Sensor ground | TBD | TBD | Pending |
| Sensor data | TBD | TBD | Pending |
| LED output | TBD | TBD | Pending |
| Buzzer output | TBD | TBD | Pending |

**Important:** Do not use these placeholders to wire the circuit. Confirm the actual board, sensor datasheet, voltage requirements, and supported pins first.

## 4. Threshold Configuration

| Parameter | Configured Value | Unit | Status |
|---|---|---|---|
| Temperature threshold | TBD | °C | Pending approval |
| Humidity threshold | TBD | %RH | Pending approval |
| Temperature recovery condition | TBD | °C | Pending approval |
| Humidity recovery condition | TBD | %RH | Pending approval |

The project team must approve threshold and recovery values before acceptance testing.

## 5. Hardware Setup Procedure

1. Identify the exact ESP32 board.
2. Identify the selected temperature and humidity sensor.
3. Verify sensor voltage and pin requirements.
4. Confirm safe GPIO assignments for the sensor and alert outputs.
5. Connect the components according to the approved wiring plan.
6. Inspect the connections before powering the circuit.
7. Record a photograph of the completed physical setup.

## 6. Hardware Verification

The hardware setup should be checked for:
- Correct power and ground connections.
- Correct sensor data connection.
- Correct LED and/or buzzer connections.
- Valid sensor readings through serial monitoring.
- Correct physical alert behavior during controlled tests.

## 7. Evidence

- Board and sensor identification: Pending
- Wiring diagram: Pending
- Physical setup photograph: Pending
- Hardware verification results: Pending

## 8. Document Status

This document is a preliminary template. No physical wiring or hardware verification is claimed as completed.
