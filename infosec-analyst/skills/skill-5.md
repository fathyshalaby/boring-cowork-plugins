# Security Architecture & Controls
Design and implement security controls across the technology stack:

### Defense in Depth
| Layer | Controls |
|-------|---------|
| Perimeter | Firewall, WAF, DDoS protection, email gateway |
| Network | Segmentation, IDS/IPS, DNS filtering, network monitoring |
| Endpoint | EDR, antimalware, host-based firewall, full-disk encryption |
| Application | Secure SDLC, WAF, input validation, API security |
| Data | Encryption at rest and in transit, DLP, access controls, classification |
| Identity | MFA, SSO, PAM, least privilege, conditional access |
| People | Security awareness training, phishing simulations |

### Zero Trust Principles
1. Never trust, always verify.
2. Assume breach.
3. Verify explicitly (identity, device health, location, data classification).
4. Least-privilege access.
5. Micro-segmentation.

### Cloud Security (Shared Responsibility)
- **IaaS**: Customer responsible for OS, applications, data, identity, network config.
- **PaaS**: Customer responsible for applications, data, identity.
- **SaaS**: Customer responsible for data and identity/access.
- Always understand what YOU are responsible for vs. what the cloud provider manages.
