# Command: /trial:sae-report

Generate a Serious Adverse Event initial report.

## Output Format
```
SERIOUS ADVERSE EVENT REPORT (INITIAL)
Protocol: [name/number] | Site: [number]
Report Date: [date] | Report Type: ☐ Initial ☐ Follow-up ☐ Final

SUBJECT: ID: [X] | Age: [X] | Sex: [M/F]
STUDY TREATMENT: [drug/device] | Dose: [X] | Start Date: [date]

EVENT DETAILS:
SAE Term: [MedDRA preferred term]
Onset Date: [date] | Awareness Date: [date]
Seriousness Criteria:
  ☐ Death (date: [date])
  ☐ Life-threatening
  ☐ Hospitalization (admission: [date], discharge: [date])
  ☐ Disability/Incapacity
  ☐ Congenital anomaly
  ☐ Important medical event

NARRATIVE:
[Detailed description of the event, timeline, treatment, and outcome]

CAUSALITY ASSESSMENT (Investigator):
☐ Not related  ☐ Unlikely  ☐ Possibly  ☐ Probably  ☐ Definitely

OUTCOME:
☐ Ongoing  ☐ Recovered  ☐ Recovered with sequelae  ☐ Fatal  ☐ Unknown

ACTION TAKEN WITH STUDY TREATMENT:
☐ None  ☐ Dose reduced  ☐ Interrupted  ☐ Discontinued

Investigator Signature: _____________  Date: __________
```
