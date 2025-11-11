# ALXprodev Advanced Git - Git-Flow Project

## Overview
This project demonstrates the implementation of Git-Flow workflow for managing features, releases, and hotfixes in a structured and scalable way.

## Git-Flow Structure

- **main**: Production-ready code
- **develop**: Integration branch for ongoing development
- **feature/***: New features in progress
- **release/***: Preparation for production releases
- **hotfix/***: Critical bug fixes on the main branch

## Features

### Login Page
Directory: `login-page/`
Status: In development

### Signup Page
Directory: `signup-page/`
Status: In development

## Workflow

### Feature Development
```bash
git flow feature start <feature-name>
# Make changes
git flow feature finish <feature-name>
```

### Release Process
```bash
git flow release start <version>
# Prepare release
git flow release finish <version>
```

### Hotfix Process
```bash
git flow hotfix start <version>
# Fix bug
git flow hotfix finish <version>
```

## Project Structure

```
ALXprodev-advanced_git/
├── README.md
├── login-page/
│   └── README.md
└── signup-page/
    └── README.md
```

## Git Hooks

### Pre-commit Hook
Checks that all directories contain a README.md file before allowing commits.

### Post-merge Hook
Logs all merges into the main branch with timestamp and commit details.

## Learning Objectives

- Understand Git-Flow branching model
- Manage feature development and releases
- Implement Git hooks for automation
- Collaborate effectively using structured workflows

## Author

ALX Software Engineering Program - DevOps Track
