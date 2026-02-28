# Command: /pv:rmp-summary

Generate an overview of the Safety Specification and Risk Minimization measures from a product RMP.

## Output Format
```
RISK MANAGEMENT PLAN (RMP) SUMMARY
Product: [Product Name] | Active Substance: [Substance]
RMP Version: [Version] | Date: [Date]

PART II: SAFETY SPECIFICATION

Important Identified Risks:
1. [Risk, e.g., Hepatotoxicity]
2. [Risk, e.g., Anaphylaxis]

Important Potential Risks:
1. [Risk, e.g., Carcinogenicity based on animal models]

Missing Information:
1. [E.g., Use in pregnancy and lactation]
2. [E.g., Use in patients with severe renal impairment]

PART V: RISK MINIMISATION MEASURES (RMM)

For Identified Risk 1: [e.g., Hepatotoxicity]
- Routine RMM: [SmPC Warning in Sec 4.4, Contraindication in severe hepatic impairment Sec 4.3]
- Additional RMM: [Yes/No - if Yes: e.g., DHPC to hepatologists; Educational materials for prescribers detailing Required LFT monitoring schedule]

For Missing Info 1: [e.g., Pregnancy]
- Routine RMM: [SmPC Sec 4.6 advice against use unless clearly necessary]
- Additional PV Activities (Part III): [e.g., Establishment of a Pregnancy Registry]

IMPLEMENTATION STATUS:
[Brief note on whether additional measures are fully approved by NCAs and rolled out]
```
