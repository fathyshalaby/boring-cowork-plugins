# Command: /inspect:summary

Generate a concise executive summary of the inspection findings for the client.

## Required Input
- Property address
- List of findings categorized by severity

## Output Format
```
PROPERTY INSPECTION SUMMARY
Property: [Address]
Date: [date] | Inspector: [name] | License: [number]

SAFETY HAZARDS (Immediate attention required):
• [Finding with location]

MAJOR DEFECTS (Significant repair/replacement needed):
• [Finding with location and estimated scope]

MINOR DEFECTS (Routine maintenance or minor repair):
• [Finding with location]

OVERALL CONDITION: [Good / Fair / Poor]
[2-3 sentence overall assessment]

Full detailed report with photographs to follow.
```
