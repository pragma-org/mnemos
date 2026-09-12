# Security Policy Template

Use this template as a starting point for a project `SECURITY.md` file.

Replace bracketed text, remove sections that do not apply and add project-specific reporting, support and operations details before publishing.

## Security Policy

[Project name] takes security seriously. If you discover a security vulnerability, please report it responsibly so maintainers can protect users, contributors and the wider ecosystem.

**Do not report undisclosed security vulnerabilities through public GitHub issues, discussions, pull requests, social media or public chat channels.**

## Supported Versions

Describe which versions receive security fixes.

| Version | Supported |
| --- | --- |
| latest release | yes |
| older releases | no |

Users should upgrade to the newest supported release before reporting an issue that may already have been fixed.

## Reporting A Vulnerability

Report vulnerabilities privately through:

- GitHub security advisory form:
- Security email:
- Other private reporting channel:

Please include:

- a clear description of the vulnerability;
- affected version, commit or deployment;
- steps to reproduce, if safe to share;
- potential impact;
- affected users, funds, systems or data;
- logs, screenshots or proof-of-concept details, if appropriate;
- suggested fix, if known;
- whether you want public credit or prefer to remain anonymous.

| Recommended reporting channel |
| --- |
| We recommend using GitHub private vulnerability reporting or a dedicated security email so sensitive details are not exposed before maintainers can investigate and prepare a fix. |

## Response Timeline

Expected response timeline:

- acknowledgement:
- initial assessment:
- fix or mitigation target:
- public disclosure target:

Example:

- acknowledge report within 48 hours;
- provide an initial assessment within 7 days;
- keep the reporter informed while the issue is investigated and fixed.

These timelines may vary depending on severity, maintainer availability and complexity.

## Disclosure Process

Maintainers will:

1. acknowledge the report;
2. investigate and assess severity;
3. confirm affected versions or deployments;
4. prepare a fix, mitigation or advisory;
5. coordinate release timing where needed;
6. disclose publicly after users have had a reasonable chance to upgrade or protect themselves.

Public disclosure may include:

- GitHub Security Advisory;
- release notes;
- changelog entry;
- blog post;
- project announcement;
- CVE or ecosystem advisory, if applicable.

## Severity And Scope

Examples of security issues:

- unauthorized access;
- loss or theft of funds;
- signature, key, wallet or credential exposure;
- consensus, validation or transaction correctness bugs;
- smart contract vulnerabilities;
- remote code execution;
- privilege escalation;
- denial-of-service vulnerabilities;
- sensitive data exposure;
- supply-chain compromise;
- dependency vulnerabilities with project impact.

Issues that may not be security vulnerabilities:

- general support requests;
- non-sensitive bugs;
- feature requests;
- public information exposure with no security impact;
- automated scanner reports without project-specific impact;
- social engineering against individual contributors outside project systems.

## Secrets And Credentials

Projects should document how secrets are handled.

Recommended guidance:

- never commit mnemonics, private keys, signing keys, API keys, passwords or production credentials;
- use environment variables, secret managers or protected deployment settings;
- redact secrets from logs, config output, crash reports and screenshots;
- restrict local key-file permissions where applicable;
- rotate any credential that may have been exposed;
- use testnet-only credentials for demos and clearly label them.

## Testnet And Demo Material

If the project includes demo wallets, test keys, fixtures or sample credentials, explain their limits.

**Demo/test credentials:**
- network:
- purpose:
- safe to publish:
- expiration or rotation plan:

Do not reuse testnet/demo credentials on mainnet or in production.

## Operational Incidents

If a key, credential or production system is exposed:

1. stop using the compromised credential or system;
2. rotate affected keys and credentials;
3. revoke exposed tokens or sessions;
4. assess affected users, funds, data and infrastructure;
5. preserve evidence needed for investigation;
6. notify affected users or ecosystem partners where appropriate;
7. publish an advisory when it is safe to do so.

## Safe Harbor

Security researchers acting in good faith should not be penalized for responsible reporting.

Good-faith research means:

- reporting privately and promptly;
- avoiding public disclosure before maintainers can respond;
- avoiding access to unrelated data or systems;
- avoiding disruption, theft, extortion or destructive testing;
- giving maintainers reasonable time to investigate and fix.

This policy does not authorize illegal activity or access to third-party systems.

## Contact

Security contact:

Backup contact:

Preferred language:

PGP key, if available:

Timezone or expected response hours:

## Maintainer Checklist

- [ ] Private reporting channel is listed.
- [ ] Public issues are discouraged for undisclosed vulnerabilities.
- [ ] Supported versions are defined.
- [ ] Expected response timeline is stated.
- [ ] Disclosure process is described.
- [ ] Secrets and credential guidance is included.
- [ ] Testnet/demo credentials are clearly labelled, if any.
- [ ] Incident response basics are included.
- [ ] Safe harbor language is included or intentionally removed.
- [ ] Security contact information is current.
