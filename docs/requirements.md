# Smart Environment Guardian — Requirements

**Document status:** Draft  
**Project status:** In development  
**Version:** 0.1

## 1. Project Objective

Develop an ESP32-based environmental monitoring system that measures room temperature and humidity, detects threshold violations, and activates a physical alert.

## 2. Functional Requirements

| ID | Requirement | Verification Method |
|---|---|---|
| SG-REQ-001 | Read temperature and humidity using the selected sensor. | Observe valid sensor readings. |
| SG-REQ-002 | Validate sensor readings and report sensor failures. | Perform a controlled sensor failure test. |
| SG-REQ-003 | Compare readings against configurable thresholds. | Test readings above configured thresholds. |
| SG-REQ-004 | Activate the configured LED and/or buzzer when a threshold is exceeded. | Observe the physical alert. |
| SG-REQ-005 | Clear the alert when readings return to the approved safe range. | Perform an alert recovery test. |
| SG-REQ-006 | Print timestamped readings, alert status, and sensor errors through serial monitoring. | Review serial output. |
| SG-REQ-007 | Separate sensor acquisition, threshold evaluation, and alert control logically. | Review firmware structure. |
| SG-REQ-008 | Perform startup diagnostics and handle errors clearly. | Review startup and error logs. |

## 3. Hardware Details

- ESP32 board model: TBD
- Temperature and humidity sensor: TBD
- Sensor GPIO pin: TBD
- LED/buzzer GPIO pins: TBD
- Power and wiring details: Pending hardware confirmation

## 4. Threshold Configuration

- Temperature threshold: TBD
- Humidity threshold: TBD
- Alert activation rule: TBD
- Alert recovery rule: TBD

These values must be confirmed by the project team.

## 5. Verification Status

All requirements are currently pending implementation and verification. No physical hardware tests have been claimed as completed.

## 6. Change History

| Version | Description |
|---|---|
| 0.1 | Initial requirements draft created |
