# Command: /clerk:foia-review

Generate a FOIA/public records request response worksheet.

## Output Format
```
PUBLIC RECORDS REQUEST
Request #: [number] | Date Received: [date]
Requester: [name] | Method: [email/mail/in-person]
Response Due: [date per statute]

RECORDS REQUESTED:
[Description as stated by requester]

SEARCH CONDUCTED:
Department(s) Searched: [list]
Keywords/Criteria: [search terms]
Records Found: [X] pages/documents

EXEMPTION REVIEW:
☐ No exemptions — full disclosure
☐ Partial exemption — redactions applied:
  [Cite specific statutory exemption for each redaction]
☐ Full denial — [statutory basis]

FEES:
Copying: [X] pages × $[X] = $[X]
Search time: [X] hours × $[X] = $[X]
Total: $[X]

RESPONSE SENT: [date] | Method: [email/mail/pickup]
```
