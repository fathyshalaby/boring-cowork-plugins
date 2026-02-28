# Command: /eu-grants:budget-calc

Generate a preliminary budget calculation for a specific partner in a Horizon Europe project.

## Output Format
```
PARTNER BUDGET CALCULATION
Partner: [Name]
Action Type: [RIA/IA/CSA] | Funding Rate: [100% or 70%]

A. PERSONNEL COSTS (Actual): 
- Senior Researcher: [X] PMs × €[Rate]/month = €[X]
- Junior/Post-Doc: [X] PMs × €[Rate]/month = €[X]
Total Personnel (A) = €[X]

B. SUBCONTRACTING: 
[Description of task] = €[X]
Total Subcontracting (B) = €[X]

C. PURCHASE COSTS:
- Travel (Meetings, Conferences) = €[X]
- Consumables/Supplies = €[X]
- Equipment (Depreciation only) = €[X]
Total Purchases (C) = €[X]

D. OTHER DIRECT COSTS (If applicable) = €[X]

E. INDIRECT COSTS (Overheads): 
(A + C + D) × 25% flat rate = €[X]
NOTE: Subcontracting (B) generates NO indirect costs.

TOTAL ESTIMATED ELIGIBLE COSTS: €[Total A+B+C+D+E]
MAXIMUM EU CONTRIBUTION: €[Total] × [Funding Rate]
```
