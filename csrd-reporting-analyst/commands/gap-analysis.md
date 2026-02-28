# Command: /csrd:gap-analysis

Generate a gap analysis template for a specific ESRS Disclosure Requirement (DR).

## Output Format
```
ESRS GAP ANALYSIS
Standard: [e.g., ESRS S1 - Own Workforce]
Disclosure Requirement: [e.g., S1-6: Characteristics of the undertaking's employees]

REQUIREMENTS (Based on ESRS specification):
1. Total number of employees by headcount.
2. Breakdown by gender.
3. Breakdown by geographic region (≥ 10% of total).
4. Breakdown by contract type (Permanent, Temporary). Breakdown by gender for temporary.
5. Breakdown by working time (Full-time, Part-time). Breakdown by gender for part-time.

CURRENT STATE ASSESSMENT:
- Current capability: HRIS system (Workday) captures headcount, gender, and full-time/part-time status for EU employees smoothly.

IDENTIFIED GAPS:
1. Temporary vs. Permanent contracts are incorrectly classified in North American branches within the HRIS.
2. We do not currently report "Non-guaranteed hours employees" (zero-hour contracts) systematically, which is a required sub-point.

REMEDIATION ACTION PLAN:
- Action: Audit and recategorize contract types in HRIS for NA/APAC regions. Define standard operating procedure for zero-hour contract tagging.
- Owner: VP Global HR Operations
- Target Resolution: [Date]

AUDIT READINESS RATING: [Red/Amber/Green]
```
