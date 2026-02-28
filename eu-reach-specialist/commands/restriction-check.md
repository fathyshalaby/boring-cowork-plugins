# Command: /reach:restriction-check

Analyze a product/material against common REACH Annex XVII restrictions.

## Output Format
```
ANNEX XVII RESTRICTION ANALYSIS
Material/Process: [e.g., Colored Leather Watch Strap, Skin Contact]
Intended Market: EU General Consumer

TARGETED RESTRICTION CHECKS:

1. ENTRY 43: Azocolourants and Azodyes
   - Scope: Textile and leather articles in direct/prolonged contact with skin.
   - Limit: Cleavage of aromatic amines < 30 mg/kg.
   - Compliance Action: Supplier test report against EN ISO 17234-1 required.

2. ENTRY 47: Chromium VI
   - Scope: Leather articles coming into contact with skin.
   - Limit: < 3 mg/kg of total dry weight.
   - Compliance Action: Verify tanning process with supplier. 3rd party lab test recommended.

3. ENTRY 50: Polycyclic-aromatic hydrocarbons (PAH)
   - Scope: Plastic/rubber parts in prolonged skin contact.
   - Limit: 1 mg/kg for 8 specific PAHs (0.5 mg/kg for toys).
   - Compliance Action: Check synthetic rubber backings or plastic components.

4. ENTRY 63: Lead and its compounds
   - Scope: Articles supplied to public that can be placed in mouth by children.
   - Limit: < 0.05% by weight (500 ppm).
   - Compliance Action: Assess metal clasps/buckles. 

OVERALL RISK: [HIGH/MED/LOW]
RECOMMENDATION: [Quarantine pending chemical analysis / Approve based on supplier history]
```
