# HARA Example — Braking System

This is a simplified learning example.

| Failure Mode | Vehicle State | Road Condition | Environment | E | C | S | ASIL |
|---|---|---|---|---|---|---|---|
| No braking effect | >100 km/h | Wet | Highway | E3 | C3 | S3 | C |
| Unexpected braking effect | 50–100 km/h | Dry | Main road | E4 | C2 | S3 | C |
| Asymmetric braking effect | Parking / <10 km/h | Dry | Side road | E4 | C2 | S1 | A |

## Learning Point

The same system can have different ASIL classifications depending on the situation.

## Embedded Insight

Safety analysis depends on context. A fault in software or sensor data may be more critical at high speed than at low speed.
