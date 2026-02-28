# Boring Cowork Plugins

This repository contains a collection of 41 highly-specialized plugins designed for [Claude Cowork](https://claude.com/product/cowork) and Claude Code, targeting high-ROI "boring" sectors that involve heavy data parsing, customer communication, and complex domain knowledge.

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
12. **`municipal-clerk`**: Zoning ordinances, Sunshine Law, meeting minutes formatting, FOIA.
13. **`hoa-manager`**: CC&R enforcement, vendor bid analysis, architectural reviews.
14. **`fleet-manager`**: PM scheduling, telematics analysis, DOT compliance check, TCO calculations.
15. **`commercial-cleaner`**: QA inspection reporting, SSOPs, shift coverage, inventory run rates.
16. **`elevator-tech`**: ASME A17.1 compliance, diagnostic trees, LOTO protocol, parts requisition.
17. **`osha-officer`**: OSHA 1910/1926 citations, JHA generation, hierarchy of controls, incident reporting.
18. **`food-safety`**: HACCP critical limits, mock recall tracing, ATP swabbing analysis, GMP audits.
19. **`pest-control`**: IPM strategies, chemical application logs, REI intervals, pest identification.
20. **`agronomist`**: Soil test N-P-K calculations, crop rotation modeling, economic threshold evaluation.
21. **`parts-expeditor`**: BOM shortage analysis, supplier scorecards, WIP expediting, PO discrepancy.
22. **`grant-writer`**: RFP formatting, budget narratives, compliance checking, DoE/NIH guidelines.
23. **`urban-planner`**: Demographic data synthesis, municipal codes, drafting comprehensive plans.
24. **`patent-examiner`**: Prior art search, USPTO office actions, 101/102/103 rejections.
25. **`technical-writer`**: OpenAPI specs conversion, Markdown/MDX formatting, Swagger UI.
26. **`customs-broker`**: HTS classification, Rules of Origin, USMCA verification, CBP compliance.
27. **`infosec-analyst`**: SOC 2 mapping, vendor security questionnaires, risk assessments, GDPR.
28. **`university-registrar`**: Transfer credit equivalencies, degree audits, catalog requirements, FERPA.
29. **`digital-archivist`**: Dublin Core/MARC schemas, finding aids, provenance descriptions, OCR cleanup.
30. **`clinical-trial-coord`**: Protocol summaries, IRB submissions, patient consent forms, SAE reports.
31. **`actuary`**: Actuarial memos, premium justifications, loss ratio analysis, state DOI rate filings.
32. **`eu-dpo`**: GDPR compliance, DPIAs, Article 28 DPA reviews, DSAR responses, RoPA.
33. **`eu-grant-specialist`**: Horizon Europe proposals, consortium management, DNSH principles, pathways to impact.
34. **`ce-marking-engineer`**: Machinery Directive, EN ISO 12100 risk assessments, Declarations of Conformity.
35. **`eu-reach-specialist`**: ECHA compliance, SVHC declarations, PCN/UFI generation, CLP classifications.
36. **`eu-pharmacovigilance`**: EMA regulations, ICSR narratives, MedDRA coding, PSUR summaries.
37. **`works-council-hr`**: EU co-determination laws, Betriebsrat consultation memos, redundancy matrices.
38. **`eu-procurement-officer`**: OJS TED notices, ESPD reviews, MEAT scoring matrices, Alcatel letters.
39. **`csrd-reporting-analyst`**: ESRS alignment, double materiality assessments, Scope 3 methodology.
40. **`euipo-paralegal`**: Nice Classifications, absolute/relative grounds defense, Cease & Desist letters.
41. **`a1-mobility-specialist`**: EU Regulation 883/2004, multi-state worker analysis, SIPSI declarations.

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
