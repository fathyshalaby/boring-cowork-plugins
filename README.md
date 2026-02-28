# Boring Cowork Plugins

This repository contains a collection of 11 highly-specialized plugins designed for [Claude Cowork](https://claude.com/product/cowork) and Claude Code, targeting high-ROI "boring" sectors that involve heavy data parsing, customer communication, and complex domain knowledge.

## The Plugins

Each plugin is equipped with exactly **10 domain-specific skills** and **5 executable commands**.

1. **`freight-dispatcher`**: Logistics, FMCSA Hours of Service, rate confirmations, load negotiations.
2. **`hvac-tech`**: Manual J load calculations, troubleshooting, refrigerant rules, customer quotes.
3. **`property-inspector`**: Defect classifications, objective reporting, building code observations.
4. **`facilities-management`**: OSHA compliance, PM scheduling, Capital Expense lifecycles.
5. **`waste-management`**: Hazmat classification, routing efficiency, container quotes.
6. **`real-estate-agent`**: CMA calculations, contract terminology, Fair Housing compliance, lead generation.
7. **`auto-repair-advisor`**: Technical translation to customers, flat-rate labor times, OEM warranty claims.
8. **`construction-super`**: CPM scheduling, delay notices, daily logs, subcontractor cure notices.
9. **`medical-biller`**: ICD-10/CPT coding extraction, insurance EOB analysis, denial appeals.
10. **`event-coordinator`**: Banquet Event Orders (BEOs), dietary matrices, venue RFPs.
11. **`claims-adjuster`**: Xactimate principles, depreciation calculation, formal Statements of Loss.

## How Plugins Work
Every plugin follows the standard structure:
```
plugin-name/
├── .claude-plugin/plugin.json   # Manifest
├── .mcp.json                    # Tool connections
├── commands/                    # Slash commands you invoke explicitly
└── skills/                      # Domain knowledge Claude draws on automatically
```

## Making Them Yours
These are starting points. Modify the `.mcp.json` to connect to your specific tools, or edit the `skills/` files to include your exact company terminology and processes.
