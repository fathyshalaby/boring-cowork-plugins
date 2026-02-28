# Command: /waste:route-schedule

Generate a weekly collection route schedule for residential or commercial service.

## Required Input
- Service area/zone
- Service type (residential curbside, commercial front-load, roll-off)
- Number of stops/accounts
- Available vehicles and drivers

## Output Format
```
WEEKLY COLLECTION SCHEDULE
Zone: [name/number] | Service: [Residential/Commercial]
Effective: [start date]

MONDAY:
Route [A]: [area description] | Vehicle: [unit#] | Driver: [name]
  Stops: [X] | Est. Tons: [X] | Start: [time] | Disposal: [facility]

TUESDAY:
[same format]

[etc.]

NOTES:
• Holiday schedule: [If Monday holiday, Monday routes shift to Tuesday, etc.]
• Overflow plan: [backup driver/vehicle assignments]
```
