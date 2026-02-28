# Reserving & IBNR Estimation
Estimate loss reserves accurately using standard actuarial methods:

### Chain Ladder (Development Factor) Method
1. Organize paid or incurred losses into a development triangle (accident year/period × development period).
2. Calculate age-to-age development factors for each development period.
3. Select factors: Use all-year weighted average, exclude outliers, or use industry benchmarks.
4. Apply selected factors to the latest diagonal to project ultimate losses.
5. IBNR = Projected Ultimate - Incurred to Date.

### Bornhuetter-Ferguson (BF) Method
1. Estimate an a priori expected loss ratio (from pricing, industry data, or long-term averages).
2. Calculate the expected unreported portion = (1 - 1/CDF) × Expected Ultimate.
3. BF Ultimate = Reported Losses + Expected Unreported.
4. Advantage: Less sensitive to immature data than the chain ladder method.

### When to Use Which Method
| Method | Best For | Weakness |
|--------|---------|---------|
| Chain Ladder | Mature data with stable development | Volatile for immature years |
| Bornhuetter-Ferguson | Immature years, catastrophe-prone lines | Depends on a priori loss ratio selection |
| Expected Loss Ratio | Very immature or new lines with no history | Ignores actual emerging experience |
| Frequency × Severity | Detailed analysis, volatile lines | Requires more granular data |

### Reserve Adequacy Testing
- Run diagnostics: Compare actual development to expected development in subsequent periods.
- Track favorable/adverse development by accident year.
- Stress test reserves under alternative assumptions (higher severity inflation, slower reporting patterns).
- Document your reserve selections with supporting rationale (ASOP No. 43).
