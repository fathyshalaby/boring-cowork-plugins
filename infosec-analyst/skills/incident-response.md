# Incident Response
Prepare for and respond to security incidents:

### Incident Response Phases (NIST SP 800-61)
1. **Preparation**: IR plan, team, tools, training, communication templates, legal/PR contacts.
2. **Detection & Analysis**: Monitor alerts, triage, determine scope and severity, classify incident.
3. **Containment**: Short-term (isolate affected systems) and long-term (apply patches, change credentials).
4. **Eradication**: Remove the threat — malware, unauthorized accounts, backdoors.
5. **Recovery**: Restore systems from clean backups, verify integrity, monitor for recurrence.
6. **Post-Incident**: Lessons learned meeting within 5 business days. Update IR plan, controls, and detection rules.

### Incident Severity Levels
| Level | Definition | Response Time |
|-------|-----------|---------------|
| SEV-1 (Critical) | Active data breach, ransomware, system-wide outage | Immediate, all-hands |
| SEV-2 (High) | Confirmed compromise, significant impact | Within 1 hour |
| SEV-3 (Medium) | Suspected compromise, limited impact | Within 4 hours |
| SEV-4 (Low) | Policy violation, minor security event | Next business day |

### Evidence Preservation
- **Do NOT** power off systems (you'll lose volatile memory data).
- Capture memory dumps and disk images before remediation when possible.
- Document every action with timestamps: who did what, when, and why.
- Preserve logs (firewall, SIEM, endpoint, authentication) for the affected timeframe.
- Chain of custody if law enforcement may be involved.
