# Dependent Failure Analysis

Dependent Failure Analysis identifies failures that are not independent.

## Example

Two redundant sensors sharing the same power supply may both fail if the supply fails.

## Embedded Examples

- shared clock source failure
- shared voltage regulator failure
- common software bug
- shared communication bus fault

## Lesson

Redundancy is not enough if redundant elements share the same weak point.
