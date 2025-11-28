# Contributing to Craftivo Portfolio Template

First off, thank you for considering contributing to this project! 🎉 

It's people like you that make open source such a great place to learn, inspire, and create. Any contributions you make will benefit everybody else and are greatly appreciated.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How Can I Contribute?](#how-can-i-contribute)
- [Style Guidelines](#style-guidelines)
- [Commit Messages](#commit-messages)
- [Pull Request Process](#pull-request-process)
- [Development Setup](#development-setup)

## Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct:

- **Be Respectful**: Treat everyone with respect. No harassment, discrimination, or offensive behavior.
- **Be Collaborative**: Work together constructively. Give and accept feedback gracefully.
- **Be Inclusive**: Welcome newcomers and help them feel included.
- **Be Patient**: Remember that everyone was a beginner once.

## Getting Started

### Prerequisites

Before you begin, ensure you have:
- A GitHub account
- Git installed on your local machine
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Fork and Clone

1. Fork the repository by clicking the "Fork" button on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Merlin-Class-Collaboration-Project.git
   cd Merlin-Class-Collaboration-Project
   ```
3. Add the original repository as upstream:
   ```bash
   git remote add upstream https://github.com/lewiii254/Merlin-Class-Collaboration-Project.git
   ```

## How Can I Contribute?

### 🐛 Reporting Bugs

Found a bug? Here's how to report it:

1. **Check existing issues** - Make sure the bug hasn't already been reported
2. **Create a new issue** using the bug report template
3. **Include details**:
   - Steps to reproduce the bug
   - Expected behavior vs. actual behavior
   - Screenshots if applicable
   - Browser and OS information

### ✨ Suggesting Features

Have an idea for a new feature?

1. **Check existing issues** - Someone might have suggested it already
2. **Create a new issue** describing your feature idea
3. **Explain the use case** - Why would this feature be helpful?
4. **Be specific** - The more detail, the better

### 📝 Improving Documentation

Documentation improvements are always welcome:
- Fix typos or unclear explanations
- Add examples or tutorials
- Translate documentation
- Update outdated information

### 💻 Code Contributions

Ready to contribute code? Here's what we're looking for:

#### Good First Issues
- Fix broken links
- Improve accessibility (ARIA labels, alt text)
- Add missing meta tags
- Fix CSS bugs
- Improve responsive design

#### Feature Ideas
- Dark mode toggle
- Language selector/i18n support
- Additional animations
- New sections or components
- Performance optimizations
- Browser compatibility fixes

## Style Guidelines

### HTML
- Use semantic HTML5 elements
- Include proper accessibility attributes
- Maintain consistent indentation (2 spaces)
- Add descriptive comments for complex sections

```html
<!-- Good Example -->
<section id="about" class="about section" aria-label="About Me">
  <div class="container">
    <h2>About Me</h2>
    <!-- Content here -->
  </div>
</section>
```

### CSS
- Follow existing naming conventions
- Use CSS custom properties for colors and common values
- Keep specificity low when possible
- Mobile-first approach for responsive styles

```css
/* Good Example */
.section-title {
  font-size: var(--font-size-lg);
  color: var(--color-primary);
  margin-bottom: 1.5rem;
}

@media (min-width: 768px) {
  .section-title {
    font-size: var(--font-size-xl);
  }
}
```

### JavaScript
- Use ES6+ syntax
- Add comments for complex logic
- Avoid global variables
- Keep functions small and focused

```javascript
// Good Example
function toggleDarkMode() {
  const body = document.body;
  body.classList.toggle('dark-mode');
  
  // Save preference to localStorage
  const isDarkMode = body.classList.contains('dark-mode');
  localStorage.setItem('darkMode', isDarkMode);
}
```

## Commit Messages

Write clear, meaningful commit messages:

### Format
```
<type>: <subject>

<body (optional)>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `perf`: Performance improvements
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```
feat: Add dark mode toggle button

fix: Correct navigation dropdown alignment on mobile

docs: Update README with installation instructions

style: Format CSS with consistent indentation
```

## Pull Request Process

### Before Submitting

1. **Update your fork**:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** and test thoroughly

4. **Commit your changes** following our commit message guidelines

### Submitting Your PR

1. Push your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

2. Go to GitHub and create a Pull Request

3. Fill out the PR template:
   - Describe your changes
   - Link related issues
   - Include screenshots for UI changes
   - List any breaking changes

### After Submitting

- Respond to review feedback promptly
- Make requested changes in new commits
- Once approved, your PR will be merged!

## Development Setup

### Local Development

1. **Open with Live Server** (VS Code):
   - Install the "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

2. **Using Python**:
   ```bash
   python -m http.server 8000
   # Open http://localhost:8000
   ```

3. **Using Node.js**:
   ```bash
   npx http-server
   # Open http://localhost:8080
   ```

### Testing Checklist

Before submitting a PR, verify:

- [ ] Website loads without JavaScript errors
- [ ] All navigation links work correctly
- [ ] Responsive design works on mobile, tablet, and desktop
- [ ] Animations play smoothly
- [ ] Contact form validation works
- [ ] Images load properly
- [ ] Page passes basic accessibility checks

### Browser Testing

Test in multiple browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

---

## Questions?

If you have questions, feel free to:
- Open an issue with the "question" label
- Reach out to the maintainers

**Thank you for contributing! 🙏**

---

*This contributing guide is adapted from various open source projects and best practices.*
