# .github

Default GitHub issue and pull request templates for my repositories.

## Purpose

This repository provides account-level default templates used by repositories that do not define their own corresponding templates.

The templates are intentionally repository- and model-agnostic. Repository-specific development rules, architecture, toolchains, and AI-agent policies should remain in each repository's `AGENTS.md`, `docs/`, or other local configuration.

## Templates

- `.github/ISSUE_TEMPLATE/implementation.md`
  - Scoped implementation work with explicit references, design decisions, acceptance criteria, verification, and stop conditions.
- `.github/ISSUE_TEMPLATE/bug.md`
  - Bug investigation and minimal corrective implementation.
- `.github/ISSUE_TEMPLATE/config.yml`
  - Keeps blank issues available for lightweight notes and tasks that do not fit the standard templates.
- `PULL_REQUEST_TEMPLATE.md`
  - Summarizes changes, related issues, verification, and remaining notes or risks.

## Repository-specific overrides

Repositories may define their own templates when they require project-specific workflows. In that case, keep the local templates intentional and avoid duplicating account-level defaults unless an override is necessary.
