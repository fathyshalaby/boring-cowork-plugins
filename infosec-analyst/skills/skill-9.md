# Security Monitoring & SIEM
Implement effective security monitoring:

### Log Sources to Monitor
| Source | Key Events |
|--------|------------|
| Firewall | Blocked connections, unusual outbound traffic |
| Authentication (AD/IdP) | Failed logins, impossible travel, privilege changes |
| Email gateway | Phishing attempts, malware blocked, suspicious attachments |
| Endpoint (EDR) | Malware detection, suspicious process execution, lateral movement |
| Cloud (AWS/Azure/GCP) | Console logins, IAM changes, unusual API calls, resource creation |
| Web application | SQL injection attempts, brute force, API abuse |
| VPN | Off-hours logins, geo-anomalies, concurrent sessions |

### Detection Engineering
- Start with high-fidelity detections: known bad (IOCs), impossible travel, new admin accounts, disabled security controls.
- Reduce false positives aggressively. Alert fatigue is the #1 enemy of effective monitoring.
- Use MITRE ATT&CK framework to map detection coverage. Identify gaps.
- Threat hunting: Proactive search for indicators of compromise that automated detections may miss.

### SIEM Best Practices
- Centralize logs in a SIEM (Splunk, Sentinel, Elastic, Chronicle).
- Normalize log formats for consistent searching.
- Retain logs for minimum 1 year (longer for compliance: PCI = 1 year, HIPAA = 6 years).
- Tune alert thresholds based on baseline behavior.
