# Contributing to Frontend Handbook

Thank you for your interest in contributing to the Frontend Handbook! This document provides guidelines and instructions for contributing.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for improvement:

1. Check if the issue already exists in the [Issues](https://github.com/yourusername/frontend-handbook/issues) section
2. If not, create a new issue with a descriptive title and detailed information

### Submitting Changes

1. Fork the repository
2. Create a new branch for your changes (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes with clear, descriptive commit messages
5. Push to your branch (`git push origin feature/amazing-feature`)
6. Submit a Pull Request

### Pull Request Process

1. Update the README.md or documentation with details of changes if appropriate
2. Your PR will be reviewed by maintainers, who may request changes
3. Once approved, your PR will be merged

## Content Guidelines

### Adding New Content

When adding new content to the handbook:

1. Follow the existing structure and formatting
2. Use clear, concise language
3. Include practical examples where appropriate
4. Cite sources for any referenced material
5. Ensure content is accessible and inclusive

### File Structure

Place new content in the appropriate directory:

- `/src/html/` - HTML-related content
- `/src/css/` - CSS-related content
- `/src/javascript/` - JavaScript-related content
- `/src/frameworks/` - Framework-specific content
- `/src/tools/` - Development tools content
- `/src/best-practices/` - Best practices content

### MDX Format

All content should be written in MDX format with the following frontmatter:

```mdx
---
title: 'Your Title Here'
description: 'A brief description of the content'
---

## Your content here
```

## Development

### Local Setup

1. Clone your fork of the repository
2. Install dependencies: `npm install`
3. Install Mintlify CLI: `npm i -g mintlify`
4. Run the development server: `mintlify dev`
5. Visit `http://localhost:3000` to see your changes

### Testing

Before submitting a PR, please:

1. Test your changes locally
2. Ensure all links work correctly
3. Check for any formatting issues

## Questions?

If you have any questions about contributing, please open an issue with your question.

Thank you for helping improve the Frontend Handbook!