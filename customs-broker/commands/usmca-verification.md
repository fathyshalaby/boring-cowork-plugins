# Command: /customs:usmca-verification

Generate a USMCA rules of origin verification worksheet.

## Output Format
```
USMCA ORIGIN VERIFICATION
Product: [description] | HTS: [code]
Exporter: [name/country] | Producer: [name/country]

ORIGIN CRITERION:
☐ A – Wholly obtained/produced
☐ B – Produced exclusively from originating materials
☐ C – Tariff shift rule met
☐ D – Regional value content met

TARIFF SHIFT ANALYSIS:
Non-originating input    HTS    Origin    Shift Required    Shift Met?
[material]               [code] [country] [rule]            [Y/N]

RVC CALCULATION (if applicable):
Method: ☐ Transaction Value  ☐ Net Cost
TV/NC: $[X] | VNM: $[X] | RVC: [X]%
Minimum Required: [X]% → ☐ Met ☐ Not Met

DETERMINATION: ☐ Qualifies  ☐ Does Not Qualify
```
