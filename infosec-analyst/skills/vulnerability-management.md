# Vulnerability Management
Implement a vulnerability management program:

### Vulnerability Management Lifecycle
1. **Discovery**: Maintain an accurate asset inventory. You can't protect what you don't know about.
2. **Scanning**: Regular vulnerability scans. Authenticated scans are more accurate than unauthenticated.
3. **Prioritization**: CVSS score alone isn't enough. Factor in: exploitability (is there a public exploit?), asset criticality, exposure (internet-facing?), and compensating controls.
4. **Remediation**: Patch, reconfigure, or apply compensating controls. Assign owners and deadlines.
5. **Verification**: Re-scan to confirm remediation was successful.
6. **Reporting**: Track metrics over time.

### Patching SLAs
| CVSS Score | Severity | Remediation SLA |
|-----------|----------|----------------|
| 9.0-10.0 | Critical | 7 days (internet-facing: 48 hours) |
| 7.0-8.9 | High | 14 days |
| 4.0-6.9 | Medium | 30 days |
| 0.1-3.9 | Low | 90 days |

### Key Metrics
- **Mean Time to Remediate (MTTR)**: Average time from vulnerability discovery to remediation.
- **Scan coverage**: % of assets included in vulnerability scans. Target: 100%.
- **SLA compliance**: % of vulnerabilities remediated within SLA. Target: ≥90%.
- **Vulnerability density**: Vulnerabilities per asset. Track trend over time.
