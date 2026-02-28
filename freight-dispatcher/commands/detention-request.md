# Command: /freight:detention-request

Generate a formal detention fee invoice or request to send to a shipper after a driver is held beyond free time at a facility.

## Required Information
- Load/reference number
- Facility name and address (pickup or delivery)
- Arrival time (with timezone)
- Departure/release time
- Free time allowance (typically 2 hours)
- Detention rate (typically $50–$75/hour)
- Supporting documentation (check-in time stamp, BOL, photos)

## Output Format
```
DETENTION FEE REQUEST

Load#: [number]
Facility: [name, address]
Driver Arrival: [date/time]
Loading/Unloading Complete: [date/time]
Total Time at Facility: [X] hours [Y] minutes
Free Time: [2] hours
Billable Detention: [X] hours at $[rate]/hour

TOTAL DETENTION DUE: $[amount]

Per the terms of our contract/rate confirmation, detention accrues at $[rate]
per hour after [X] hours of free time. Please remit payment within [30] days.

Supporting Documentation Attached:
- Check-in time stamp
- Bill of Lading
- Driver log showing arrival/departure
```
