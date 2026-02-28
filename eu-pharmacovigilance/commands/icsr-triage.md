# Command: /pv:icsr-triage

Assess an incoming safety report for validity and expedited reporting requirements.

## Output Format
```
ICSR VALIDITY ASSESSMENT
Date of Receipt (Day 0): [Date]
Source: [e.g., Spontaneous Consumer, HCP, Literature, Clinical Study]

1. MINIMUM CRITERIA CHECK (Required for Validity)
☐ Identifiable Reporter (Name/Initials/Contact or HCP status identified): [Details]
☐ Identifiable Patient (Age/Gender/Initials): [Details]
☐ Suspected Medicinal Product: [Product Name]
☐ Suspected Adverse Event: [List events]
Result: ☐ VALID  ☐ INVALID (Missing info: [Identify missing elements. Must seek follow-up])

2. SERIOUSNESS CRITERIA (If Valid)
Did the event result in any of the following?
☐ Death
☐ Life-threatening
☐ Requires inpatient hospitalization or prolongation of existing hospitalization
☐ Results in persistent or significant disability/incapacity
☐ Is a congenital anomaly/birth defect
☐ Is an Important Medical Event (IME list check)
Result: ☐ SERIOUS (15-day timeline)  ☐ NON-SERIOUS (90-day timeline)

3. EXPECTEDNESS (If Valid & Serious)
Assessed against current Reference Safety Information (e.g., SmPC Section 4.8):
Is the event listed in the applicable RSI? ☐ YES (Expected)  ☐ NO (Unexpected)

4. REPORTING CONCLUSION (Expedited reporting to EudraVigilance)
☐ Valid, Serious, Unexpected (SUSAR/Expedited - 15 days)
☐ Valid, Serious, Expected (Expedited - 15 days)
☐ Valid, Non-Serious (Expedited - 90 days if originating in EU)
☐ Do Not Report Expedited (Reason: [e.g., Invalid, Non-serious non-EU case])
```
