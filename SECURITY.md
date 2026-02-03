# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

## Reporting a Vulnerability

We take security seriously and appreciate your efforts to responsibly disclose your findings.

### How to Report

**Do NOT open a public issue** for security vulnerabilities. Instead, please report security issues through one of these
channels:

1. **GitHub Security Advisories** (Preferred): [Report via GitHub](https://github.com/LanikSJ/lsusb/security/advisories/new)
2. **Email**: Send details to [security@lanik.us](mailto:security@lanik.us)
3. **Security Discussions**: Open a discussion in our [GitHub Discussions](https://github.com/LanikSJ/lsusb/discussions/categories/security)
4. **Security Issues**: Create a [Security Advisory](https://github.com/LanikSJ/lsusb/security/advisories/new) on GitHub

### What to Include

When reporting a vulnerability, please include:

- **Description**: Clear explanation of the security issue
- **Steps to Reproduce**: Detailed steps to reproduce the vulnerability
- **Impact Assessment**: Potential impact and affected components
- **Proof of Concept**: If applicable, a minimal reproduction case
- **Suggested Fix**: If you have ideas for a fix (optional)

### Response Timeline

We are committed to responding to security reports in a timely manner:

- **Initial Response**: Within 48 hours of receiving the report
- **Status Update**: Within 5 business days with assessment
- **Resolution**: We will work diligently to fix critical vulnerabilities as quickly as possible

### Responsible Disclosure

We ask that you:

- Give us reasonable time to investigate and fix the issue before public disclosure
- Do not access, modify, or delete user data
- Do not perform attacks that could harm the availability of our services
- Do not publicly disclose the vulnerability until we have had a chance to address it

## Security Considerations

### Project-Specific Security

This project provides USB device listing functionality. Security considerations include:

- **System Access**: Limited to USB device enumeration
- **No Sensitive Data**: The project does not handle sensitive user data
- **Minimal Dependencies**: Uses minimal external dependencies to reduce attack surface

## Security Best Practices

### For Users

- **Keep Updated**: Always use the latest version of the tool
- **Verify Sources**: Only download from official sources
- **Report Suspicious Activity**: If you notice anything unusual, please report it

### For Developers

When contributing to the project:

- **Validate Inputs**: Always validate new inputs before submission
- **Follow Guidelines**: Adhere to the project's contribution guidelines
- **Security First**: Prioritize security when adding new features

## Security Resources

- [GitHub Security Documentation](https://docs.github.com/en/code-security/getting-started)

## Contact

For general security questions or concerns, you can:

- Open a discussion in our [GitHub Discussions](https://github.com/LanikSJ/lsusb/discussions)
- Contact the maintainers through the security email above for sensitive matters

Thank you for helping keep lsusb secure!
