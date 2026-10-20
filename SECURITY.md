# Security Policy

## Supported Versions
Current main branch (demo / test).

## Reporting a Vulnerability
Please open a private GitHub issue or email the project maintainers. Do not disclose publicly until patched.

## Security Practices
- No private keys, seeds, or API secrets are stored in this repository.
- All wallet encryption happens client-side (AES-GCM + PBKDF2).
- Seed Round emails are routed via Formspree (or equivalent) so no credentials live in the frontend.
- Content-Security-Policy header is recommended for production.
- This is a demo. Do not use with real funds until full protocol integration and audit.

## Self-custody
You control your keys. Never share seed phrases.
