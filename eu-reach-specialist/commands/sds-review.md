# Command: /reach:sds-review

Generate an audit checklist for evaluating a supplier's Safety Data Sheet.

## Output Format
```
SDS COMPLIANCE AUDIT
Mixture Name: [Name] | Supplier: [Company]
Date of SDS: [Date] | Reviewed By: [Name]

FORMAT & LEGAL BASIS
☐ Follows REACH Annex II format (16 Sections)
☐ Language matches country of use: [Country/Language]
☐ Date is recent (Within last 2-3 years indicating tracking of CLP updates)

CRITICAL SECTIONS REVIEW
Sec 1.1: UFI number present? (Required for hazardous mixtures)
Sec 1.2: Are our company's uses (e.g., industrial spraying) identified?
Sec 2: Hazard identification (CLP classifications, H-phrases) clearly stated?
Sec 3: Are all hazardous ingredients listed with their EC/CAS and concentration ranges?
Sec 8: Specific Occupational Exposure Limits (OELs) and precise PPE requirements (e.g., specific glove material and breakthrough time, not just "wear gloves") listed?
Sec 15: Regulatory info (e.g., SVHC presence, Annex XVII restrictions) populated?

EXPOSURE SCENARIOS (eSDS)
☐ Attached? (If No, substance may be registered <10t/y or not dangerous)
☐ If Yes, does ES #[X] cover our operational conditions and RMMs?

ACTIONABLE FINDINGS:
[List discrepancies or actions needed by EHS/Management based on the SDS]
```
