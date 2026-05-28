# Contributing to Ummah Beacon

Thank you for your interest in contributing to Ummah Beacon! We welcome contributions that help us serve the Muslim Ummah better.

## Code of Conduct

All contributors must follow our Islamic ethical principles:

- **Niyyah (Intention)**: Contribute with pure intention to serve
- **Amanah (Trust)**: Respect the trust placed in you
- **Sidq (Truthfulness)**: Be honest in all communications
- **Ihsan (Excellence)**: Pursue excellence in your contributions
- **Mas'uliyyah (Accountability)**: Take responsibility for your work

## How to Contribute

### Reporting Issues

1. Check if the issue already exists
2. Provide a clear title and description
3. Include steps to reproduce bugs
4. Attach screenshots or error logs if relevant
5. Respect privacy—never share personal or payment information

### Submitting Changes

1. **Fork the Repository**
   ```bash
   git clone https://github.com/YahyaAliyi/ummahbeacon.git
   cd ummahbeacon
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Keep commits atomic and well-documented
   - Follow existing code style
   - Test changes locally before submitting

4. **Security Checklist**
   - [ ] No hardcoded secrets or credentials
   - [ ] No sensitive data in comments
   - [ ] All inputs properly validated
   - [ ] No XSS vulnerabilities
   - [ ] No SQL/LDAP injection risks
   - [ ] External links are secure (HTTPS)

5. **Commit Your Changes**
   ```bash
   git commit -m "Add/Fix: Brief description of changes"
   ```

6. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Open a Pull Request**
   - Reference related issues
   - Describe changes clearly
   - Include testing notes
   - List any security considerations

## Pull Request Review Process

All PRs require:

- ✅ At least one reviewer approval
- ✅ All status checks passing
- ✅ No merge conflicts
- ✅ Security review (for sensitive changes)
- ✅ Documentation updates (if applicable)

## Development Guidelines

### Code Style

- **HTML**: Use semantic HTML5
- **CSS**: Follow BEM naming conventions
- **JavaScript**: Use ES6+ where supported
- **Comments**: Explain the "why", not just the "what"

### Testing

Before submitting:

1. Test across browsers (Chrome, Firefox, Safari, Edge)
2. Test on mobile devices
3. Validate HTML/CSS
4. Check accessibility (WCAG 2.1)
5. Verify all links work

### Documentation

- Update README.md for major changes
- Add comments for complex logic
- Document any new features
- Keep CNAME file unchanged

## Security Guidelines

**NEVER**:
- Commit API keys or passwords
- Include payment processor details
- Store personal user data
- Use `eval()` or dynamic code execution
- Rely solely on client-side validation

## Questions?

For questions about contributing:
- Email: yahya@ummahbeacon.com
- Open a discussion in the repository
- Check existing documentation

## Recognition

We recognize and appreciate all contributors. Significant contributions may be:
- Listed in README.md
- Credited in release notes
- Featured in our community newsletter

---

**Barakallahu feek for your contribution!** 🤲
