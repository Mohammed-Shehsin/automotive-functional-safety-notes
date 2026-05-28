# Watchdog Timers

A watchdog timer supervises whether software is running correctly.

If the software fails to refresh the watchdog in time, the system resets or enters a safe state.

## Why It Matters

Embedded software can hang due to infinite loops, memory corruption, timing errors, or unexpected interrupts.

## STM32 Example Concept

A window watchdog can detect both refresh too early and refresh too late.

## Safety-Oriented Use

A watchdog should not only reset the MCU blindly. The system should define what safe state is required after reset.
