# Fail-Safe vs Fail-Operational

## Fail-Safe

A fail-safe system transitions into a safe state after detecting a fault.

Examples: motor shutdown, output disabled, emergency stop, safe GPIO state.

## Fail-Operational

A fail-operational system continues working in a degraded but safe mode after a fault.

Examples: redundant braking channel, reduced steering assistance, backup sensor channel.

## Embedded Engineering Perspective

Fail-safe is usually simpler and common in industrial automation. Fail-operational requires redundancy, diagnostics, and more complex architecture.

## Recruiter Perspective

Understanding this difference shows system-level thinking, not only firmware coding.
