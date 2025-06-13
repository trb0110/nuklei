# Contributing to Nuklei

Thank you for your interest in contributing to Nuklei! We appreciate your time and effort in helping us build a comprehensive framework for nuclear energy projects.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
   - [Reporting Bugs](#reporting-bugs)
   - [Suggesting Enhancements](#suggesting-enhancements)
   - [Code Contributions](#code-contributions)
   - [Documentation](#documentation)
4. [Development Workflow](#development-workflow)
5. [Code Review Process](#code-review-process)
6. [Community](#community)
7. [License](#license)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [INSERT CONTACT EMAIL].

## Getting Started

### Prerequisites

- Git
- GitHub account
- Basic understanding of Markdown for documentation contributions
- (For code contributions) Familiarity with our tech stack


## How to Contribute

### Reporting Bugs

1. **Check for existing issues** to avoid duplicates
2. Create a new issue using the "Bug Report" template
3. Include as much detail as possible:
   - Clear description of the problem
   - Steps to reproduce
   - Expected vs. actual behavior
   - Screenshots or error messages if applicable
   - Environment details

### Suggesting Enhancements

1. Check existing issues and feature requests
2. Create a new issue using the "Feature Request" template
3. Include:
   - The problem you're trying to solve
   - Your proposed solution
   - Any alternative solutions considered
   - Additional context

### Code Contributions

1. Find an issue to work on or create a new one
2. Assign the issue to yourself
3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes
5. Write or update tests as needed
6. Ensure all tests pass
7. Commit your changes with a descriptive message:
   ```bash
   git commit -m "feat: add new feature"
   ```
8. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
9. Open a pull request against the main branch

### Documentation

We welcome contributions to improve our documentation. This includes:

- Fixing typos and grammatical errors
- Adding new sections or clarifying existing content
- Translating documentation to other languages
- Improving code examples

## Development Workflow

### Branch Naming Conventions

- `feature/`: New features or enhancements
- `bugfix/`: Bug fixes
- `docs/`: Documentation changes
- `test/`: Adding or updating tests
- `chore/`: Maintenance tasks

### Commit Message Format

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types**:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code changes that don't fix bugs or add features
- `perf`: Performance improvements
- `test`: Adding or modifying tests
- `chore`: Changes to the build process or auxiliary tools

**Example**:
```
feat(api): add user authentication endpoint

- Add POST /api/auth/login endpoint
- Implement JWT token generation
- Add input validation

Closes #123
```

## Code Review Process

1. A maintainer will review your PR as soon as possible
2. The reviewer may request changes
3. Once approved, a maintainer will merge your PR
4. Your changes will be included in the next release

### Review Guidelines

- Be respectful and constructive
- Focus on the code, not the person
- Explain your reasoning clearly
- Be open to discussion and feedback
- Keep PRs focused and manageable in size

## Community

### Getting Help

- Join our [Discord/Slack/Matrix] channel: [LINK]
- Check out our [FAQ](docs/FAQ.md)
- Browse [existing issues](https://github.com/nuklei-org/nuklei/issues)

### Events

- [Upcoming events]
- [Past events and recordings]

### Community Roles

- **Contributors**: Anyone who submits a PR that gets merged
- **Reviewers**: Experienced contributors who help review PRs
- **Maintainers**: Core team members with merge access

## License

By contributing to Nuklei, you agree that your contributions will be licensed under its [LICENSE](LICENSE) (CC BY-SA 4.0).

## Acknowledgments

- Thank you to all our contributors
- Special thanks to our sponsors and backers
- Inspired by the open source community

---

*This document was adapted from the [Contributor Covenant](https://www.contributor-covenant.org/) and other open source contribution guidelines.*
