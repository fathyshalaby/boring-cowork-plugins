# Command: /eu-proc:procedure-selector

Generate recommendations for the appropriate procurement procedure based on project specifics.

## Output Format
```
PROCUREMENT PROCEDURE RECOMMENDATION
Project: [Name]
Estimated Value: [€ Amount]
Sector/Type: [Supplies / Services / Works]

1. THRESHOLD ANALYSIS
- Current EU Threshold for this type: [€ Amount]
- Status: [Above/Below EU Threshold -> Directives Apply / National Law Applies]

2. RECOMMENDED PROCEDURE
Primary Recommendation: [e.g., Open Procedure / Restricted Procedure]
Alternative: [e.g., Competitive Procedure with Negotiation]

3. RATIONALE & JUSTIFICATION
- [Why this procedure fits best, e.g., "The Open Procedure is recommended due to the standard nature of these IT supplies, maximizing competition while keeping administrative overhead low."]
- [If suggesting Negotiation/Dialogue: "Justified under Art. 26(4) because the contract requires design/innovative solutions that cannot be established with precision upfront."]

4. STATUTORY DEADLINES (For Recommended Procedure)
- Minimum time for receipt of tenders: [X] days from Contract Notice.
- Standstill period: 10 days post-award notification.
```
