# Inventory Management & Control
Manage parts inventory to balance availability and cost:

### Inventory Classification (ABC Analysis)
| Class | % of Items | % of Value | Control Level |
|-------|-----------|-----------|---------------|
| A | 10-20% | 70-80% | Tight: frequent review, safety stock, dual source |
| B | 20-30% | 15-20% | Moderate: periodic review, standard reorder |
| C | 50-70% | 5-10% | Basic: reorder when depleted, bulk buy |

### Key Inventory Metrics
- **Inventory turns**: Cost of goods consumed ÷ Average inventory value. Higher = more efficient. Target: depends on industry (2-4 for MRO, 4-12 for production).
- **Fill rate**: % of requests filled from stock. Target: ≥95% for critical parts.
- **Stockout rate**: % of requests that cannot be filled. Target: <2% for critical parts.
- **Dead stock**: Items with no usage in 12+ months. Review and dispose to free capital and space.

### Reorder Point Calculation
```
Reorder Point = (Average Daily Usage × Lead Time in Days) + Safety Stock
Safety Stock = Z × σ × √L
  Z = service level factor (1.65 for 95%, 2.33 for 99%)
  σ = standard deviation of daily demand
  L = lead time in days
```
- Use an ERP/CMMS system to automate reorder triggers.
- Review and adjust safety stock levels quarterly based on actual usage patterns.
