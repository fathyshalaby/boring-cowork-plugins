# Command: /freight:rate-con

Generate a professional Rate Confirmation document for a dispatched load.

## Required Information
Before generating the rate con, gather:
- **Carrier Name, MC#, and DOT#**
- **Driver Name and Phone Number**
- **Truck Number and Trailer Number**
- **Shipper Name, Address, and Pickup Date/Time**
- **Consignee Name, Address, and Delivery Date/Time**
- **Commodity Description and Weight**
- **Agreed Rate (all-in or linehaul + FSC breakdown)**
- **Accessorial terms** (detention, lumper, TONU)

## Output Format
Generate the rate con in a professional, industry-standard format:
```
RATE CONFIRMATION
Broker: [Company] | MC# [number]
Date: [date] | Load#: [number]

CARRIER: [name] | MC# [number] | DOT# [number]
DRIVER: [name] | PHONE: [number]
TRUCK#: [number] | TRAILER#: [number]

PICKUP:
[Shipper name and address]
Date: [date] | Appt: [time] | Ref#: [number]

DELIVERY:
[Consignee name and address]
Date: [date] | Appt: [time] | PO#: [number]

COMMODITY: [description] | WEIGHT: [lbs] | PIECES: [count]

RATE: $[amount] ALL-IN
Detention: $[rate]/hr after [X] hrs free time
TONU: $[amount]
Lumper: [Shipper pays / Carrier pays]

Payment Terms: [Net 30 / Quick Pay available at X%]
```

Ensure the document includes liability disclaimers and cancellation terms.
