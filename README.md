# Okta-Entra-ID-Integration-Lab
# Okta to Microsoft Entra ID Federation Lab

## Overview

This project demonstrates the configuration and implementation of identity federation between Okta and Microsoft Entra ID (Azure AD) using SAML 2.0 authentication. The lab focuses on establishing trust relationships between an Identity Provider (IdP) and Service Provider (SP), enabling secure Single Sign-On (SSO) and centralized identity management.

## Objectives

* Configure identity federation between Okta and Microsoft Entra ID
* Implement SAML 2.0 authentication and Single Sign-On (SSO)
* Configure user and group assignments
* Validate identity provider and service provider trust relationships
* Troubleshoot authentication and federation issues
* Apply Identity & Access Management (IAM) and Zero Trust security principles

## Technologies Used

* Okta
* Microsoft Entra ID (Azure AD)
* SAML 2.0
* Single Sign-On (SSO)
* SCIM Provisioning
* Multi-Factor Authentication (MFA)
* Conditional Access
* Role-Based Access Control (RBAC)
* Identity Federation
* Identity & Access Management (IAM)

## Architecture

```text
User
  │
  ▼
Microsoft Entra ID (Identity Provider)
  │
  │ SAML Assertion
  ▼
Okta (Service Provider)
  │
  ▼
Authorized Application Access
```

## Implementation Steps

### 1. Configure Microsoft Entra ID

* Created Enterprise Application
* Configured SAML-based Single Sign-On
* Generated Federation Metadata
* Configured User and Group Assignments

### 2. Configure Okta

* Created SAML Application Integration
* Imported Entra ID Metadata
* Configured Assertion Consumer Service (ACS) URL
* Configured Audience URI and SAML Attributes

### 3. Establish Federation

* Exchanged metadata between Entra ID and Okta
* Configured trust relationship
* Validated SAML assertions and authentication flow

### 4. User Access Testing

* Tested authentication workflow
* Verified successful Single Sign-On experience
* Validated user provisioning and access permissions

## Security Controls Implemented

* Multi-Factor Authentication (MFA)
* Conditional Access Policies
* Role-Based Access Control (RBAC)
* Least Privilege Access
* Identity Federation
* Zero Trust Principles

## Troubleshooting Scenarios

During this lab, the following IAM troubleshooting scenarios were analyzed:

* Invalid SAML assertions
* Certificate trust issues
* User assignment errors
* Group mapping inconsistencies
* Federation metadata configuration issues
* Authentication and authorization failures

## Key Skills Demonstrated

* Identity Federation
* Microsoft Entra ID Administration
* Okta Administration
* Single Sign-On (SSO)
* SAML Configuration
* IAM Governance
* Conditional Access
* RBAC Implementation
* MFA Configuration
* Authentication Troubleshooting

## Video Walkthrough
[
](https://youtu.be/nhVZe9arLc0)

## Outcome

Successfully configured federation between Okta and Microsoft Entra ID, enabling centralized identity management and secure Single Sign-On authentication while applying enterprise IAM and Zero Trust security best practices.
