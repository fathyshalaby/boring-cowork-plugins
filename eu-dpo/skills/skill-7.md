# International Data Transfers
Navigate the complex rules for transferring data outside the EEA (Chapter V):

### Transfer Hierarchy
Data can only be transferred to a third country (outside EEA) if one of the following mechanisms is used:

1. **Adequacy Decision (Art. 45)**: The EU Commission has deemed the country has an adequate level of protection (e.g., UK, Japan, Canada (commercial), New Zealand, Switzerland). Data flows freely.
2. **Appropriate Safeguards (Art. 46)**: 
   - **Standard Contractual Clauses (SCCs)**: The most common mechanism. Pre-approved templates adopted by the EC. Cannot be modified (except to add commercial clauses that don't contradict the SCCs).
   - **Binding Corporate Rules (BCRs)**: For intra-group transfers within a multinational corporation. Requires SA approval.
3. **Derogations (Art. 49)**: For specific, occasional situations (e.g., explicit consent, necessary for a contract between the subject and controller, establishing legal claims). Cannot be used for systematic, bulk transfers.

### Schrems II & Transfer Impact Assessments (TIA)
The landmark CJEU ruling (Schrems II) invalidated the US Privacy Shield and placed additional burdens on SCC users:
- You must verify, on a case-by-case basis, whether the law of the destination country ensures adequate protection (often focusing on government surveillance laws like US FISA 702).
- Conduct a **Transfer Impact Assessment (TIA)**.
- If protection isn't adequate, you must implement **Supplementary Measures** (technical, organizational, contractual), such as strong encryption where the keys remain in the EU.
- Note: The EU-US Data Privacy Framework (DPF) adopted in July 2023 provides a new adequacy decision for certified US companies, simplifying transfers for those entities.
