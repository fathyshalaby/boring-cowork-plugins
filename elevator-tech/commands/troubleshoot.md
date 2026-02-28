# Command: /elevator:troubleshoot

Generate a structured troubleshooting worksheet for a reported fault.

## Output Format
```
TROUBLESHOOTING WORKSHEET
Unit: [ID] | Date: [date] | Tech: [name]
Reported Symptom: [description]
Fault Code (if any): [code]

DIAGNOSTIC STEPS:
Step  Action                           Result    Finding
──────────────────────────────────────────────────────────
1     [Check/test action]              [result]  [finding]
2     [Next logical test]              [result]  [finding]
3     [Narrowing down]                 [result]  [finding]

ROOT CAUSE: [determined cause]

REPAIR PERFORMED:
[Description of repair, parts replaced]

VERIFICATION:
☐ Unit tested and operating normally
☐ Multiple floor runs completed
☐ Fault code cleared

TIME: Arrived [time] | Completed [time] | Total: [X] hrs
```
