# Identity & Access Management
Implement robust identity and access management:

### IAM Fundamentals
- **Authentication**: Proving identity (password, MFA, biometrics, certificates).
- **Authorization**: Determining permissions (RBAC, ABAC, least privilege).
- **Accounting**: Logging and auditing access activity.

### MFA Implementation
- **Require MFA for**: All remote access (VPN, cloud apps), privileged accounts, email, and any internet-facing application.
- **MFA methods** (strongest to weakest): Hardware security key (FIDO2) > Authenticator app (TOTP) > Push notification > SMS OTP.
- **SMS should be avoided** for high-security accounts — vulnerable to SIM swapping.

### Privileged Access Management (PAM)
- Separate privileged accounts from daily-use accounts.
- Just-in-time (JIT) access: Grant admin rights only when needed, for a limited time.
- Session recording for privileged sessions.
- Rotate privileged credentials automatically.
- Monitor for anomalous privileged activity.

### Access Reviews
- Quarterly access reviews for critical systems.
- Semi-annual for all other systems.
- Review scope: Are users active? Is access still appropriate? Are privileged accounts justified?
- Document reviewer, date, and decisions (retain, modify, revoke).
