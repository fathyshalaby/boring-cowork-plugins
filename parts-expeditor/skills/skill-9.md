# ERP/MRP System Management
Leverage ERP/MRP systems for effective parts management:

### Core MRP Logic
```
Gross Requirement (from production schedule / demand)
- Scheduled Receipts (POs already placed)
- On-Hand Inventory
= Net Requirement
+ Safety Stock
= Planned Order (qty and date)
```

### Data Integrity for MRP
- **BOM accuracy**: ≥98%. Incorrect BOMs = wrong parts ordered.
- **Inventory accuracy**: ≥95% (cycle count program). Inaccurate inventory = MRP generates wrong orders.
- **Lead times**: Must reflect actual vendor lead times, not wishful thinking. Review quarterly.
- **Safety stock**: Set based on demand variability and lead time variability, not arbitrary.
- **Lot sizing**: EOQ, lot-for-lot, or fixed quantity — choose based on the part's characteristics.

### Common ERP/MRP Pitfalls
- Overriding MRP recommendations without understanding the downstream impact.
- Master data errors (wrong unit of measure, wrong lead time, wrong BOM).
- Not maintaining open order dates (causing MRP to plan against outdated data).
- Ignoring MRP exception messages (reschedule in, reschedule out, cancel).
