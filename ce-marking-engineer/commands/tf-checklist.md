# Command: /ce:tf-checklist

Generate an audit checklist for Technical File compiled documentation.

## Output Format
```
TECHNICAL FILE AUDIT CHECKLIST
Product: [Name/Model]
Date of Audit: [Date] | Auditor: [Name]

1. PRODUCT IDENTIFICATION [Status: Pass/Fail/Missing]
☐ General description
☐ Marketing material/brochures
☐ Serial number definition/tracking

2. DESIGN DOCUMENTS [Status: Pass/Fail/Missing]
☐ BOM (Bill of Materials) identifying critical safety components
☐ CE/UL certs for sub-components collected
☐ Electrical schematics (wiring diagrams, PCB layouts)
☐ Mechanical/Assembly drawings

3. RISK & STANDARDS [Status: Pass/Fail/Missing]
☐ List of applied Directives & Harmonized Standards
☐ Documented Risk Assessment (signed)
☐ Essential Requirements (EHSR) Matrix mapping

4. TEST REPORTS [Status: Pass/Fail/Missing]
☐ LVD/Safety Test Report (internal or ISO 17025 lab)
☐ EMC Test Report (Emissions & Immunity)
☐ Ingress Protection (IP) rating proof (if claimed)
☐ Software validation documentation (if safety critical)

5. USER INFORMATION [Status: Pass/Fail/Missing]
☐ User Manual (Original language)
☐ Warning label artwork (ISO 7010 compliant)
☐ Data plate layout (must show CE mark, Mfg address, specs)

6. DECLARATION [Status: Pass/Fail/Missing]
☐ Signed EU Declaration of Conformity
```
