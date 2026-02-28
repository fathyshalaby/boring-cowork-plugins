# Command: /trial:consent-form

Generate an informed consent process checklist and compliance verification.

## Output Format
```
INFORMED CONSENT VERIFICATION
Protocol: [name/number] | ICF Version: [X] | IRB Approval Date: [date]

Subject: [ID] | Visit: [Screening/Re-consent]
Date of Consent: [date] | Time: [time]

CONSENT PROCESS CHECKLIST:
☐ Current IRB-approved ICF version used
☐ Subject given adequate time to review (not rushed)
☐ All pages of ICF reviewed with subject
☐ Subject's questions answered completely
☐ Subject signed and dated all required pages
☐ Person obtaining consent signed and dated
☐ Witness signature obtained (if applicable)
☐ Subject received a signed copy
☐ Original filed in regulatory binder
☐ Consent documented in source notes with date/time

CONSENT VERSION TRACKING:
Version    Date Approved    Changes Summary    Subjects Re-consented
──────────────────────────────────────────────────────────────────────
[X]        [date]           [Original]         N/A
[X]        [date]           [Amendment X changes]   [X of X]

NOTES: [Any special circumstances documented]
```
