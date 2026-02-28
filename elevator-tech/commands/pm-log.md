# Command: /elevator:pm-log

Generate a preventive maintenance service log entry.

## Output Format
```
PREVENTIVE MAINTENANCE LOG
Unit: [ID] | Location: [building/address]
Date: [date] | Technician: [name] | Hours: [X]

TASKS COMPLETED:
☐ Ride quality check (up/down, all floors)
☐ Door operation (open/close timing, force, detector)
☐ Machine room inspection (temp, leaks, noise)
☐ Guide rail lubrication
☐ Pit inspection and cleaning
☐ emergency communication test
☐ Signal/indicator check

MEASUREMENTS:
Door close force: [X] lbf (max 30)
Leveling accuracy: [X]" (max ±1/4")
Machine room temp: [X]°F

DEFICIENCIES:
[Description and recommended action]

PARTS USED:
[Part, quantity, cost]

NEXT PM DUE: [date]
```
