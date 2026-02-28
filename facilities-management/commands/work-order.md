# Command: /facility:work-order

Generate a detailed maintenance work order for tracking and assignment.

## Output Format
```
WORK ORDER
WO#: [auto-number] | Priority: [Emergency/High/Medium/Low]
Date Created: [date] | Requested By: [name/tenant]

LOCATION: [Building, Floor, Suite/Room]
CATEGORY: [HVAC / Plumbing / Electrical / General / Janitorial]

DESCRIPTION:
[Detailed description of the issue or work requested]

ASSIGNED TO: [Technician/Vendor name]
TARGET COMPLETION: [date/time]

PARTS/MATERIALS NEEDED:
• [item and quantity]

SPECIAL INSTRUCTIONS:
[Access requirements, safety considerations, tenant coordination needs]

STATUS: [Open / In Progress / Awaiting Parts / Complete]
```
