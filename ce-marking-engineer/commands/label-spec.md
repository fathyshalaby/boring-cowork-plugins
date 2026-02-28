# Command: /ce:label-spec

Generate the layout requirements for a compliant machine data plate.

## Output Format
```
DATA PLATE / CE LABEL SPECIFICATION
Product: [Name/Model]

MANDATORY CONTENT (Must be legible and indelible):

1. MANUFACTURER DETAILS:
   [Company Name]
   [Street, City, Postal Code, Country] (Must be physical address, not PO Box)
   
   *If non-EU Manufacturer, Authorized Rep Address must ALSO be visible somewhere on product.*

2. PRODUCT IDENTIFICATION:
   Type / Model Name: [Model]
   Serial Number: [S/N]
   Year of Construction: [YYYY]

3. TECHNICAL DATA:
   Voltage: [X] V  |  Phase: [X] ph
   Freq: [X] Hz   |  Full Load Amps: [X] A
   Short Circuit Rating (SCCR): [X] kA
   Weight: [X] kg (Mandatory if machine > 100kg limits limits manual handling)
   IP Rating: IP[XX]

4. CE MARKING:
   [CE logo placeholder]
   - Min height: 5mm
   - Keep proportions per Reg 765/2008
   - NB Number: [Add 4 digits if Applicable]

5. WEEE MARKING:
   [Crossed-out wheelie bin symbol] (Required if electronic)
```
