# Command: /construction:punch-list

Generate a structured punch list for project closeout.

## Output Format
```
PUNCH LIST
Project: [name] | Date: [date]
Area/Floor: [description]
Walk performed by: [names and roles]

#    Location      Description                    Trade      Status
──────────────────────────────────────────────────────────────────────
1    Room 101      Drywall crack above door        Drywall    Open
2    Room 101      Paint touch-up at window trim   Painter    Open
3    Corridor      Ceiling tile misaligned         Ceiling    Open
4    Room 102      Outlet cover plate missing      Electrical Open
5    Room 102      Door closer adjustment needed   Doors      Open
[etc.]

TOTAL ITEMS: [X]
Completion Deadline: [date]

RESPONSIBLE PARTIES:
[Trade]: [X] items | Subcontractor: [company] | Foreman: [name/phone]

NOTES:
• All punch items must be completed before final payment release.
• Re-inspection scheduled for: [date]
```
