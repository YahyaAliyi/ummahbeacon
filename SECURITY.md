# Security Policy for Ummah Beacon

## Reporting a Vulnerability

If you discover a security vulnerability in the Ummah Beacon website, please report it responsibly to **yahya@ummahbeacon.com** instead of using the public issue tracker.

### Guidelines for Reporting:

1. **Email Details**: Include a detailed description of the vulnerability
2. **Steps to Reproduce**: Provide clear steps to reproduce the issue
3. **Impact Assessment**: Explain the potential impact on users and data
4. **Suggested Fix** (optional): If you have a solution, we'd appreciate it
5. **Responsible Disclosure**: Please give us 90 days to fix before public disclosure

### What to Expect:

- **Acknowledgment**: We'll acknowledge receipt within 48 hours
- **Assessment**: Security team will evaluate the vulnerability
- **Timeline**: We aim to patch critical vulnerabilities within 7 days
- **Communication**: Regular updates on remediation progress
- **Credit**: We're happy to credit researchers who report responsibly

## Security Measures

Our website implements:

### Content Security
- ✅ **Content Security Policy (CSP)** - Prevents XSS and injection attacks
- ✅ **X-Frame-Options** - Prevents clickjacking
- ✅ **X-Content-Type-Options** - Prevents MIME type sniffing
- ✅ **HTTPS/TLS** - All traffic encrypted
- ✅ **HSTS** - Forces HTTPS connections
- ✅ **Referrer Policy** - Controls referrer information
- ✅ **Permissions Policy** - Restricts browser APIs

### Code Security
- ✅ **Input Validation** - Email validation on forms
- ✅ **Output Encoding** - Prevents injection attacks
- ✅ **No Sensitive Data in Client Code** - Payment processing via external APIs
- ✅ **Git Security** - Regular audits of repository access

### Operational Security
- ✅ **Branch Protection** - Code review required before merge
- ✅ **Dependabot Enabled** - Automatic dependency updates
- ✅ **GitHub Security Alerts** - Monitors for known vulnerabilities

## Data Protection

The Ummah Beacon website:

- **Does NOT** store sensitive payment data
- **Does NOT** retain personal information beyond sessions
- **Uses** Google Drive for secure document hosting
- **Uses** WhatsApp and Wise for payment processing

## Security Best Practices for Users

We recommend:

1. Always access the site via **https://www.ummahbeacon.com**
2. Never share payment screenshots in public channels
3. Verify sender before clicking links from our organization
4. Report suspicious activity to yahya@ummahbeacon.com
5. Keep your browser and antivirus software updated

## Compliance

We comply with:
- GDPR (for EU users)
- CCPA (for California users)
- Web Content Accessibility Guidelines (WCAG 2.1)
- GitHub's Community Guidelines
- Islamic ethical principles in data handling

## Security Updates

We regularly audit and update security measures. Subscribe to our newsletter for critical security announcements.

---

**Last Updated**: May 2026
**Next Review**: November 2026
