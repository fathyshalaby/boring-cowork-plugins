# Command: /reach:svhc-assessment

Analyze a Bill of Materials to determine Article 33 communication and SCIP notification duties.

## Output Format
```
REACH SVHC ARTICLE 33 & SCIP ASSESSMENT
Product: [Product Name/SKU]
Total Weight: [X] g
Assessed against Candidate List: [e.g., 240 SVHCs, Jan 2024]

SVHC ANALYSIS (O5A Component Level):
#  Article Component       Material     SVHC Name         CAS Number   Conc. (% w/w)
────────────────────────────────────────────────────────────────────────────────────
1  [e.g., Brass Standoff]  [Brass]      [Lead]            [7439-92-1]  [3.5%]
2  [e.g., Power Cord]      [PVC]        [DEHP]            [117-81-7]   [1.2%]
[Add rows for all parts containing SVHCs >0.1%]

ARTICLE 33 OBLIGATION (Supply Chain Communication):
☐ YES, SVHCs present >0.1%. 
Action: Must provide "Safe Use Information" (minimum: substance name) to B2B customers upon delivery.

SCIP NOTIFICATION OBLIGATION:
☐ YES. SCIP dossier submission required before placing on EU market.
Action Required: Create IUCLID dataset linking [Component] -> [Sub-assembly] -> [Final Product].

ANNEX XIV/XVII RESTRICTION CHECK:
- Lead (Entry 63): Exempt if internal component not placed in mouth.
- DEHP (Entry 51): Restricted in toys/childcare. Verify intended use of product.
```
