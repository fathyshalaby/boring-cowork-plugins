# Supply Chain Communication & BOM Scrubbing
Implement processes to gather REACH data from global suppliers:

### The Data Gathering Challenge
Manufacturers of complex articles cannot analyze every part in a lab. You must rely on supplier declarations (BOM scrubbing - Bill of Materials).

### Best Practices for Supplier Outreach
1. **Do not ask for "REACH Certificates"**: There is no such official thing. Ask for a "Declaration of REACH SVHC Compliance" mapped to the *current* Candidate List (include the date/number of SVHCs, e.g., "240 SVHCs as of Jan 2024").
2. **Use Standardized Formats**: Use industry standards like IPC-1752A or IEC 62474 for electronic data exchange, rather than custom Excel/PDF forms.
3. **Full Material Disclosure (FMD)**: The gold standard. Ask suppliers to provide the complete chemical composition of their parts. This insulates you from future SVHC list updates (you write a script to check your FMD database instead of emailing the supplier again).

### Red Flags in Supplier Declarations
- Vague statements: "Our products comply with REACH" (Do they mean registration, SVHCs, or restrictions?).
- Outdated lists: Referencing SVHC lists from 2 years ago.
- Flat-out denials for complex parts like PCBA or motors containing brass (brass universally contains Lead as an SVHC >0.1%).

### Component Analysis Priorities
Focus requests on high-risk materials:
- Soft plastics/PVC (Phthalates).
- Brass/Aluminum alloys (Lead).
- Flame retardants in plastics (SCCPs, DecaBDE).
- Adhesives/Sealants.
