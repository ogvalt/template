# Personal Project Template

A standardized project template for my personal projects to ensure consistent structure, tooling, and best practices across all my repositories.

## Overview

This template repository provides a solid foundation for starting new projects with pre-configured development tools, CI/CD workflows, and common project structure. It's designed to minimize repetitive setup tasks and enforce consistent practices.

## Features

- **Task Automation**: Pre-configured [Taskfile](https://taskfile.dev/) for common development operations
- **Environment Configuration**: Environment variables management via `.env` files
- **Git Hooks**: Pre-commit hooks for code quality enforcement
- **VS Code Integration**: Optimized VS Code settings for development
- **Documentation Structure**: Organized documentation folder
- **CI/CD Setup**: GitHub Actions workflows

## Project Structure

```
├── .github/              # GitHub Actions workflows and configurations
├── .vscode/              # VS Code editor settings
├── docs/                 # Project documentation
├── .gitignore            # Git ignore rules
├── .pre-commit-config.yaml # Pre-commit hooks configuration
├── example.env           # Example environment variables
├── README.md             # This file
└── Taskfile.yaml         # Task runner configuration
```

## Getting Started

1. Clone this template repository or use it as a template for a new project
2. Copy `example.env` to `.env` and adjust variables as needed
3. Install required dependencies (varies by project type)
4. Run `task setup` to initialize the project

## Available Tasks

The repository includes the following pre-configured tasks:

| Task | Description |
|------|-------------|
| `task setup` | Setting up the environment |
| `task build` | Build the project |
| `task test` | Running tests |
| `task lint` | Linting the code |
| `task deploy` | Deploying the project |
| `task clean` | Cleaning up |

## Customization

When using this template for a new project:

1. Update this README with project-specific information
2. Modify the Taskfile.yaml to include project-specific commands
3. Adjust the .pre-commit-config.yaml to match project requirements
4. Update environment variables in example.env

## License

[Specify your preferred license]

## Author

[Your Name/Username]