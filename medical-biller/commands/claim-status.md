# Command: /billing:claim-status

Generate a structured claim status inquiry for payer follow-up calls.

## Output Format
```
CLAIM STATUS INQUIRY

Date: [date] | Caller: [name]
Payer: [payer name] | Payer Phone: [number]
Payer Representative: [name] | Reference #: [call ref number]

CLAIM DETAILS:
Patient: [name] | DOB: [date] | Member ID: [number]
Provider: [name] | NPI: [number]
Date of Service: [date]
Claim #: [number] | Billed Amount: $[X]

CPT Codes Billed: [list]
ICD-10 Codes: [list]

STATUS INQUIRY RESULTS:
☐ Claim received – in processing
☐ Claim paid – Check/EFT #[number], Date: [date], Amount: $[X]
☐ Claim denied – Reason: [code and description]
☐ Claim pending – Reason: [description], Est. resolution: [date]
☐ Claim not on file – Resubmission needed

ACTION REQUIRED:
[Description of next steps]

NOTES:
[Additional information from the call]
```
