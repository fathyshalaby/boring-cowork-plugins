# Command: /hvac:epa-log

Generate an EPA-compliant refrigerant tracking log entry for a service event.

## Required Information
- Date of service
- Customer name and address
- System make, model, and serial number
- Refrigerant type (R-22, R-410A, R-32, etc.)
- Pounds recovered
- Pounds charged
- Leak found? (Y/N) — if yes, location and repair details
- Technician name and EPA certification number
- Recovery equipment serial number

## Output Format
```
EPA REFRIGERANT TRACKING LOG

Date: [date]
Technician: [name] | EPA Cert #: [number]
Recovery Equipment S/N: [number]

Customer: [name]
System: [make/model] | Serial: [number]

Refrigerant Type: [type]
Total System Charge (nameplate): [X] lbs

Action Taken:
  Refrigerant Recovered: [X] lbs
  Refrigerant Added:     [X] lbs
  Net Change:            [+/- X] lbs

Leak Detected: [YES / NO]
  Location: [description]
  Repair Performed: [description]
  Leak Verified After Repair: [YES / NO]

Notes: [additional observations]

Technician Signature: _______________  Date: __________
```

Per EPA Section 608, this log must be maintained for a minimum of 3 years and made available upon request.
