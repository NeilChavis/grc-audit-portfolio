# Project 1: Cloud File Sharing System
## Overview
TThis project is a simulation of a security assessment and for a Cloud File Sharing System (CFSS) that is used by Apex Consulting Group, a consulting firm that works with critical business data and only a small amount of personally identifiable information (PII). This work is not to design the system from scratch, but to look at its current security posture. The system is already in operation.

The NIST Risk Management Framework (RMF) is used to do the evaluation, and it shows how a GRC Analyst, ISSO, or IT Auditor would look at a real-world system. This means knowing how the system works in real life, figuring out where security controls work and where they don't, and writing down risks based on how the system really works and what it depends on. The idea is to go beyond just thinking about things and instead make structured, evidence-based outputs that help with a decision on whether or not to give someone permission.

## Project Scope
This assessment focuses on how Apex Consulting Group uses the Cloud File Sharing System (CFSS), with a focus on how the company controls access, data, and system settings in a SaaS setting.

### In Scope
- CFSS application as used by the organization
- User accounts, roles, and access permissions
- System configuration settings
- Data stored, processed, and shared within the system

### Out of Scope
- Underlying infrastructure managed by the SaaS provider
- Identity provider (Okta) used for authentication
- Microsoft 365 email system
- User endpoint devices

## Repository Structure
- 1-System-Overview
  - Provides background on the organization, system purpose, users, and data types.
- 2-Cloud-Responsibility
  - Defines the SaaS shared responsibility model between the provider and the organization.
- 3-FIPS-199-Categorization
  - Documents system impact levels based on confidentiality, integrity, and availability using FIPS 199 and NIST SP 800-60.
- 4-Control-Selection
  - Identifies applicable security controls using FIPS 200 and NIST SP 800-53B.
- 5-Control-Implementations
  - Explains how selected controls are implemented within the system environment using NIST SP 800-53 and NIST SP 800-53A.
- 6-Risk-Register
  - Captures identified risks through a qualitative risk assessment methodology consistent with NIST SP 800-30 and organizational risk factors from NIST SP 800-39.
- 7-POA&M
  - Outlines corrective actions and timelines to address identified control gaps.
- 8-Authorization-Summary
  - Provides a risk-based recommendation to support the system’s authorization decision using NIST SP 800-37

## Goal
The purpose of this project is to imitate a real-world security assessment of an information system that is being utilized and show how governance, risk, and compliance activities are employed in real life. This project is not only about documentation. It also looks at how a system works, how well its security controls work, and what dangers come from practical use and dependencies.

This project focuses on:
- Understanding how the system operates within its real-world environment
- Evaluating the effectiveness of security controls based on actual system behavior
- Identifying risks tied to access, data handling, and system dependencies
- Producing structured outputs that support risk-informed decision-making
