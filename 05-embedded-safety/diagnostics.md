# Diagnostics

Diagnostics detect faults before they create unsafe behavior.

## Examples

- sensor range check
- sensor plausibility check
- communication timeout
- CRC check
- supply voltage monitoring
- memory test
- watchdog supervision

## Embedded Example

If a temperature sensor reads impossible values, software should reject the value and move to a safe mode.

## Real Automotive Usage

Diagnostics are used in ECUs to detect faults, store diagnostic information, and support safe operation.
