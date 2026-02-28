# Command: /billing:eligibility-check

Generate a structured insurance eligibility verification worksheet.

## Output Format
```
INSURANCE ELIGIBILITY VERIFICATION
Date: [date] | Verified By: [name]
Patient: [name] | DOB: [date]

INSURANCE INFORMATION:
Payer: [name]
Plan Type: [PPO/HMO/EPO/POS/Medicare/Medicaid]
Member ID: [number]
Group #: [number]
Effective Date: [date]
Termination Date: [date or "Active"]

BENEFITS VERIFIED:
Coverage Active: ☐ Yes ☐ No
PCP Required: ☐ Yes (PCP: [name]) ☐ No
Referral Required: ☐ Yes ☐ No
Prior Auth Required for [service]: ☐ Yes ☐ No

PATIENT RESPONSIBILITY:
Annual Deductible: $[X] | Met to Date: $[X]
Copay (Office Visit): $[X]
Coinsurance: [X]%
Out-of-Pocket Max: $[X] | Met to Date: $[X]

ESTIMATED PATIENT COST FOR TODAY'S VISIT: $[X]

NOTES:
[Any special coverage limitations, carve-outs, or exclusions noted]

Verification Source: ☐ Portal ☐ Phone (Rep: [name], Ref#: [number])
```
