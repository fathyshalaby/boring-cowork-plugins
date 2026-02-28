# Command: /construction:change-order

Generate a formal Change Order Proposal (COP) for additional or changed work.

## Output Format
```
CHANGE ORDER PROPOSAL
COP #: [number] | Date: [date]
Project: [name]
To: [Owner/Owner's Rep]

DESCRIPTION OF CHANGE:
[Detailed description of the additional or changed work, referencing
the directive, RFI response, or field condition that requires the change]

REASON FOR CHANGE:
☐ Owner-directed change
☐ Design error/omission (Architect RFI #[number])
☐ Unforeseen field condition
☐ Code requirement
☐ Value engineering

COST BREAKDOWN:
Item                    Labor      Material    Equipment   Total
──────────────────────────────────────────────────────────────────
[Description]           $[X]       $[X]        $[X]        $[X]
Subtotal:                                                  $[X]
OH&P ([X]%):                                               $[X]
TOTAL PROPOSED CHANGE:                                     $[X]

TIME IMPACT:
☐ No time impact
☐ [X] calendar days added to the contract time

SUPPORTING DOCUMENTATION:
• [Sub quotes, material invoices, T&M tickets, photos, RFI reference]

This proposal is valid for [30] days from the date above.
```
