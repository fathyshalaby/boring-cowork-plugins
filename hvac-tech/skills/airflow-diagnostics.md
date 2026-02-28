# Airflow Diagnostics & Duct Design
Diagnose and resolve airflow problems, which are the #1 cause of comfort complaints:

### Measuring Airflow
- **Temperature split (Delta-T)**: Measure return air temp and supply air temp across the coil. Cooling: 14–22°F delta-T. Heating: 40–70°F delta-T (varies by equipment).
- **Static pressure**: Measure external static pressure (ESP) at the supply and return plenums with a manometer. Target: Equipment rated ESP (typically 0.50" WC). Above 0.80" WC indicates duct problems.
- **CFM per ton**: Standard airflow is 400 CFM per ton of cooling. An under-performing blower or restricted duct drops this, causing frozen coils and poor dehumidification.

### Common Airflow Problems
| Symptom | Likely Cause | Fix |
|---------|-------------|-----|
| High static pressure, low airflow | Dirty filter, undersized ductwork, collapsed flex duct | Replace filter, resize ducts, repair flex |
| Low static, low airflow | Blower motor failing, wrong fan speed setting | Check capacitor, amp draw, speed tap |
| Rooms too hot/cold | Missing or disconnected duct runs, damper closed, undersized branch | Inspect ductwork, open dampers, add runs |
| Humidity too high with AC running | Airflow too high (oversized blower) or too low (dirty coil) | Adjust fan speed, clean coil |

### Duct Design Principles
- **Return air**: 1 sq. inch of return grille per 1 CFM. A 3-ton system (1200 CFM) needs at least 1200 sq. inches of return grille.
- **Flex duct**: Maximum 25-foot run. Must be fully extended (not bunched up). Every bend reduces airflow.
- **Duct sealing**: Seal all joints with mastic (not duct tape—it fails within 5 years).
