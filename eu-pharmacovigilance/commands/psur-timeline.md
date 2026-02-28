# Command: /pv:psur-timeline

Calculate drafting and submission deadlines based on a Data Lock Point.

## Output Format
```
PSUR SUBMISSION TIMELINE PLANNER
Product: [Product Name] | Active Substance: [Substance Name]
PSUSA Procedure Number: [PSUSA/XXXX/YYYYMM]
EURD List Data Lock Point (DLP): [Date]

DEADLINE CALCULATION
Reporting Interval: [e.g., 6 months, 1 year, 3 years]
Applicable Regulatory Deadline format: [70 Days (for <=12m interval) or 90 Days (for >12m interval)]
Regulatory Submission Deadline: [DLP + 70/90 days]

INTERNAL DRAFTING MILESTONES (Working backward from Submission)
- T-Minus 0: SUBMISSION via PSUR Repository [Date]
- T-Minus 7 days: Final QPPV Review & Sign-off [Date]
- T-Minus 14 days: Cross-functional review complete (Medical, Regulatory, PV) [Date]
- T-Minus 21 days: First Draft compilation complete [Date]
- T-Minus 35 days: Medical writing & Signal evaluation drafted [Date]
- T-Minus 45 days: Line listings & Summary tabulations generated from Safety Database [Date]
- DLP: Database cut-off [Date]
- T-Plus (Pre-DLP): Clean open cases, ensure coding accuracy prior to lock.

CRITICAL ASSESSMENTS REQUIRED FOR THIS PERIOD:
- Review of actions taken for safety reasons.
- Updates to Reference Safety Information (RSI).
- Overview of signals (new, ongoing, closed).
```
