# Smart Environment Guardian — Build and Flash Guide

**Document status:** Draft  
**Version:** 0.1

## 1. Purpose

This guide documents how to configure the development environment, build the Smart Environment Guardian firmware, upload it to the physical ESP32 board, and verify startup using serial monitoring.

## 2. Environment Details

| Item | Confirmed Details |
|---|---|
| Operating system | TBD |
| ESP32 board model | TBD |
| Development environment | TBD |
| Firmware framework | TBD |
| Compiler/build tool | TBD |
| USB connection and driver | TBD |
| Serial monitor baud rate | TBD |
| Firmware source location | TBD |

These details must be confirmed by the firmware developer before the guide is finalized.

## 3. Prerequisites

Before building, confirm that:
- The correct ESP32 board is identified.
- The development environment is installed.
- Required board support packages and libraries are installed.
- The firmware source code is available.
- Sensor and alert pin assignments match the approved wiring.
- The correct USB connection and serial port are available.

## 4. Build Procedure

1. Open the firmware project in the approved development environment.
2. Select the confirmed ESP32 board and required build configuration.
3. Verify that the required libraries and dependencies are available.
4. Run the project's documented build command.
5. Review the build output for errors and warnings.
6. Record the result and the firmware commit or version.

**Build command:** TBD

**Expected result:** The firmware compiles successfully for the confirmed board.

**Actual result:** Not yet tested.

## 5. Flashing Procedure

1. Connect the physical ESP32 board using a suitable USB cable.
2. Identify the correct serial port.
3. Select the confirmed board and port in the development environment.
4. Upload the successfully built firmware.
5. Check the upload output for errors.
6. Record the firmware version and upload evidence.

**Upload procedure:** TBD

**Expected result:** Firmware uploads successfully to the physical board.

**Actual result:** Not yet tested.

## 6. Serial Monitor Verification

1. Open the serial monitor in the approved development environment.
2. Select the baud rate configured by the firmware.
3. Restart the board if required.
4. Observe startup diagnostics.
5. Check for temperature and humidity readings, timestamps, alert status, and sensor errors.
6. Save the actual output as a log file.

**Expected result:** The serial output matches the approved logging requirements.

**Actual result:** Not yet tested.

## 7. Evidence to Collect

- Successful build output.
- Successful upload output.
- Confirmed board and serial port information.
- Startup diagnostic messages.
- Serial log containing sensor readings.
- Firmware version or commit identifier.

## 8. Troubleshooting

### Build failure
Check the selected board, installed dependencies, configuration, and compiler messages.

### Upload failure
Check the USB cable, selected serial port, board connection, and required upload procedure.

### No serial output
Check the serial port, baud rate, USB connection, and firmware startup behavior.

### Sensor errors
Check the approved wiring, sensor power requirements, GPIO assignments, and firmware configuration.

## 9. Current Status

Build and flashing instructions are pending confirmation of the actual development environment and hardware. No successful build or physical upload is claimed as completed.
