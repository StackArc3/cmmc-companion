# Security Policy

## Reporting a Vulnerability

Please report security vulnerabilities through GitHub's private vulnerability reporting feature:

1. Go to the **Security** tab of this repository
2. Click **Report a vulnerability**
3. Fill out the advisory form

This keeps the report private until a fix is released.

**Please do not open public issues for security vulnerabilities.**

## Response Timeline

- **Initial Response:** Within 72 hours
- **Status Update:** Within 7 days
- **Fix Timeline:** Varies by severity (critical issues prioritized)

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | :white_check_mark: |

## Scope

This tool runs entirely client-side with no backend. Security concerns include:
- Cryptographic implementation flaws
- Client-side vulnerabilities (XSS, etc.)
- Logic errors in compliance checks
- Documentation inaccuracies that could lead to misconfiguration

