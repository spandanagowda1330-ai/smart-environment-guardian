# Smart Environment Guardian — Test Plan

**Document status:** Draft  
**Version:** 0.1

## 1. Objective

The purpose of this test plan is to verify that Smart Environment Guardian correctly reads temperature and humidity, detects threshold violations, activates physical alerts, recovers to a normal state, and reports sensor errors.

## 2. Testing Scope

The following functions will be tested:

- Sensor reading and validation.
- Temperature and humidity threshold evaluation.
- LED and/or buzzer activation.
- Alert recovery when readings return to the approved safe range.
- Timestamped serial output.
- Sensor failure detection.
- Startup diagnostics and error handling.

## 3. Test Environment

| Item | Details | Status |
|---|---|---|
| ESP32 board | TBD | Pending |
| Environmental sensor | TBD | Pending |
| Firmware version or commit | TBD | Pending |
| Temperature threshold | TBD | Pending |
| Humidity threshold | TBD | Pending |
| Serial monitor configuration | TBD | Pending |

## 4. Planned Test Cases

### SG-TST-001: Valid Sensor Readings

**Procedure:**
1. Power on the assembled device.
2. Open the serial monitor.
3. Observe temperature and humidity readings.

**Expected result:** Valid readings are displayed with the required timestamps.

**Status:** Pending.

### SG-TST-002: Sensor Failure Detection

**Procedure:**
1. Establish normal sensor communication.
2. Perform a controlled sensor failure test using the approved test procedure.
3. Observe the serial output.

**Expected result:** The firmware detects the failure and reports an appropriate error.

**Status:** Pending.

### SG-TST-003: Threshold Detection

**Procedure:**
1. Confirm the approved temperature and humidity thresholds.
2. Produce a controlled reading above a configured threshold.
3. Observe the serial output and alert state.

**Expected result:** The threshold violation is detected and reported.

**Status:** Pending.

### SG-TST-004: Physical Alert Activation

**Procedure:**
1. Trigger a configured threshold violation.
2. Observe the LED and/or buzzer.

**Expected result:** The configured physical alert activates.

**Status:** Pending.

### SG-TST-005: Alert Recovery

**Procedure:**
1. Trigger an alert condition.
2. Return the readings to the approved safe range.
3. Observe the alert state.

**Expected result:** The alert clears according to the approved recovery rule.

**Status:** Pending.

### SG-TST-006: Serial Logging

**Procedure:**
1. Observe serial output during startup and normal operation.
2. Observe output during a controlled alert and sensor failure.

**Expected result:** Required readings, timestamps, alert states, and sensor errors are reported.

**Status:** Pending.

### SG-TST-007: Firmware Structure Review

**Procedure:**
1. Review the firmware source code.
2. Identify sensor acquisition, threshold evaluation, and alert control.
3. Check that their responsibilities are logically separated.

**Expected result:** The required functions are clearly separated in the implemented design.

**Status:** Pending.

### SG-TST-008: Startup Diagnostics

**Procedure:**
1. Restart the physical device.
2. Observe startup messages and diagnostic behavior.
3. Check error handling when a required component is unavailable.

**Expected result:** Startup diagnostics and relevant errors are reported clearly.

**Status:** Pending.

## 5. Test Result Recording

For every executed test, record:

- Test ID.
- Date and time.
- Firmware version or commit.
- Test setup and procedure.
- Expected result.
- Actual result.
- Pass, Fail, or Blocked status.
- Evidence filename or repository path.
- Tester name.

## 6. Test Completion Criteria

A test passes only when the observed result meets its expected result and the necessary evidence is recorded.

The project acceptance criteria must be reviewed against the test results before the system is declared ready.

## 7. Current Status

All test cases are planned and pending execution. No physical acceptance tests are claimed as completed.
