# Command: /ce:directive-scout

Analyze a product description to identify likely applicable EU Directives/Regulations.

## Output Format
```
DIRECTIVES & REGULATIONS ANALYSIS
Product: [Product Description]

PRIMARY DIRECTIVES:
☐ [Directive Abbreviation] ([Directive Number])
Rationale: [Why it applies based on product specs]
Key Essential Requirement: [e.g., Electrical safety, Annex I EHSRs]

SECONDARY/HORIZONTAL DIRECTIVES:
☐ RoHS (2011/65/EU) - Restrict 10 hazardous substances in electronics.
☐ WEEE (2012/19/EU) - Take-back and recycling obligations.
☐ REACH (1907/2006) - Chemical usage in articles.

EXCLUSIONS / BORDERLINE CASES:
- [Directive Abbreviation]: This directive does NOT apply because [reference specific exclusion article].
- [Boundary conflict e.g., LVD vs MD]: According to MD 2006/42/EC Art 1(2)(k), this product falls solely under LVD.

RECOMMENDED CONFORMITY ROUTE:
- Likely Module: [Module A/B/etc.]
- Notified Body required? [Yes/No - Why]
```
