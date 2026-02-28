# Command: /customs:invoice-audit

Audit a commercial invoice for customs compliance.

## Output Format
```
COMMERCIAL INVOICE AUDIT
Invoice #: [number] | Date: [date]
Seller: [name] | Buyer: [name]

COMPLIANCE CHECK:
Item                          Status    Issue
────────────────────────────────────────────────
Seller/Buyer identified        ☐ Pass    [note]
Terms of Sale (Incoterms)      ☐ Pass    [note]
Country of Origin stated       ☐ Pass    [note]
HTS codes included             ☐ Pass    [note]
Unit values & currency         ☐ Pass    [note]
Assists/royalties declared     ☐ Pass    [note]
Related party disclosure       ☐ Pass    [note]

VALUATION NOTES:
[Any additions or deductions to transaction value]

ACTION ITEMS:
[Corrections needed before entry filing]
```
