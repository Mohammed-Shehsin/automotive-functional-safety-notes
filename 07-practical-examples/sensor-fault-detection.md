# Practical Example — Sensor Fault Detection

## Goal

Detect invalid sensor values and react safely.

## Example

A sensor value is considered faulty if value is outside physical range, changes too quickly, is stuck for too long, or two redundant sensors disagree.

## Safe Reaction

- ignore invalid value
- use fallback value
- disable output
- raise diagnostic flag
