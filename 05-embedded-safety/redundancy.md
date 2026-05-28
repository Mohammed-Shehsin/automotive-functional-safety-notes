# Redundancy

Redundancy means having additional elements to support safety when one element fails.

## Types

- sensor redundancy
- processor redundancy
- communication redundancy
- power supply redundancy

## Warning

Redundancy must avoid common-cause failures.

Example: Two sensors using the same failed power rail may both fail together.

## Embedded Example

Compare two sensor readings and detect disagreement beyond a defined threshold.
