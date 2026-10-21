# Security Policy

## Scope
This project is a browser-based simulation of a retro operating-system interface. It is **not** Microsoft Windows 95, does not execute operating-system binaries, and its simulated login is **not** real authentication.

## Supported versions
Security fixes are considered for the latest version on the default branch. There is no separately supported release series.

## Reporting vulnerabilities
Please **do not disclose exploitable issues in a public issue before a fix is available**. Use GitHub's private vulnerability reporting feature if enabled, or contact the maintainer privately through the contact methods listed on their GitHub profile. If no private reporting channel is available, first request a secure contact channel without sharing exploit details.

When reporting, include the affected URL or commit, reproduction steps, impact, and suggested mitigation if known. Do not include credentials, personal information, or attack traffic.

## Security considerations
- Never enter real credentials into the simulated login.
- Treat any future file import or user-generated HTML as untrusted input.
- Avoid introducing third-party script dependencies without review.
- Do not mistake the simulated BIOS, filesystem, or browser for a security boundary.
