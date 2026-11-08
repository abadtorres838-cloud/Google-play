## 2023-11-08 - [Repository Initialization]
**Vulnerability:** Missing security policy
**Learning:** Repositories without a clear security policy may have vulnerabilities reported publicly, which increases risk before patches are available. Additionally, using dummy email addresses like security@example.com in security policies can misdirect sensitive vulnerability reports to unauthorized domains.
**Prevention:** Always include a `SECURITY.md` file in new repositories that directs security researchers to use secure reporting channels (like GitHub Private Vulnerability Reporting) instead of public issues or dummy emails.
