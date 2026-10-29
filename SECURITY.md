# Security Policy

## Reporting a vulnerability

Please do not publish credentials, API keys, personal information, or exploit details in a public issue. Contact the repository owner privately through the contact method listed on their GitHub profile and include a concise description and steps to reproduce the issue.

## Secrets and configuration

Do not commit `.env` files, signing keys, access tokens, service-account credentials, or machine-specific configuration. If a secret is committed, revoke or rotate it; deleting it in a later commit does not remove it from Git history.
