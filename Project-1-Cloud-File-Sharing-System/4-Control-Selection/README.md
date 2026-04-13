# Control Selection
The security controls for the Cloud File Sharing System (CFSS) were chosen based on the control baselines set by NIST SP 800-53B and FIPS 200. The system's Moderate impact level was used to find the security procedures that were relevant to the control families. These were then compared to the Moderate baseline.

We looked at artifacts such as the SaaS architecture and the shared responsibility model to make sure that the controls we chose would work in the CFSS operating environment. The organization was responsible for reviewing controls related to user access, data handling, system configuration, and monitoring. However, controls related to the infrastructure level that are maintained by the service provider were not considered to be within the scope of direct implementation.

## Control Selection Approach
Selection and scalability of controls were based on their potential impact on system functionality and risk profile; as a result, not all controls were applied uniformly. The emphasis in a SaaS environment was on control families that help with data security, system monitoring, risk management, and authenticated access.

Key control families considered in this assessment include:
- Access Control (AC) – User access, permissions, and role-based controls
- Identification and Authentication (IA) – Authentication mechanisms, including SSO and MFA
- Audit and Accountability (AU) – Logging, monitoring, and audit review
- System and Communications Protection (SC) – Data protection and secure transmission
- System and Information Integrity (SI) – Monitoring and detection of system anomalies
- Configuration Management (CM) – System configuration and change control
- Contingency Planning (CP) – System availability and recovery considerations

## Control Selection Table
The following table summarizes selected controls and their relevance to the CFSS environment.

![Control Selection Table](control_selection.pdf)
