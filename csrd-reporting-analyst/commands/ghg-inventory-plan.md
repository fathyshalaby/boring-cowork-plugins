# Command: /csrd:ghg-inventory-plan

Draft a plan for identifying and calculating relevant Scope 3 GHG categories.

## Output Format
```
SCOPE 3 GHG EMISSIONS MAPPING PLAN (ESRS E1-6)
Company Profile: [e.g., Software/SaaS operations, mostly office-based]

STEP 1: SCREENING & RELEVANCE ASSESSMENT (Determining which of the 15 Categories matter)

Category 1: Purchased Goods & Services
- Relevance: HIGH. (Servers, cloud computing contracts, office IT equipment, consultant travel).
- Proposed Calc Method: Spend-based method initially, moving to Supplier-specific method for top 3 cloud providers next year.

Category 6: Business Travel
- Relevance: MED. (Flights, hotels for sales/executive teams).
- Proposed Calc Method: Distance-based method using flight logs from travel agency API.

Category 7: Employee Commuting
- Relevance: MED. (Commute impact for 1000 employees + Teleworking emissions).
- Proposed Calc Method: Average-data method based on annual employee commuting survey.

Category 11: Use of Sold Products
- Relevance: LOW/MED. (Power consumption of servers running our client software is complex to separate from client's total workload).
- Proposed Calc Method: Estimate based on average CPU draw per user session.

Categories 2,3,4,5,8,9,10,12,13,14,15: Assessed as immaterial/not relevant due to business model. Must document justification for exclusion.

STEP 2: DATA GATHERING TIMELINE
- [Date]: Issue travel data request to Concur/CWT.
- [Date]: Extrapolate spend data from Procurement ERP for Category 1.
- [Date]: Distribute employee commute survey.
```
