# Command: /pv:capa-generator

Structure a CAPA plan for a pharmacovigilance deviation or audit finding.

## Output Format
```
PHARMACOVIGILANCE CAPA PLAN
Deviation/Finding ID: [ID] | Source: [Internal Audit / NCA Inspection / Internal Deviation]
Date Raised: [Date]

1. PROBLEM DESCRIPTION (The Finding)
[e.g., 5 Serious ICSRs from literature were submitted to EudraVigilance between 2 to 10 days late during Q3 2024.]

2. ROOT CAUSE ANALYSIS (RCA)
Method Used: [e.g., 5 Whys / Fishbone Diagram]
Identified Root Cause: [e.g., Literature screening vendor changed their email alert system, causing a delay in the delivery of abstracts to the MAH triage inbox. No backup mechanism was in place.]

3. CORRECTIVE ACTION (Immediate Fix)
Action: [e.g., Submit the 5 late cases (Already completed). Audit the vendor's outgoing queue to ensure no other cases are pending.]
Owner: [Name] | Target Date: [Date] | Status: [Completed]

4. PREVENTIVE ACTION (Systemic Fix)
Action 1: [e.g., Revise Vendor Management SOP to require a monthly reconciliation report between vendor logs and MAH inbox.]
Owner: [Name] | Target Date: [Date] | Status: [Open]
Action 2: [e.g., Establish a secondary automated alert for literature hits directly from the database source as a failsafe.]
Owner: [Name] | Target Date: [Date] | Status: [Open]

5. EFFECTIVENESS CHECK PLAN
Question: Did the actions permanently resolve the root cause?
Method: [e.g., Review the subsequent 3 months of literature reporting compliance metrics. Target: 100% on-time reporting via this source.]
Check Date: [Date + X months]
```
