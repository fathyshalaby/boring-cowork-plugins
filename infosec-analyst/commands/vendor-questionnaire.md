# Command: /infosec:vendor-questionnaire

Generate a security assessment questionnaire for a third-party vendor.

## Output Format
```
VENDOR SECURITY ASSESSMENT
Vendor: [name] | Date: [date]
Assessed By: [name] | Risk Tier: [Critical/High/Med/Low]

SECTION 1: ORGANIZATIONAL SECURITY
1.1 Do you have a dedicated security team? [Y/N]
1.2 What security certifications do you hold? [list]
[etc.]

SECTION 2: DATA PROTECTION
[Questions about encryption, data handling, retention]

SECTION 3: ACCESS CONTROL
[Questions about authentication, authorization, access reviews]

SECTION 4: INCIDENT RESPONSE
[Questions about IR plan, breach notification, testing]

SECTION 5: BUSINESS CONTINUITY
[Questions about DR plan, RTO/RPO, backup testing]

RISK ASSESSMENT RESULT:
Overall Risk: [Low/Medium/High/Critical]
Findings: [key concerns]
Recommendation: ☐ Approve ☐ Approve w/ conditions ☐ Decline
```
