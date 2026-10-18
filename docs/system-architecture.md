# Smart Environment Guardian — System Architecture

**Document status:** Draft  
**Version:** 0.1

## 1. Overview

Smart Environment Guardian is an ESP32-based embedded system designed to monitor room temperature and humidity. It evaluates sensor readings against configurable thresholds and activates a physical alert when the configured limits are exceeded.

## 2. System Workflow

The planned system workflow is:

1. **Sensor Acquisition:** Read temperature and humidity from the selected sensor.
2. **Sensor Validation:** Check whether readings are valid and detect sensor errors.
3. **Threshold Evaluation:** Compare valid readings against configured temperature and humidity thresholds.
4. **Alert Control:** Activate the configured LED and/or buzzer when a threshold is exceeded.
5. **Recovery:** Clear the alert when readings satisfy the approved recovery rule.
6. **Serial Logging:** Report readings, timestamps, alert status, and sensor errors through UART/serial output.

## 3. Logical Architecture

Temperature and Humidity Sensor
          |
          v
Sensor Acquisition and Validation
          |
          v
Threshold Evaluation
          |
          v
Alert Control
          |
          v
LED and/or Buzzer

Serial Logging reports sensor readings, system status, and errors.

## 4. Main Components

### 4.1 ESP32 Controller
Reads sensor data, evaluates configured conditions, controls alert outputs, and reports system status.

### 4.2 Environmental Sensor
Measures room temperature and humidity. The exact sensor model is pending hardware confirmation.

### 4.3 Alert Outputs
An LED and/or buzzer provides a physical indication when configured thresholds are exceeded. The final output configuration is pending confirmation.

### 4.4 Serial Monitoring
Provides diagnostic messages, readings, alert status, and sensor error information.

## 5. Error Handling

The planned firmware should:
- Detect invalid sensor readings.
- Report sensor communication failures.
- Perform startup diagnostics.
- Avoid treating invalid readings as valid environmental measurements.
- Report error and alert states clearly.

The detailed behavior must be confirmed during firmware implementation.

## 6. Hardware and Software Dependencies

- ESP32 board: TBD
- Environmental sensor: TBD
- Alert output pins: TBD
- Firmware framework: TBD
- Timestamp source: TBD

## 7. Verification Plan

The architecture will be reviewed against the implemented firmware. Integration testing will verify sensor acquisition, threshold detection, physical alert activation, recovery behavior, and error reporting.

## 8. Document Status

This document describes the planned logical architecture. It does not claim that the hardware has been connected, the firmware has been built, or the system has passed physical testing.
