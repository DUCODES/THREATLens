
# Security Policy

## Overview

THREATLens takes the security of its platform, users, contributors, and customers seriously.

As a cybersecurity risk management platform handling threat intelligence, security assessments, vendor risk information, and potentially sensitive organizational data, security is a fundamental part of our development process.

We appreciate the efforts of security researchers, developers, and the wider cybersecurity community in helping us identify and resolve vulnerabilities responsibly.


### Supported Versions
Security updates are provided for actively maintained versions of THREATLens.

Users are encouraged to always upgrade to the latest stable release to receive security improvements and vulnerability fixes.

### Reporting a Security Vulnerability
If you discover a potential security vulnerability in THREATLens, please report it responsibly.

Do not publicly disclose the vulnerability before we have investigated and addressed the issue.

### Preferred Reporting Method
Send vulnerability reports to:

### What to Include in Your Report
A useful vulnerability report should include:

- A clear description of the vulnerability.
- Affected component or feature.
- Steps required to reprComponent:
Vendor Risk Assessment Module

Issue:
Broken access control allowing unauthorized vendor report access.

Impact:
Users with limited permissions may view restricted assessment data.

Steps:

    Login as a standard user.

    Navigate to vendor assessment URL.

    Modify vendor ID parameter.

    Access another organization's assessment.


# Responsible Disclosure Guidelines

Security researchers are expected to:

- Avoid accessing data beyond what is necessary to demonstrate the vulnerability.
- Avoid modifying or deleting user data.
- Avoid disrupting production services.
- Avoid social engineering attacks.
- Avoid denial-of-service testing.
- Maintain confidentiality until remediation is complete.

THREATLens commits to:

- Acknowledge reports within a reasonable timeframe.
- Investigate reported issues.
- Provide updates during remediation.
- Credit researchers who responsibly disclose vulnerabilities.

# Scope of Security Testing

Security testing may include:

## Included

- Authentication vulnerabilities.
- Authorization issues.
- Data exposure.
- Injection vulnerabilities.
- Cryptographic weaknesses.
- API security issues.
- Access control flaws.
- Business logic vulnerabilities.

## Excluded

The following activities are not permitted:

- Social engineering against THREATLens employees.
- Physical security testing.
- Spam attacks.
- Denial-of-service attacks.
- Automated scanning that impacts service availability.
- Testing against third-party systems.

# Security Development Practices
THREATLens follows security-focused development practices including:

- Secure software development lifecycle (SSDLC).
- Code review requirements.
- Dependency vulnerability scanning.
- Secret detection.
- Security testing.
- Access control reviews.
- Audit logging.
- Secure configuration management.

# Data Protection Principles
THREATLens prioritizes:

- Confidentiality of customer information.
- Integrity of security assessments.
- Availability of platform services.
- Least privilege access.
- Secure handling of threat intelligence data.

# Security Updates
Security fixes may be released through:

- Regular software releases.
- Emergency security patches.
- Dependency updates.
- Configuration changes.

Users should monitor official THREATLens communication channels for important security announcements.

# Acknowledgements

We appreciate security researchers and contributors who help improve THREATLens security.

Responsible disclosure helps create a safer cybersecurity ecosystem.oduce the issue.
- Proof-of-concept (if available).
- Potential impact.
- Suggested remediation (if known).
- Your contact information for follow-up.

Example:
Component:
Vendor Risk Assessment Module

Issue:
Broken access control allowing unauthorized vendor report access.

Impact:
Users with limited permissions may view restricted assessment data.

Steps:

Login as a standard user.
Navigate to vendor assessment URL.
Modify vendor ID parameter.
Access another organization's assessment.


### Responsible Disclosure Guidelines
Security researchers are expected to:

- Avoid accessing data beyond what is necessary to demonstrate the vulnerability.
- Avoid modifying or deleting user data.
- Avoid disrupting production services.
- Avoid social engineering attacks.
- Avoid denial-of-service testing.
- Maintain confidentiality until remediation is complete.

THREATLens commits to:

- Acknowledge reports within a reasonable timeframe.
- Investigate reported issues.
- Provide updates during remediation.
- Credit researchers who responsibly disclose vulnerabilities.

### Scope of Security Testing
Security testing may include:

- Authentication vulnerabilities.
- Authorization issues.
- Data exposure.
- Injection vulnerabilities.
- Cryptographic weaknesses.
- API security issues.
- Access control flaws.
- Business logic vulnerabilities.

  ## Excluded
The following activities are not permitted:

- Social engineering against THREATLens employees.
- Physical security testing.
- Spam attacks.
- Denial-of-service attacks.
- Automated scanning that impacts service availability.
- Testing against third-party systems.

### Security Development Practices
THREATLens follows security-focused development practices including:

- Secure software development lifecycle (SSDLC).
- Code review requirements.
- Dependency vulnerability scanning.
- Secret detection.
- Security testing.
- Access control reviews.
- Audit logging.
- Secure configuration management.

### Data Protection PrinciplesTHREATLens prioritizes:

- Confidentiality of customer information.
- Integrity of security assessments.
- Availability of platform services.
- Least privilege access.
- Secure handling of threat intelligence data.

# Security Updates
Security fixes may be released through:

- Regular software releases.
- Emergency security patches.
- Dependency updates.
- Configuration changes.
Users should monitor official THREATLens communication channels for important security announcements.

# Acknowledgements

We appreciate security researchers and contributors who help improve THREATLens security.

Responsible disclosure helps create a safer cybersecurity ecosystem.
