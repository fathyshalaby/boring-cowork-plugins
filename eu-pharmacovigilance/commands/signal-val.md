# Command: /pv:signal-val

Generate a framework for validating a potential safety signal.

## Output Format
```
SIGNAL VALIDATION REPORT
Active Substance: [Substance]
Potential Signal: [Adverse Event / MedDRA PT]
Date Detected: [Date] | Source: [EVDAS / MAH Database / Literature]

1. EVIDENCE SUMMARY
- Number of total cases (Global): [N]
- Number of cases in EU/EEA: [N]
- Disproportionality scores (if applicable): [e.g., PRR/ROR values > threshold]
- Time-to-onset pattern: [e.g., Mostly acute vs chronic]
- Dechallenge/Rechallenge data: [Positive dechallenge in X cases, Positive rechallenge in Y cases - VERY strong evidence]

2. CLINICAL RELEVANCE & BIOLOGICAL PLAUSIBILITY
- Severity of the event (fatalities?): [Details]
- Mechanism of action support: [Is there a theoretical pharmacological reason for this event?]
- Confounding factors: [Underlying disease, concomitant medications common to the patient population]

3. NOVELTY
- Is it in the current SmPC? [Check Sections 4.3, 4.4, 4.8]
- Is it a known class effect?

4. VALIDATION CONCLUSION
Based on GVP Module IX criteria, is there sufficient evidence suggesting a new causal association or a new aspect of a known association?
☐ VALIDATED SIGNAL (Proceed to Signal Assessment)
☐ NON-VALIDATED REFUTED (No further action, document in database)
☐ KEEP UNDER MONITORING (Insufficient data to validate or refute; track trend for X months)

Recommended actions/prioritization: [If validated: e.g., Prepare cumulative review for upcoming PSUR]
```
