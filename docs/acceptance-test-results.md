# Smart Environment Guardian — Acceptance Test Results

**Document status:** Draft  
**Version:** 0.1  
**Overall acceptance status:** Not yet tested

## 1. Purpose

This document records the actual results of acceptance testing for the Smart Environment Guardian ESP32-based environmental monitoring system.

## 2. Test Environment

| Item | Actual Details |
|---|---|
| ESP32 board model | Not confirmed |
| Sensor model | Not confirmed |
| Firmware version or commit | Not available |
| Build environment | Not confirmed |
| Temperature threshold | Not approved |
| Humidity threshold | Not approved |
| Test date | Not scheduled |

## 3. Acceptance Test Results

| Test ID | Test Description | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| SG-TST-001 | Valid sensor readings | Valid temperature and humidity are reported | Not tested | Not Run |
| SG-TST-002 | Sensor failure detection | Sensor failure is reported | Not tested | Not Run |
| SG-TST-003 | Threshold detection | Threshold violation is detected | Not tested | Not Run |
| SG-TST-004 | Physical alert activation | Configured LED and/or buzzer activates | Not tested | Not Run |
| SG-TST-005 | Alert recovery | Alert clears according to the approved recovery rule | Not tested | Not Run |
| SG-TST-006 | Serial logging | Required readings, timestamps, statuses, and errors are reported | Not tested | Not Run |
| SG-TST-007 | Firmware structure review | Required firmware responsibilities are separated | Not reviewed | Not Run |
| SG-TST-008 | Startup diagnostics | Startup checks and error handling work as required | Not tested | Not Run |

## 4. Evidence Register

| Evidence ID | Description | File Path | Status |
|---|---|---|---|
| SG-EVD-001 | Successful firmware build | TBD | Pending |
| SG-EVD-002 | Firmware flashed to physical board | TBD | Pending |
| SG-EVD-003 | Valid sensor readings | TBD | Pending |
| SG-EVD-004 | Threshold detection and physical alert | TBD | Pending |
| SG-EVD-005 | Alert recovery | TBD | Pending |
| SG-EVD-006 | Sensor failure handling | TBD | Pending |
| SG-EVD-007 | Serial-monitor logs | TBD | Pending |
| SG-EVD-008 | Physical prototype demonstration | TBD | Pending |

## 5. Acceptance Decision

**Current decision:** Not yet evaluated.

The project must not be declared accepted until the required build, flashing, and physical acceptance tests have been completed and the evidence reviewed.

## 6. Issues and Observations

No physical test observations have been recorded yet.

Issues discovered during testing will be documented with their test ID, description, severity, responsible teammate, corrective action, and retest result.

## 7. Sign-Off

- Firmware verification: Pending
- Hardware verification: Pending
- Test evidence review: Pending
- Final project approval: Pending
