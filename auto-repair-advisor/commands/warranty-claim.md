# Command: /auto:warranty-claim

Generate warranty claim documentation for a repair that falls under a parts or labor warranty.

## Output Format
```
WARRANTY CLAIM
Date: [date] | Original RO#: [number] | Warranty RO#: [number]

CUSTOMER: [name] | Phone: [number]
VEHICLE: [Year Make Model] | VIN: [number] | Current Mileage: [X]

ORIGINAL REPAIR:
Date: [date] | Mileage at repair: [X]
Description: [What was done]
Parts installed: [Part name, brand, part number]

WARRANTY COVERAGE:
Type: [Parts & Labor / Parts Only / Labor Only]
Duration: [X months / X miles, whichever comes first]
Warranty expires: [date] or [X miles]

CURRENT COMPLAINT:
[Customer's description of the problem]

INSPECTION FINDINGS:
[Technician's diagnosis of the warranty concern]

DETERMINATION:
☐ Covered under warranty – Repair at no charge
☐ Not covered – [Explanation of why the warranty does not apply]

RESOLUTION:
[Description of the warranty repair performed]

Parts used: [list]
Labor time: [X hrs]
Internal cost: $[X]

Authorized by: ____________________  Date: __________
```
