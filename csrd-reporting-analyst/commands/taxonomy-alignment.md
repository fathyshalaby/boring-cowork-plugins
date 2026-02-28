# Command: /csrd:taxonomy-alignment

Structure the evaluation of a specific economic activity against the EU Taxonomy.

## Output Format
```
EU TAXONOMY ALIGNMENT EVALUATION
Activity: [NACE Code / Description, e.g., 6.5 Transport by motorbikes, passenger cars and light commercial vehicles]
Target Objective: [Climate Change Mitigation]

1. SUBSTANTIAL CONTRIBUTION (SC) TEST:
- Technical Criteria: Vehicle must have zero tailpipe CO2 emissions (e.g., electric/hydrogen).
- Fleet Status Assessment: 400 of our 1000 fleet vehicles are battery-electric.
- SC Pass? ☐ YES (for the 400 EV vehicles) ☐ NO (for ICE vehicles)

2. DO NO SIGNIFICANT HARM (DNSH) TEST (Applied to the EVs):
- Climate Adaptation: Climate risk assessment conducted for main fleet depots? [Yes]
- Water/Marine: Wash bays have compliant wastewater capture? [Yes]
- Circular Economy: Are vehicles highly recyclable? Are EV batteries sent to compliant secondary life/recycling facilities? [Action required: Need end-of-life battery contracts from leasing company].
- Pollution: Do tires comply with external rolling noise requirements? [Action required: Request tyre certs from fleet manager].
- DNSH Pass? ☐ PENDING EVIDENCE

3. MINIMUM SOCIAL SAFEGUARDS (MSS) TEST:
- OECD/UNGP Compliance: Does the company have robust human rights due diligence, anti-bribery, and fair taxation policies? [Yes, validated via group level policies].
- MSS Pass? ☐ YES

ALIGNMENT RESULT:
Eligible CapEx: [€ Total fleet spend]
Aligned CapEx: [€ Zero for now, pending DNSH tire/battery evidence. Once resolved, € spend on the 400 EVs will be aligned.]
```
