# PAUSATF GitHub Repository Structure

This document outlines the structure and purpose of the PAUSATF GitHub repositories.

## Repository Overview

PAUSATF uses a consolidated repository structure to simplify maintenance and collaboration:

1. **[wordpress-site](https://github.com/pausatf/wordpress-site)**: Main WordPress codebase
2. **[infrastructure](https://github.com/pausatf/infrastructure)**: Infrastructure, deployment, and monitoring code
3. **[content-assets](https://github.com/pausatf/content-assets)**: Content, media, and backups
4. **[pausatf-docs](https://github.com/pausatf/pausatf-docs)**: Comprehensive documentation

## Repository Details

### wordpress-site

The main WordPress codebase repository contains:

- WordPress core (as a submodule)
- Custom plugins
- TheSource theme (as a submodule)
- Configuration files

**Development Workflow:**
1. Clone the repository
2. Initialize and update submodules
3. Set up local development environment
4. Create feature branches for changes
5. Submit pull requests for review

### infrastructure

The infrastructure repository contains:

- Terraform configurations
- Deployment scripts
- Monitoring configurations
- Security settings

**Usage:**
1. Clone the repository
2. Follow the setup instructions in the README
3. Use Terraform commands to manage infrastructure
4. Use deployment scripts to deploy changes

### content-assets

The content-assets repository contains:

- Media files
- Backup scripts and data
- Content exports

**Usage:**
1. Clone the repository
2. Follow the backup and restore instructions in the README
3. Use the backup scripts to create and manage backups

### pausatf-docs

The documentation repository contains:

- Technical documentation
- User guides
- Process documentation
- Development standards

**Contributing to Documentation:**
1. Clone the repository
2. Create or update documentation files
3. Submit pull requests for review
