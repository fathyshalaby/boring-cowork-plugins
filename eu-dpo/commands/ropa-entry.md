# Command: /dpo:ropa-entry

Generate a new entry for the Article 30 Record of Processing Activities.

## Output Format
```
RECORD OF PROCESSING ACTIVITY (RoPA)
Business Process: [Name, e.g., Employee Payroll Processing]
Department/Owner: [Department Name]

PROCESSING DETAILS
Lawful Basis: [Art. 6 basis, e.g., Contract execution (Art.6(1)(b))]
Special Category Basis (if applicable): [Art. 9 exception, e.g., Employment Law (Art.9(2)(b))]
Purposes of Processing: [Why the data is used]

DATA & SUBJECTS
Categories of Individuals: [E.g., current and former employees]
Categories of Personal Data: [E.g., Name, bank details, tax ID, salary]

RECIPIENTS & TRANSFERS
Internal Access: [Roles/Departments with access]
Processors/Third Parties: [E.g., Workday, ADP, local tax authority]
International Transfers: ☐ Yes ☐ No | Destination: [Country] | Mechanism: [SCCs/Adequacy]

RETENTION & SECURITY
Retention Period: [Time limit, e.g., 7 years post-termination per tax law]
Deletion Trigger/Process: [How and when it is deleted]
Security Measures: [Brief desc. e.g., AES-256 encryption at rest, MFA access, RBAC]

DPO Review Date: [Date]
```
