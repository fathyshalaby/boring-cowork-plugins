# Command: /billing:patient-statement

Generate a clear, patient-friendly billing statement.

## Output Format
```
[Practice Logo/Name]
[Practice Address]
[Phone] | [Website]

STATEMENT DATE: [date]
ACCOUNT #: [number]

[Patient Name]
[Patient Address]

──────────────────────────────────────────────────────────
YOUR ACCOUNT SUMMARY

Previous Balance:                            $[X]
Payments Received (Thank You!):             ($[X])
Insurance Adjustments:                      ($[X])
New Charges:                                 $[X]
                                             ──────
AMOUNT DUE:                                  $[X]

PAYMENT DUE BY: [date]

──────────────────────────────────────────────────────────
DETAIL OF CHARGES:

Date        Service              Charge    Insurance   You Owe
──────────────────────────────────────────────────────────────
[date]      [description]        $[X]      ($[X])      $[X]

──────────────────────────────────────────────────────────

PAYMENT OPTIONS:
💳 Online: [payment portal URL]
📞 Phone: [number]
📮 Mail: [address]

Need help understanding your bill? Call us at [number].
Payment plans are available for balances over $[X].
```
