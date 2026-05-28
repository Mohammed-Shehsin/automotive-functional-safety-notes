# Practical Example — Simple Watchdog Demo

## Goal

Demonstrate how a watchdog can reset or recover an embedded system if software hangs.

## Concept

Normal operation: main loop refreshes watchdog and LED toggles normally.

Fault condition: software enters infinite loop, watchdog is not refreshed, system resets or enters safe state.

## Learning Value

Shows how supervision improves embedded reliability.
