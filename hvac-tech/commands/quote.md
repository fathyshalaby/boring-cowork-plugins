# Command: /hvac:quote

Generate an itemized, professional HVAC repair or replacement quote for a customer.

## Required Information
- Customer name and service address
- System type and model (if known)
- Problem diagnosed / work to be performed
- Parts required with part numbers (if known)
- Labor estimate (hours)
- Warranty terms

## Output Format
```
HVAC SERVICE QUOTE
Date: [date] | Quote #: [number]
Technician: [name]

Customer: [name]
Address: [address]
System: [make/model/serial] | Age: [years]

WORK DESCRIPTION:
[Detailed description of diagnosed problem and proposed repair]

PARTS:
[Part name]               [Part #]        $[price]
[Part name]               [Part #]        $[price]
                             Parts Subtotal: $[total]

LABOR:
[X] hours at $[rate]/hour                  $[total]

                              TOTAL ESTIMATE: $[total]

WARRANTY: [Parts: X year manufacturer | Labor: X days]

ALTERNATIVE OPTION (if applicable):
[System replacement details and pricing]

This quote is valid for 30 days from the date above.
Signature: ____________________  Date: __________
```
