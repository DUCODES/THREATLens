
## Contributing to THREATLens

Thank you for your interest in contributing to THREATLens.

THREATLens is a cybersecurity platform designed to help organizations manage cyber threats, third-party risks, security assessments, and compliance workflows.

We welcome contributions from developers, cybersecurity professionals, researchers, designers, and documentation contributors who share our goal of improving cybersecurity capabilities.

### Code of Conduct

All contributors are expected to maintain professional and respectful behavior.

Contributors must:

- Communicate respectfully.
- Provide constructive feedback.
- Avoid harmful or malicious contributions.
- Respect intellectual property.
- Follow responsible security practices.

### Ways to Contribute

There are several ways to contribute:

### Software Development
Examples:

- Backend development.
- Frontend improvements.
- API development.
- Database optimization.
- Security improvements.
- Performance enhancements.

### Cybersecurity Contributions
Examples:

- Threat intelligence improvements.
- MITRE ATT&CK mappings.
- Detection rules.
- Security framework mappings.
- Risk assessment improvements.
- Vendor questionnaire enhancements.

### Documentation
Examples:

- Improving technical documentation.
- Writing tutorials.
- Creating examples.
- Improving user guides.

### Testing
Examples:

- Identifying bugs.
- Testing new features.
- Improving usability.
- Reporting security concerns.

### Development Workflow

The recommended contribution workflow:
Fork Repository
       ↓
Create Feature Branch
       ↓
Implement Changes
       ↓
Run Tests
       ↓
Submit Pull Request
       ↓
Code Review
       ↓
Merge

### Creating a Branch
Create a descriptive branch name:

Examples:


feature/vendor-risk-dashboard

feature/mitre-attack-mapping

bugfix/authentication-error

security/api-validation-fix

Avoid generic names:

test
update
changes
fix

### Commit Guidelines
Use clear commit messages.

Recommended format:
type: description
Examples:

feat: add vendor questionnaire scoring engine
fix: resolve API authorization issue
docs: update threat intelligence documentation
security: improve authentication validation

### Pull Request Requirements
Before submitting a pull request:

Ensure:

- Code follows project standards.
- Tests pass successfully.
- Documentation is updated.
- No sensitive information is included.
- No secrets or credentials are committed.
- Changes are clearly explained.

### Pull Request Template
Every pull request should include:

## Description
Explain:

- What was changed.
- Why the change was required.
- How it improves THREATLens.

## Testing
Describe:

- Tests performed.
- Expected results.

## Security Considerations
Explain:

- Any security impact.
- Data handling considerations.
- Required security review.

Example:
This change improves vendor assessment scoring by adding
weighted control evaluation.

Security Impact:
No additional permissions introduced.

Testing:
Completed unit tests and API validation tests.

# Coding Standards

## General Principles
Contributors should prioritize:

- Secure coding.
- Maintainability.
- Simplicity.
- Performance.
- Documentation.

# Security Requirements
All contributions must consider:

 ## Authentication
- Proper identity validation.
- Secure session handling.
- MFA compatibility.

 ## Authorization
- Least privilege access.
- Proper role validation.
- Tenant isolation.

 ## Data Protection
- Encryption where required.
- Secure storage.
- Avoid unnecessary data exposure.

 ## Input Validation
Prevent:

- SQL injection.
- Command injection.
- Cross-site scripting.
- Malicious file uploads.

# Cybersecurity Data Contributions
Threat intelligence contributions must include:

- Source reliability.
- Confidence rating.
- Timestamp.
- References.
- Context.
Example:
Threat:
Ransomware Campaign

Actor:
Example Group

Confidence:
High

Source:
Public threat intelligence report

MITRE Techniques:
T1566, T1059

Date:
2026-01-01

# Adding New Security Controls

New security controls should include:

- Control objective.
- Security framework mapping.
- Implementation guidance.
- Testing approach.

Supported mappings may include:

- NIST CSF.
- ISO 27001.
- CIS Controls.
- SOC 2.
- MITRE ATT&CK.

# Reporting Bugs

Non-security bugs should be submitted through GitHub Issues.
Include:

- Description.
- Steps to reproduce.
- Expected behavior.
- Actual behavior.
- Screenshots/logs where applicable.

# Security Vulnerabilities

Do not submit security vulnerabilities through public GitHub issues.
Follow the process described in:
SECURITY.md

# Review Process
Pull requests may be reviewed for:

- Code quality.
- Security impact.
- Architecture consistency.
- Performance.
- Documentation quality.
Security-sensitive changes may require additional review.

# License Agreement
By contributing to THREATLens, contributors agree that their contributions may be used according to the project's licensing terms.
See:

LICENSE
for applicable licensing information.

# Thank You

Every contribution helps improve cybersecurity capabilities and enables organizations to better understand and manage cyber risk.
Thank you for helping build THREATLens.
