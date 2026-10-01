# Security Policy

## Supported Versions

Currently, only the latest version of the application is supported with security updates. If you are experiencing a security issue, please ensure you are running the most recent commit on the `main` branch.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| Older   | :x:                |

## Reporting a Vulnerability

Security is taken very seriously. If you discover a security vulnerability within this project (such as leaked credentials, dependency vulnerabilities, or cross-site scripting risks), please do not report it via public GitHub issues.

Instead, please follow these steps:
1. Send an email to the repository owner or use GitHub's private vulnerability reporting feature if enabled.
2. Provide a detailed description of the vulnerability, including steps to reproduce it.

You should receive a response within 48 hours acknowledging receipt of the vulnerability. 

## Best Practices for Contributors
- **Never commit API Keys:** Ensure that no real API keys (like Google Maps API keys) are hardcoded into the `web/index.html` or Dart files. Always use `.env` files and ensure they are added to `.gitignore`.
- **Keep dependencies updated:** Regularly run `flutter pub upgrade` to ensure you are not pulling in packages with known CVEs.
