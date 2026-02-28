# Command: /reach:tonnage-tracker

Generate a template for tracking substance import volumes to evaluate registration thresholds.

## Output Format
```
REACH IMPORT TONNAGE TRACKER
Entity: [EU Importer Name]
Year: [YYYY]
Threshold Warning Level set to: 0.8 Tonnes (800kg)

SUBSTANCE INVENTORY & CALCULATION
#  Substance Name    CAS Number    Mixture/Import Source       Conc %   Total Vol (kg)   Substance Vol (kg)
──────────────────────────────────────────────────────────────────────────────────────────────────────────
1  [Acetone]         [67-64-1]     [Cleaning Solvent A, USA]   [80%]    [500]            [400]
2  [Acetone]         [67-64-1]     [Thinner B, China]          [100%]   [500]            [500]
                                                              ------------------------------------
   TOTAL ACETONE FOR YEAR [YYYY]:                                                          [900 kg] 
   STATUS: ⚠️ APPROACHING 1T/Y THRESHOLD

3. [Substance X]     [CAS-XX]      [Raw Material C, Japan]     [100%]   [1200]           [1200]
                                                              ------------------------------------
   TOTAL [Substance X] FOR YEAR [YYYY]:                                                    [1200 kg]
   STATUS: 🛑 REGISTRATION REQUIRED (>1t/y threshold breached)

ACTION PLAN:
- Substance X: Initiate Late Pre-registration/Inquiry to ECHA. Contact SIEF Lead Registrant for LoA cost.
- Acetone: Monitor next Q4 shipments tightly. Consider sourcing Cleaning Solvent A from an EU supplier to offload import registration burden.
```
