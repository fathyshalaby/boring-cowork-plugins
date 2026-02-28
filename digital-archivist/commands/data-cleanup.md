# Command: /archive:data-cleanup

Generate a metadata cleanup and standardization plan for a batch of records.

## Output Format
```
METADATA CLEANUP PLAN
Collection: [name] | Records: [count]

ISSUES IDENTIFIED:
Field         Issue              Count    Fix
─────────────────────────────────────────────────
[field]       [inconsistency]    [X]      [standardization rule]

STANDARDIZATION RULES:
1. Dates: Convert all to ISO 8601 (YYYY-MM-DD)
2. Names: Last, First Middle format per LCNAF
3. Subjects: Map free-text to LCSH controlled terms

ESTIMATED EFFORT: [X] hours
```
