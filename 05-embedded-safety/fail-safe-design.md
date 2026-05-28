# Fail-Safe Design

Fail-safe design means the system moves to a safe state when a fault is detected.

## Examples

- disabling PWM output
- opening relay contact
- reducing motor torque
- ignoring invalid sensor values
- entering degraded mode

## Embedded Design Rule

Outputs should have defined safe default states.

## Practical STM32 Example

If communication with a controller is lost for more than 100 ms, disable motor PWM output.
