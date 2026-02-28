# Command: /freight:driver-instructions

Generate clear, concise pickup or delivery instructions to send to a driver.

## Required Information
- Pickup or delivery
- Facility name and full address
- Appointment date and time
- Reference/PO numbers
- Special instructions (dock assignment, check-in process, lumper status)
- Emergency contact

## Output Format
```
PICKUP INSTRUCTIONS
Load#: [number]

FACILITY: [Name]
ADDRESS: [Full address with zip]
APPOINTMENT: [Date] at [Time] [Timezone]
REFERENCE#: [number(s)]

CHECK-IN PROCESS:
[Step-by-step: where to go, who to ask for, what paperwork to present]

SPECIAL NOTES:
- [e.g., "Must have lumper—we will provide comcheck code"]
- [e.g., "Scale on-site. Must weigh before departing."]
- [e.g., "No overnight parking allowed at this facility."]

BROKER CONTACT: [Name] | [Phone] | [Email]
```

Keep instructions simple and scannable. Drivers read these on a phone screen while driving.
