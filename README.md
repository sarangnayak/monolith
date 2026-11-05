# MONOLITH

**Infrastructure, under your control.**

MONOLITH is a self-hosted infrastructure and AI automation platform
designed to run on privately owned hardware.

## Vision

Build a secure, modular platform that provides:

- Self-hosted applications and services
- User authentication and access management
- File and data management
- System monitoring and infrastructure visibility
- AI-powered automation and agent workflows
- Secure remote access for invited users

## Architecture

MONOLITH begins as a modular monolith.

- Frontend: React + TypeScript
- Backend: Node.js + TypeScript
- Database: SQLite
- Infrastructure: Linux
- Remote access: Tailscale

## Project Structure

- `apps/web` — Web application
- `apps/api` — Backend API
- `packages` — Shared packages
- `infrastructure` — Server configuration
- `scripts` — Automation scripts
- `docs` — Technical documentation
- `tests` — Automated tests
- `notes` — Development notes

## Development Status

Early development — infrastructure and project foundation.

## Security Principles

- Least-privilege access
- No exposed secrets
- Authentication and authorization
- Secure remote access
- Automated backups
- Auditable operations
