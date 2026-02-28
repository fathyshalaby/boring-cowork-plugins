# Command: /csrd:dma-matrix

Generate a framework for assessing impact and financial materiality for a specific ESG topic.

## Output Format
```\DOUBLE MATERIALITY ASSESSMENT LOG
Topic: [e.g., ESRS E5 - Resource Use and Circular Economy]
Sub-topic: [e.g., Packaging Waste]
Business Context: [e.g., E-commerce retailer distributing 5M packages/year]

1. IMPACT MATERIALITY (Inside-Out)
Scale: [1-5]: [Justification: Volume of single-use plastic entering environment]
Scope: [1-5]: [Justification: Geographic spread of waste distribution]
Irremediability/Remediability: [1-5]: [Justification: Ocean plastic degradation timeline]
Severity Score (Scale x Scope x Irrem): [XX]
Likelihood (for potential impacts): [1-5]
Total Impact Score: [XX/125]
Conclusion Impact: ☐ MATERIAL  ☐ NOT MATERIAL

2. FINANCIAL MATERIALITY (Outside-In)
Risks: [e.g., Upcoming Extended Producer Responsibility (EPR) packaging taxes across EU, increasing raw material costs for virgin plastics]
Opportunities: [e.g., Cost reduction through reusable packaging loop, competitive advantage in B2B public procurement]
Financial Magnitude: [Low/Med/High - e.g., Estimated €2M annual tax liability impact]
Likelihood of occurrence: [Low/Med/High]
Total Financial Risk/Opp: [XX]
Conclusion Financial: ☐ MATERIAL  ☐ NOT MATERIAL

OVERALL ASSESSMENT
Final Decision: [MATERIAL - Included in CSRD Scope]
Relevant ESRS Data Points required: [E5-1 through E5-6]
```
