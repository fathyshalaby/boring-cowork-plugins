# Command: /fleet:maintenance-schedule

Generate a PM schedule for a fleet vehicle.

## Output Format
```
PREVENTIVE MAINTENANCE SCHEDULE
Unit: [ID] | Year/Make/Model: [X]
Current Odometer: [X] | Annual Miles: [est.]

SERVICE SCHEDULE:
Service   Next Due (Miles)   Next Due (Date)   Last Completed
──────────────────────────────────────────────────────────────
PM-A      [X]                [date]            [date]
PM-B      [X]                [date]            [date]
PM-C      [X]                [date]            [date]

SPECIAL SERVICES:
[Timing belt, coolant flush, transmission, etc. with interval]

RECALLS: [Open recalls from NHTSA if any]
```
