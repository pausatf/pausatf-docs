# GitHub Workflows for PAUSATF

This document outlines the GitHub workflows used in PAUSATF repositories.

## Branch Protection Rules

All repositories have branch protection rules for the main branch:

- Require pull request reviews before merging
- Require status checks to pass
- Enforce all administrators to follow these rules
- Require linear history

## Pull Request Process

1. Create a feature branch from main
2. Make changes and commit them
3. Push the branch to GitHub
4. Create a pull request
5. Wait for reviews and status checks
6. Address feedback
7. Merge the pull request

## Dependabot

Dependabot is configured to:

- Check for dependency updates weekly
- Create pull requests for updates
- Apply security patches automatically
- Limit open pull requests to 10 per repository

## GitHub Actions

### wordpress-site

- **Test and Deploy**: Runs tests and deploys changes to production
- **PHP Lint**: Checks PHP syntax
- **WordPress Coding Standards**: Ensures code follows WordPress standards

### infrastructure

- **Terraform Validate**: Validates Terraform configurations
- **Terraform Plan**: Shows planned infrastructure changes
- **Terraform Apply**: Applies infrastructure changes (manual trigger)

### content-assets

- **Backup**: Runs daily backups of the database and media files
- **Restore**: Restores backups (manual trigger)

### pausatf-docs

- **Build Docs**: Builds documentation site
- **Deploy Docs**: Deploys documentation to GitHub Pages
