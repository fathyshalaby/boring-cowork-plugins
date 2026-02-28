# Command: /infosec:incident-summary

Generate a security incident summary report.

## Output Format
```
SECURITY INCIDENT REPORT
Incident ID: [X] | Severity: [SEV-1/2/3/4]
Date Detected: [date/time] | Date Resolved: [date/time]
Reported By: [name] | Incident Commander: [name]

EXECUTIVE SUMMARY:
[2-3 sentence summary for leadership]

TIMELINE:
Time          Event
──────────────────────────────────
[timestamp]   [event description]

IMPACT:
Systems Affected: [list]
Data Affected: [type, volume]
Business Impact: [description]

ROOT CAUSE: [description]

ACTIONS TAKEN:
[Containment, eradication, recovery steps]

LESSONS LEARNED:
1. [What went well]
2. [What needs improvement]
3. [Action items with owners and deadlines]

NOTIFICATION REQUIREMENTS:
☐ Regulatory (GDPR 72hr, state breach laws)
☐ Customer notification
☐ Law enforcement
```
