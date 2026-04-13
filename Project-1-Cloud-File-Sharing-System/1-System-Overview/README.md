# System Overview

## System Name
Cloud File Sharing System (CFSS)
## System Description
The Cloud File Sharing System (CFSS) is a Software as a Service (SaaS) platform used by the organization to securely store, access, and share digital files and documents. The system serves as a centralized repository for business and client-related data, enabling collaboration among employees and project teams across all departments.
## System Purpose
The CFSS supports daily operations by allowing users to upload, retrieve, and share files internally and externally with clients through secure methods. The system is critical to business operations, as it replaces traditional file storage and email-based file sharing, and is relied upon for ongoing project work and document management.
## Users and Roles
### Employees (Standard Users):  
Regular users include consultants and general employees. They are who generate the majority of system activity. They use the system to upload, access, and share files required for daily operations with standard access permissions.
### Managers/Supervisors:  
This will include managers and project leads. These are users with elevated visibility over team-related content. They coordinate collaboration efforts, oversee shared resources, and may have broader access to departmental files based on their role.
### System Administrators (IT/Admin):  
Responsible for managing system configuration, user accounts, access permissions, and security settings. They ensure the system operates properly and that access is appropriately controlled.
### External Users:  
Non-organizational users granted limited access to specific files or folders for approved business purposes such as collaboration, document exchange, or communication.

## Data Types
### Internal Data:  
Includes internal business documents such as procedures, reports, and operational materials used across teams to support daily business functions.
### Business-Sensitive Data:  
Includes client and project-related information such as deliverables, contracts, and presentations, where unauthorized disclosure could impact business operations, client relationships, or organizational reputation.
### Confidential / Financial Data:  
Includes sensitive organizational information such as financial records, budgeting data, and restricted internal reports, where disclosure could result in financial loss or significant business impact.
### Personally Identifiable Information (PII):  
Includes data that can identify individuals, such as names, email addresses, and contact details, which requires protection due to privacy concerns and potential regulatory implications.

## Operating Environment
The Cloud File Sharing System (CFSS) is deployed fully as a Cloud-hosted Software as a Service (SaaS) platform. The third-party vendor is responsible for  managing  all of the underlying infrastructure including servers and databases. Apex does not hold any of its infrastructure on premise.
Apex Consulting Group is responsible for the system-level configurations such as assigning user roles, permissions, various settings, and integrations. The method assigned for accessing this system is over the internet via browser. Apex’s identity provider is integrated with the CFSS to authenticate users. It utilizes SSO and MFA for all users.

## System Interconnections
The Cloud File Sharing System (CFSS) works with a number of outside systems to make it work. Okta, the organization's identity provider, provides authentication services for the system. These include Single Sign-On (SSO) and Multi-Factor Authentication (MFA). This makes Okta a key part of the system that users need to access.
The CFSS also works with Microsoft 365, the organization's email system, to send notifications about file sharing, access requests, and system alerts. Users can get to the system through endpoint devices like laptops and mobile phones, but these endpoints are not part of the system boundary. 

## System Boundary
The system boundary for the Cloud File Sharing System (CFSS) includes all components and functions that are directly managed and controlled by Apex Consulting Group within the SaaS environment. This includes the use of the application for storing, processing, and sharing organizational and client data, as well as all user and configuration management activities.
### In-Scope Components
The following components are within the system boundary:
- CFSS application as utilized by the organization  
- System configuration settings and controls  
- User account management and access control  
- Roles, permissions, and privilege assignments  
- Data stored, processed, and shared within the system 
### External Dependencies (Out of Scope)
The following systems interact with CFSS but are not part of the system boundary:
- Okta (Identity Provider) used for authentication, Single Sign-On (SSO), and Multi-Factor Authentication (MFA)  
- Microsoft 365 (Email System) used for notifications and communication  
- User endpoint devices (e.g., laptops, mobile devices) used to access the system 
### Excluded Components
The following components are not within the system boundary and are managed by the third-party service provider:
- Underlying infrastructure, including servers, databases, and storage  
- Operating system and runtime environment  
- Network infrastructure and supporting platform services

