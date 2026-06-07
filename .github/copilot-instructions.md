# Copilot Instructions for this Repository

## Overview
This repository is a Stackblitz core project that provides foundational tooling and utilities for building and deploying web applications. It serves as the backbone for the Stackblitz platform and agent skills integration.

## Key Guidelines
- Follow consistent coding standards and TypeScript best practices
- Use Jest for unit and integration tests
- Document all public APIs and exported functions with JSDoc comments
- Maintain backward compatibility where possible
- Write clear commit messages following conventional commits

## Tech Stack
- Language: TypeScript/JavaScript
- Framework: Node.js
- Build Tool: Webpack/Rollup
- Testing: Jest
- Dependencies: Core runtime dependencies for Stackblitz platform

## File Structure
- `/src` - Source code for core modules
- `/tests` - Unit and integration test files
- `/docs` - Project documentation
- `/dist` - Compiled/bundled output (generated)
- `/.github` - GitHub workflows and configurations

## Common Tasks

### How to run the project locally
```bash
npm install
npm run build
npm run dev
```

### How to run tests
```bash
npm test
npm run test:watch  # Watch mode for development
npm run test:coverage  # Generate coverage report
```

### How to build/deploy
```bash
npm run build      # Production build
npm run bundle     # Create distribution bundles
npm run release    # Prepare release version
```

## Important Notes

### Setup Requirements
- Node.js 18+ required
- npm or yarn as package manager
- Git for version control

### Performance Considerations
- Minimize bundle size for core modules
- Optimize for tree-shaking and code splitting
- Monitor runtime performance metrics
- Keep dependencies up to date

### Security Guidelines
- Regularly audit dependencies for vulnerabilities
- Follow secure coding practices
- Sanitize user inputs
- Review third-party integrations carefully
- Use environment variables for sensitive configuration

### Code Quality
- Maintain 80%+ test coverage
- Use ESLint and Prettier for code formatting
- Run linting before commits
- Request code reviews for all PRs
- Use TypeScript strict mode

### Contribution Guidelines
- Create feature branches from `main`
- Write descriptive commit messages
- Include tests for new features
- Update documentation accordingly
- Reference related issues in PR descriptions
