# Command: /eu-proc:modification-check

Assess whether a proposed post-award contract modification requires a new tender.

## Output Format
```
CONTRACT MODIFICATION ASSESSMENT (Article 72 Check)
Contract Ref: [Number/Name]
Original Value: [€ Amount]
Proposed Modification Value: [€ Amount increase/decrease] ([X]% change)
Nature of Modification: [Brief description, e.g., adding an extension to the building / adding 6 months of software support]

SAFE HARBOR ANALYSIS (Does it fit one of these exceptions?)

☐ 1. Clear Review Clauses (Art. 72.1.a) -> [Analysis]
☐ 2. Necessary Additional Works/Services (Art. 72.1.b) -> [Analysis - Does it exceed 50%? Is changing contractor economically unviable?]
☐ 3. Unforeseeable Circumstances (Art. 72.1.c) -> [Analysis - Was the pandemic/war/geological issue truly unforeseeable by a diligent authority?]
☐ 4. Replacement of Contractor (Art. 72.1.d) -> [Analysis - e.g., standard M&A transfer?]
☐ 5. De Minimis (Art. 72.2) -> [Analysis - Is the value <10% (services) or <15% (works) AND below EU threshold?]

SUBSTANTIALITY TEST (If no safe harbors apply)
Would the change significantly alter the contract nature? Introduce conditions that would have allowed other bidders? Shift economic balance to contractor? Extend scope considerably?

CONCLUSION
☐ MODIFICATION LEGAL: Proceed under exception [X]. Requires publication of a Modification Notice on TED.
☐ MODIFICATION ILLEGAL: Too substantial. Requires a new procurement procedure.
```
