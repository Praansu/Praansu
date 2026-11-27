# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |

## Reporting a Vulnerability

Please report security vulnerabilities by opening a [GitHub Security Advisory](https://github.com/Praansu/REPO_NAME/security/advisories/new) or emailing **Praansu12@gmail.com**.

Do NOT report security vulnerabilities in public issues, discussions, or pull requests.

We will acknowledge receipt within 48 hours and provide a timeline for a fix.

## Security Best Practices

- All dependencies are scanned weekly via Dependabot
- Docker images are built on push to main
- Secrets are never committed — use `.env` files (gitignored)
- API keys are rotated periodically
- CI runs security-relevant lints (ruff/oxlint)