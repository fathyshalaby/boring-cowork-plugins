# Command: /auto:decline-letter

Generate a declined service documentation form for when a customer chooses not to perform recommended repairs.

## Output Format
```
DECLINED SERVICE ACKNOWLEDGMENT

Date: [date] | RO#: [number]
Vehicle: [Year Make Model] | Mileage: [X]
Customer: [name]

The following repair(s) were recommended and DECLINED by the customer:

1. [Repair description]
   Reason recommended: [safety concern / reliability / manufacturer requirement]
   Estimated cost: $[X]

2. [Repair description]
   Reason recommended: [description]
   Estimated cost: $[X]

By signing below, I acknowledge that the above repair(s) were recommended
by [Shop Name] and I have chosen to decline them at this time. I understand
the potential risks associated with operating my vehicle without these
repairs, including [specific risks, e.g., "reduced braking performance",
"potential engine damage", "safety hazard"].

Customer Signature: ____________________  Date: __________
Service Advisor: ____________________    Date: __________
```
