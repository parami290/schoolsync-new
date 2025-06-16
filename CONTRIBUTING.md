# Contributing to SchoolSync

Thank you for your interest in contributing to SchoolSync! We welcome contributions from the community and are pleased to have you join us.

## 🤝 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## 🚀 How to Contribute

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed and what behavior you expected**
- **Include screenshots if applicable**
- **Include your environment details** (OS, browser, Node.js version)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and explain the behavior you expected**
- **Explain why this enhancement would be useful**

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Install dependencies**: `npm install`
3. **Make your changes** following our coding standards
4. **Test your changes**: `npm run test`
5. **Lint your code**: `npm run lint`
6. **Commit your changes** with a clear commit message
7. **Push to your fork** and submit a pull request

#### Pull Request Guidelines

- **Fill in the required template**
- **Do not include issue numbers in the PR title**
- **Include screenshots and animated GIFs** when applicable
- **Follow the TypeScript and React coding standards**
- **Include thoughtfully-worded, well-structured tests**
- **Document new code** based on the Documentation Styleguide
- **End all files with a newline**

## 🏗️ Development Setup

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Git

### Setup Steps

1. **Clone your fork**
   ```bash
   git clone https://github.com/yourusername/schoolsync.git
   cd schoolsync
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Run tests**
   ```bash
   npm run test
   ```

## 📝 Coding Standards

### TypeScript

- Use TypeScript for all new code
- Define proper interfaces and types
- Avoid `any` type unless absolutely necessary
- Use meaningful variable and function names

### React

- Use functional components with hooks
- Follow React best practices
- Use proper prop types
- Implement proper error boundaries

### Styling

- Use Tailwind CSS classes
- Follow mobile-first responsive design
- Maintain consistent spacing and colors
- Use semantic HTML elements

### File Organization

- Keep components small and focused
- Use proper file naming conventions
- Organize files by feature/domain
- Export components properly

## 🧪 Testing

- Write tests for new features
- Maintain existing test coverage
- Use descriptive test names
- Test both happy path and edge cases

## 📚 Documentation

- Update README.md for significant changes
- Document new features and APIs
- Include code examples where helpful
- Keep documentation up to date

## 🎯 Project Structure

```
src/
├── components/          # Reusable UI components
├── context/            # React context providers
├── pages/              # Page components
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── types/              # TypeScript type definitions
└── constants/          # Application constants
```

## 🏷️ Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, etc.)
- `refactor:` Code refactoring
- `test:` Adding or updating tests
- `chore:` Maintenance tasks

Example:
```
feat: add dark mode toggle to header
fix: resolve login form validation issue
docs: update installation instructions
```

## 🔄 Release Process

1. Version bumping follows [Semantic Versioning](https://semver.org/)
2. Releases are created from the `main` branch
3. Release notes are automatically generated
4. All releases are tagged and published

## ❓ Questions?

Don't hesitate to ask questions! You can:

- Open an issue with the `question` label
- Join our Discord community
- Email us at dev@schoolsync.com

## 🙏 Recognition

Contributors will be recognized in:

- README.md contributors section
- Release notes
- Project documentation
- Annual contributor highlights

Thank you for contributing to SchoolSync! 🎓