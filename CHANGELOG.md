# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-02-03

### Added

- **Backend**: Initial Spring Boot implementation with secure file storage, RBAC, and database integration.
- **Frontend**: React/TypeScript dashboard with modern UI, real-time metrics, and file management.
- **ML Service**: Python-based Load Prediction Service using Random Forest for proactive scaling.
- **Ops**: Docker Compose orchestration for MySQL, Jenkins, and Gitea.
- **Docs**: Comprehensive setup guides, architectural diagrams, and implementation reports.
- **Community**: Added `LICENSE`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and GitHub templates.

### Security

- Implemented JWT authentication for all API endpoints.
- Added Role-Based Access Control (Admin/User).
- Secured file permission logic (Private/Public/Shared).
