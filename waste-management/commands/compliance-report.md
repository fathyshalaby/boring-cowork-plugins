# Command: /waste:compliance-report

Generate a monthly or quarterly regulatory compliance status report.

## Output Format
```
REGULATORY COMPLIANCE STATUS REPORT
Period: [Month/Quarter Year]
Facility: [name] | Permit #: [number]

PERMIT STATUS:
Permit Type         Status        Expiration    Action Needed
────────────────────────────────────────────────────────────
Solid Waste Permit  Active        [date]        None
Air Quality Permit  Active        [date]        Renewal due [date]
Stormwater NPDES    Active        [date]        DMR due [date]
Scale Certificate   Active        [date]        Calibration due [date]

MONITORING & TESTING:
Test                Frequency    Last Done     Next Due      Result
────────────────────────────────────────────────────────────────────
Groundwater         Quarterly    [date]        [date]        Pass
Leachate Analysis   Monthly      [date]        [date]        Pass
Gas Monitoring      Quarterly    [date]        [date]        Pass
Stormwater          Per event    [date]        [date]        Pass

INCIDENTS & VIOLATIONS:
[List any NOVs, spills, complaints, or incidents]

TRAINING COMPLETED:
[List training sessions completed during the period]

CORRECTIVE ACTIONS:
[Status of any open corrective action items]
```
