# Risk Assessment Methodology
Conduct security risk assessments to prioritize investments:

### Risk Assessment Process
1. **Asset inventory**: Identify all information assets (systems, data, applications, people).
2. **Threat identification**: What could go wrong? (malware, insider threat, natural disaster, supply chain compromise)
3. **Vulnerability identification**: What weaknesses exist? (unpatched systems, weak passwords, misconfiguration)
4. **Likelihood assessment**: How probable is this threat exploiting this vulnerability? (1-5 scale or qualitative)
5. **Impact assessment**: What's the business impact if this occurs? (financial, reputational, operational, legal)
6. **Risk calculation**: Risk = Likelihood × Impact. Produce a risk matrix.
7. **Risk treatment**: Accept, Mitigate, Transfer (insurance), or Avoid.

### Risk Matrix
```
              IMPACT
              Low(1)  Med(2)  High(3)  Crit(4)
LIKELIHOOD
High(4)       4       8       12       16
Med(3)        3       6       9        12
Low(2)        2       4       6        8
Rare(1)       1       2       3        4
```
- **13-16**: Critical — immediate action required
- **9-12**: High — action plan within 30 days
- **5-8**: Medium — action plan within 90 days
- **1-4**: Low — accept or monitor

### Common Pitfalls
- Assessing risk without understanding business context.
- Treating all risks equally instead of prioritizing by business impact.
- Not updating the risk register after changes (new systems, new threats, incidents).
