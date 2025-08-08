# Contributing to Oneliner

Thank you for your interest in contributing to Oneliner! This document provides guidelines and information for contributors.

## 🎯 Ways to Contribute

### 🐛 Bug Reports
- Use GitHub Issues to report bugs
- Include clear steps to reproduce the issue
- Mention browser version and operating system
- Add screenshots if relevant

### 💡 Feature Requests
- Open an issue with the "enhancement" label
- Clearly describe the feature and its use case
- Discuss the implementation approach if you have ideas

### 🔧 Code Contributions
- Bug fixes
- New features
- Performance improvements
- UI/UX enhancements
- Documentation improvements

### 📚 Documentation
- README improvements
- Code comments
- Usage examples
- Tutorial content

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript
- Git for version control

### Development Setup
1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/yourusername/oneliner.git
   cd oneliner
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

4. **Start developing**
   ```bash
   # Simply open index.html in your browser
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux
   ```

## 🛠️ Development Guidelines

### Code Style
- Use consistent indentation (2 spaces)
- Follow existing naming conventions
- Write clear, descriptive variable names
- Add comments for complex logic

### CSS Guidelines
- Use CSS custom properties (variables) for consistency
- Follow the existing design system
- Maintain responsive design principles
- Test in multiple browsers

### JavaScript Guidelines
- Use modern ES6+ features
- Write pure functions when possible
- Handle errors gracefully
- Test edge cases

### HTML Guidelines
- Use semantic HTML elements
- Maintain accessibility standards
- Include proper ARIA labels
- Test with screen readers when possible

## 🔍 Testing

### Manual Testing Checklist
- [ ] Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices
- [ ] Test dark/light theme switching
- [ ] Test all conversion options
- [ ] Test keyboard shortcuts
- [ ] Test copy functionality
- [ ] Test with various input formats

### Test Cases to Consider
1. **Single Command Mode**
   - Empty input
   - Single line input
   - Multi-line SQL queries
   - Multi-line curl commands
   - Text with special characters

2. **Multiple Commands Mode**
   - Numbered commands
   - Commands separated by blank lines
   - Mixed command types
   - Very long command lists

3. **Edge Cases**
   - Very large inputs
   - Unicode characters
   - Commands with quotes
   - Malformed commands

## 📝 Commit Guidelines

### Commit Message Format
```
type(scope): description

Optional longer description

Closes #123
```

### Types
- `feat`: New features
- `fix`: Bug fixes
- `docs`: Documentation changes
- `style`: Code formatting, CSS changes
- `refactor`: Code refactoring
- `perf`: Performance improvements
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```bash
feat(ui): add command syntax highlighting
fix(parser): handle empty lines in multiple mode
docs(readme): add keyboard shortcuts section
style(css): improve dark mode contrast
```

## 🔄 Pull Request Process

1. **Before Submitting**
   - Test your changes thoroughly
   - Update documentation if needed
   - Add comments to complex code
   - Ensure your code follows the style guidelines

2. **Submit Pull Request**
   - Use a clear, descriptive title
   - Fill out the PR template completely
   - Link related issues
   - Add screenshots for UI changes

3. **After Submission**
   - Respond to feedback promptly
   - Make requested changes
   - Keep the PR up to date with main branch

## 🚨 Issue Triage

### Bug Report Template
```markdown
**Describe the bug**
A clear description of what the bug is.

**Steps to reproduce**
1. Go to '...'
2. Click on '...'
3. Enter '...'
4. See error

**Expected behavior**
What you expected to happen.

**Screenshots**
Add screenshots if applicable.

**Environment:**
- Browser: [e.g. Chrome 96]
- OS: [e.g. macOS 12]
- Device: [e.g. iPhone 13]
```

### Feature Request Template
```markdown
**Problem Statement**
What problem does this solve?

**Proposed Solution**
How would you like it to work?

**Alternatives Considered**
What alternatives have you considered?

**Additional Context**
Add any other context or screenshots.
```

## 🎨 Design Guidelines

### UI/UX Principles
- **Simplicity**: Keep the interface clean and uncluttered
- **Consistency**: Follow existing design patterns
- **Accessibility**: Ensure usability for all users
- **Performance**: Maintain fast loading and smooth interactions

### Color Scheme
- Use CSS custom properties for theming
- Maintain good contrast ratios
- Support both light and dark modes
- Test with colorblind users in mind

## 📋 Code Review Checklist

### For Reviewers
- [ ] Code follows project guidelines
- [ ] Changes are well tested
- [ ] Documentation is updated
- [ ] No breaking changes (or properly documented)
- [ ] Performance impact considered
- [ ] Accessibility maintained

### For Contributors
- [ ] Self-review completed
- [ ] Tests pass in multiple browsers
- [ ] Documentation updated
- [ ] Commit messages follow guidelines
- [ ] PR description is clear

## 🏷️ Release Process

1. **Version Numbering**
   - Follow semantic versioning (semver)
   - Major.Minor.Patch format
   - Document breaking changes

2. **Release Notes**
   - Highlight new features
   - List bug fixes
   - Mention breaking changes
   - Credit contributors

## 🤝 Community Guidelines

### Be Respectful
- Use inclusive language
- Be constructive in feedback
- Help newcomers get started
- Celebrate contributions

### Be Patient
- Reviews take time
- Complex features need discussion
- Not all ideas can be implemented
- Quality over speed

## 🆘 Getting Help

- **GitHub Issues**: For bugs and feature requests
- **GitHub Discussions**: For questions and ideas
- **Code Review**: Ask for feedback on your PRs

## 🙏 Recognition

Contributors will be:
- Listed in the README
- Mentioned in release notes
- Given credit for their contributions
- Invited to be maintainers for significant contributions

---

Thank you for contributing to Oneliner! Your efforts help make this tool better for developers worldwide. 🚀