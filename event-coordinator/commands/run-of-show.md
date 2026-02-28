# Command: /events:run-of-show

Generate a minute-by-minute run-of-show document for event day execution.

## Output Format
```
RUN OF SHOW
Event: [name] | Date: [date] | Venue: [name]
Event Manager: [name] | Phone: [number]

TIME        ACTIVITY                RESPONSIBLE     AV/LIGHTING    NOTES
──────────────────────────────────────────────────────────────────────────
[time]      [activity]             [person]        [cue]          [note]
[etc.]

EMERGENCY CONTACTS:
Venue: [name/phone] | AV: [name/phone] | Caterer: [name/phone]
Security: [name/phone] | First Aid: [location]
```
