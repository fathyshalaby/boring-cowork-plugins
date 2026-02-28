# Command: /parts:supplier-scorecard

Generate a supplier performance scorecard.

## Output Format
```
SUPPLIER SCORECARD
Supplier: [name] | Period: [Q# Year]
Buyer: [name]

PERFORMANCE METRICS:
Metric               Target    Actual    Grade
─────────────────────────────────────────────────
On-Time Delivery     ≥95%      [X]%      [A-F]
Quality (Accept Rate) ≥98%      [X]%      [A-F]
Lead Time Accuracy   ≤105%     [X]%      [A-F]
Responsiveness       <24 hrs   [X] hrs   [A-F]

OVERALL GRADE: [A-F]

OPEN ISSUES:
[Quality, delivery, or responsiveness issues]

ACTION ITEMS:
[Agreed improvement actions with deadlines]

NEXT REVIEW: [date]
```
