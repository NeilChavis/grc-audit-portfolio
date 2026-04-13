# Control Implementation
The chosen security controls were tested in the CFSS environment. The service provider and Apex Consulting Group work together to put controls in place under the SaaS model. The shared ownership of infrastructure, user administration, and system configuration makes it clear what each party's responsibility is.

## Implementation Statements
### AC-2 – Account Management
Apex connects Okta and the Cloud File Sharing System (CFSS) to add, change, and remove user accounts. According to the principle of least privilege, users are only given access to what they need to do their job. Management has to give the go-ahead for account creation, and when an employee leaves the company or changes roles, their account is disabled or deleted. Access reviews are done from time to time to make sure that active accounts are still allowed.
AC-6 – Least Privilege
Apex enforces least privilege by only giving users the access they need to do their jobs. CFSS has role-based access controls set up, and permissions are checked on a regular basis to make sure that no one has too much access. Only authorized people can have administrative privileges, and elevated access is only given when it is needed and approved.
AC-7 – Unsuccessful Logon Attempts
To keep accounts secure, CFSS uses Okta to manage logins. Apex sets the specific rules like how many failed attempts are allowed and how long a lockout lasts. This partnership protects against brute-force attacks while ensuring Apex maintains full control over its security policies.
IA-2 – Identification and Authentication (Organizational Users)
Okta is the front door to CFSS, and it gives every user SSO and MFA. Apex keeps track of our identities and makes sure our security standards are met. MFA is enforced to strengthen access security and reduce the risk of unauthorized access.
IA-5 – Authenticator Management
Okta manages user authenticators, including passwords and multi-factor authentication methods. Apex enforces password complexity, rotation  policies, and MFA usage through configuration settings within Okta. Users are required to maintain secure authentication credentials in accordance with organizational policy.
AU-2 – Event Logging
CFSS maintains a clear digital record of all activity, including logins and how files are accessed or shared. Apex determines exactly which events need to be tracked to ensure we’re meeting our security and monitoring standards. This oversight keeps everyone accountable and makes it much easier to spot and investigate any suspicious behavior.
AU-6 – Audit Record Review, Analysis, and Reporting
Apex is in charge of looking over the audit logs that CFSS generates. Logs are reviewed to see if there are any strange user actions, attempts to get into the system without permission, or other issues. Findings are written down and, if necessary, are escalated to the appropriate personnel to help with incident response and compliance work.
AU-12 – Audit Record Generation
The CFSS vendor automatically generates audit logs for system activity. Apex configures logging settings to make sure the right events are being captured and periodically checks that the logs are detailed enough to support monitoring and compliance needs.
SC-8 – Transmission Confidentiality and Integrity
All data traveling to and from CFSS is protected by secure, vendor-managed encryption. This keeps our information from being intercepted or altered. Apex oversees this by ensuring all user access happens over these verified, secure connections.
CM-2 – Baseline Configuration
The vendor is responsible for ensuring that the core system configuration is up to date, which includes the platform's default settings and setup. Apex takes care of application-level settings like user roles, permissions, and access settings. This shared approach keeps the system safe while still meeting the needs of the business.
SI-4 – System Monitoring
The vendor provides built-in logging and monitoring features for the system. Apex uses these logs to keep track of what the system is doing and adds any alerts that are important to its own monitoring. This helps find behavior that seems off and helps people respond quickly to possible problems.
CP-2 – Contingency Plan
The vendor supports system availability through backups, redundancy, and failover capabilities. Apex develops its own internal procedures to handle disruptions, including how teams will continue operations and communicate if the system becomes unavailable.
