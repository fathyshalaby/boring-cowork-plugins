# Command: /customs:incoterm-summary

Generate an Incoterms 2020 comparison for a specific shipment.

## Output Format
```
INCOTERMS 2020 ANALYSIS
Shipment: [origin] → [destination] | Mode: [ocean/air/land]

RECOMMENDED TERM: [Incoterm]

RISK & COST TRANSFER COMPARISON:
Term    Risk Transfer Point    Cost Transfer Point    Customs Value Includes
──────────────────────────────────────────────────────────────────────────────
EXW     Seller's premises      Seller's premises      All costs to US port
FOB     Ship's rail, origin    Ship's rail, origin    Freight + insurance
CIF     Ship's rail, origin    Destination port       Already included
DDP     Buyer's door           Buyer's door           Deduct post-import costs

IMPACT ON DUTY CALCULATION:
[How the selected Incoterm affects the entered value for duty purposes]
```
