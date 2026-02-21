# TestCPRepo1

A cloud configuration profile repository for managing component versions and dependencies.

## Overview

This repository serves as a central location for managing versions and branch references of dependent repositories in your microservices architecture.

## Configuration

All version and branch configurations are managed through the `.env` file.

### Environment Variables

- `DEMOREPOFORPRODUCT1` - Version of DemoRepoForProduct1 (e.g., `1.0.0`)
- `DEMOREPOFORPRODUCT1_BRANCH` - Branch name for DemoRepoForProduct1 (e.g., `release-1.0.0`)

## Usage

Include this repository in your CI/CD pipeline to:
- Manage consistent versions across dependent services
- Control branch deployments
- Maintain a single source of truth for component versions

## Current Configuration

```
DEMOREPOFORPRODUCT1=1.0.0
DEMOREPOFORPRODUCT1_BRANCH=release-1.0.0
```
