# Command: /eu-proc:award-criteria-matrix

Draft a Best Price-Quality Ratio scoring matrix for tender documents.

## Output Format
```
AWARD CRITERIA MATRIX (BPQR Scheme)
Contract: [Name]

OVERALL WEIGHTING: Price [X]% | Quality [X]%

1. PRICE/COST EVALUATION ([X]%)
Formula: Score = (Lowest Submitted Price / Evaluated Price) × [Max Points]
*Explanation: Ensures the lowest bidder receives maximum points, with others scored proportionally relative to the lowest bid.*

2. QUALITATIVE EVALUATION ([X]%)

Criterion 1: Technical Methodology ([X] points)
- Focus: Assessment of the proposed approach to deliver the services, risk management plan, and quality assurance framework.
- Scoring Guide: 0=Unacceptable, 1-3=Poor/Below Avg, 4-6=Acceptable, 7-8=Good, 9-10=Excellent.

Criterion 2: Team Organization & Experience ([X] points)
- Focus: Assessment of the CVs of key personnel allocated to the project, demonstrating specific relevant experience beyond minimum selection criteria.
- Scoring Guide: [As above]

Criterion 3: Sustainability & Social Value ([X] points)
- Focus: Proposal for minimizing carbon footprint during service delivery and providing training opportunities.
- Scoring Guide: [As above]

TIE-BREAKER RULE:
In the event of equal total scores, the tender with the highest score in [Criterion 1: Technical Methodology] will be awarded the contract.
```
