# Contributing to lsusb

First off, thank you for considering contributing to lsusb! It's people like you that make this project better.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Guidelines](#coding-guidelines)
- [Testing](#testing)
- [Documentation](#documentation)

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

### Our Pledge

We are dedicated to providing a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

**Positive behaviors that contribute to a welcoming environment:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

**Unacceptable behaviors include:**
- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

### Enforcement

Instances of unacceptable behavior may be reported by contacting the project team at [forums.lanik.us](https://forums.lanik.us). All complaints will be reviewed and investigated promptly and fairly.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed and what behavior you expected**
- **Include screenshots and animated GIFs if possible**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and explain the behavior you expected**
- **Explain why this enhancement would be useful**

## Development Setup

### Prerequisites

- Ensure you have the necessary development tools installed
- Clone the repository: `git clone https://github.com/LanikSJ/lsusb.git`
- Install dependencies as specified in the project documentation

### Getting Started

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Run tests to ensure everything works
5. Commit your changes: `git commit -m 'Add some amazing feature'`
6. Push to the branch: `git push origin feature/amazing-feature`
7. Open a Pull Request

## Pull Request Process

1. **Pre-submission Checklist:**
   - [ ] Remove any install or build dependencies before the end of the layer when doing a build
   - [ ] Update documentation with details of changes to the interface
   - [ ] Increase version numbers appropriately
   - [ ] Ensure your code follows the project's coding guidelines
   - [ ] Add or update tests as necessary
   - [ ] Ensure all tests pass
   - [ ] Update the README.md with details of changes

2. **Version Management:**
   - Follow [Semantic Versioning](http://semver.org/)
   - Update version numbers in example files and documentation

3. **Review Requirements:**
   - You may merge the Pull Request once you have approval from at least two maintainers
   - If you don't have merge permissions, request the second reviewer to merge it for you
   - Ensure CI/CD checks pass before requesting review

4. **Post-Merge:**
   - Delete your feature branch
   - Update relevant documentation

## Coding Guidelines

### General Principles

- Write clean, readable, and maintainable code
- Follow existing code style and conventions
- Add comments for complex logic
- Keep functions focused and single-responsibility

### Commit Messages

Use clear and descriptive commit messages:

```
type(scope): brief description

Longer explanation if needed

Fixes #issue-number
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

### Code Style

- Follow the existing code style in the project
- Use meaningful variable and function names
- Keep lines reasonably sized (max 120 characters)
- Use consistent indentation

## Testing

### Running Tests

- Ensure all existing tests pass before submitting
- Add tests for new features and bug fixes
- Run the test suite with: `make test` or the appropriate command

### Test Coverage

- Aim for comprehensive test coverage
- Include both positive and negative test cases
- Test edge cases and error conditions

## Documentation

### What to Document

- New features and functionality
- Changes to existing APIs
- Configuration options
- Installation and setup instructions

### Documentation Standards

- Use clear, concise language
- Include code examples where appropriate
- Keep documentation up-to-date with code changes
- Use proper Markdown formatting

## Additional Resources

- [Project README](../README.md)
- [Project Wiki](https://github.com/LanikSJ/lsusb/wiki)
- [Issue Tracker](https://github.com/LanikSJ/lsusb/issues)

## Questions?

If you have questions about contributing, please:

1. Check the existing documentation and issues
2. Start a discussion in the issue tracker
3. Contact the maintainers at [forums.lanik.us](https://forums.lanik.us)

---

**Thank you for contributing to lsusb!** 🎉
