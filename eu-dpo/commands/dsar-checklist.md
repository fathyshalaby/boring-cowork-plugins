# Command: /dpo:dsar-checklist

Generate a processing checklist for a Data Subject Access Request.

## Output Format
```
DATA SUBJECT ACCESS REQUEST (DSAR) CHECKLIST
Request ID: [ID] | Data Subject: [Name, Type (e.g. Employee/Customer)]
Date Received: [Date] | Deadline: [Date + 1 month]

VERIFICATION
☐ Identity verified [Method]
☐ Scope of request clarified (if necessary)

DATA GATHERING (Systems Searched)
☐ CRM / Customer Database
☐ HRIS (if employee)
☐ Email Archives / Communication tools
☐ Marketing Systems
☐ Processors/Third Parties contacted

REVIEW & REDACTION
☐ Third-party personal data redacted
☐ Legally privileged information withheld
☐ Commercial/Trade secrets withheld
☐ Exemptions applied (Log exemptions and justifications)

FINAL REVIEW
☐ Data collated into secure, machine-readable format
☐ Accompanying Article 15 information drafted (purposes, retention, rights list)
☐ Final review by DPO/Legal

DISPATCH
☐ Sent securely to Data Subject
☐ Logged in DSAR Register
☐ Date closed: [Date]

Internal Notes: [E.g., extensions applied, fee charged, refusal rationale]
```
