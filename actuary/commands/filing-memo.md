# Command: /actuary:filing-memo

Generate a structured actuarial memorandum for a regulatory rate filing.

## Output Format
```
ACTUARIAL MEMORANDUM
Line of Business: [name]
State: [state] | Filing Type: [Rate Revision / New Program / Rule Change]
Effective Date: [date]
Prepared By: [name, credentials] | Date: [date]

I. EXECUTIVE SUMMARY
[1 paragraph: Overall indicated change, requested change, and financial impact]
Overall Indicated Change: [+/- X.X%]
Selected/Requested Change: [+/- X.X%]

II. BACKGROUND & SCOPE
[Description of the analysis scope, lines, states]

III. DATA
[Source, period, volume, known limitations]

IV. METHODOLOGY
[Step-by-step methodology with formulas and assumptions]
A. Loss Development: [method, selected LDFs]
B. Trend: [frequency trend, severity trend, selections]
C. Credibility: [standard, Z factor, complement]
D. Expense & Profit Provisions: [fixed, variable, target UW profit]

V. RESULTS
[Indicated rate changes by coverage/class with summary exhibit]

VI. RATE IMPACT
[Distribution of premium impact by customer segment]

VII. CERTIFICATION
I, [name], [credentials], am a member in good standing of the
[CAS/SOA] and meet the Qualification Standards for this opinion.

Signature: _______________  Date: __________
```
