# Command: /hvac:service-report

Generate a professional diagnostic service report documenting the technician's findings, measurements, and recommendations.

## Required Information
- Customer name and address
- System make, model, serial number, and age
- Customer's complaint
- Diagnostic findings and measurements taken
- Recommended repairs
- Parts and pricing (if applicable)

## Output Format
```
HVAC SERVICE REPORT
Date: [date] | Work Order #: [number]
Technician: [name] | License #: [number]

CUSTOMER: [name]
ADDRESS: [address]
SYSTEM: [make] [model] | Serial: [number] | Age: [X] years
Refrigerant Type: [R-410A / R-22 / etc.]

CUSTOMER COMPLAINT:
[What the customer reported]

DIAGNOSTIC FINDINGS:
[Detailed, technical description of what was found]

MEASUREMENTS TAKEN:
- Supply air temp: [X]°F | Return air temp: [X]°F | Delta-T: [X]°F
- Suction pressure: [X] PSIG | Discharge pressure: [X] PSIG
- Superheat: [X]°F | Subcooling: [X]°F
- Compressor amps: [X]A (rated: [X]A)
- Capacitor reading: [X] μF (rated: [X] μF)

DIAGNOSIS:
[Clear statement of the root cause]

RECOMMENDATION:
☐ Repair: [description and cost]
☐ Replace: [description and cost]

SYSTEM CONDITION NOTES:
[Overall assessment: coil condition, ductwork, filter, electrical]
```
