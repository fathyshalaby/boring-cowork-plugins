# Command: /dpo:breach-log

Generate an internal log entry for a potential personal data breach.

## Output Format
```
INTERNAL DATA BREACH LOG
Incident ID: [Number]
Date of Incident: [Date] | Date Discovered: [Date/Time]
Reported By: [Name/Role]

NATURE OF THE BREACH
Type: ☐ Confidentiality (disclosure) ☐ Integrity (alteration) ☐ Availability (loss/destruction)
Description of events: [What happened, how it happened]

DATA & SUBJECTS AFFECTED
Categories of Data: [E.g., names, emails, financial, health]
Volume: Approx [Number] records
Categories of Subjects: [E.g., employees, customers, minors]

RISK ASSESSMENT
Likely consequences for individuals: [E.g., phishing risk, identity theft, minor inconvenience]
Overall risk to rights and freedoms: ☐ High ☐ Medium ☐ Low  ☐ None

NOTIFICATION DECISION
Notify Supervisory Authority (72h)? ☐ YES  ☐ NO (Justification if No)
Notify Data Subjects? ☐ YES  ☐ NO (Justification if No)

REMEDIAL ACTIONS TAKEN
[Measures taken to contain the breach and prevent recurrence]

DPO Sign-off: [Name and Date]
```
