# Security Policy

## Supported versions

Lorelight is sideloaded, so only the newest release receives fixes. Please update before reporting.

| Version | Supported |
| --- | --- |
| Latest release | ✅ |
| Older releases | ❌ |

## Reporting a vulnerability

Please report privately, not in a public issue.

1. Open this repository's **Security** tab.
2. Choose **Report a vulnerability** (GitHub private vulnerability reporting).
3. Include the affected version, your device and Android version, a clear description of the issue and its impact, and reproduction steps or a proof of concept if you have one.

What to expect: acknowledgement within 5 days, an initial assessment within 14 days, and a fix in the next release once confirmed. Reporters are credited in release notes unless they prefer to stay anonymous.

**Never include** keystores, passwords, signing keys, or `.env` contents in a report, public or private.

## Scope

In scope:

- The published release builds and how they were produced
- The build and release workflow in this repository
- Credential handling in the release pipeline

Out of scope:

- Third-party source plugins and manga extensions, and the remote sites they read
- Issues requiring a rooted or already-compromised device, or physical access to an unlocked phone
- Findings from modified or unofficial builds of Lorelight

## How this project handles secrets

No keystore, password, or `.env` file is ever committed to any Lorelight repository, public or private. Release signing credentials exist only as encrypted GitHub Actions secrets and are used transiently inside an ephemeral build runner. Only the maintainer holds the signing key.

## Notes for users

Install APKs only from this repository's Releases page. A build from anywhere else is not Lorelight. An update that refuses to install over your existing app indicates a signing-key mismatch — stop and check the source.
