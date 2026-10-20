# Security Policy

## Supported Versions
We currently support and provide security updates for:
- **v1.0.1** (Latest stable)

## Official Security Contact & PGP Key
- **Security Contact Email**: `security@bluewhale.stellar.org` (cc: `lewechigodsfavour@gmail.com`)
- **PGP Fingerprint**: `4B9A 8F21 C3E0 71D4 99A2  08E1 55C7 B210 9F4E 6A11`
- **Response SLA**:
  - **Initial Acknowledgment**: Within **48 hours** of receipt.
  - **Triage & Severity Assessment**: Within **5 business days**.
  - **Remediation & Coordinated Disclosure**: Within **14–30 days** depending on severity.

## GitHub Private Vulnerability Reporting

This repository has **GitHub Private Vulnerability Reporting** enabled to allow researchers to submit vulnerability reports directly and privately without exposing potential threats publicly.

### How to Report via GitHub:
1. Navigate to the [Security Advisories](https://github.com/progidyken-hub/BLUEWHALE/security/advisories) tab of this repository.
2. Click the **"Report a vulnerability"** button.
3. Fill out the advisory form with:
   - Affected ecosystem package (`@redishfish/bluewhale-core`, `core-go`, `core-dart`, or `@redishfish/bluewhale`).
   - Vulnerability severity estimate (CVSS vector).
   - Detailed proof-of-concept (PoC) code or reproduction steps.
   - Proposed mitigation or patch if available.
4. Submit the report. Our security maintainers will be notified privately and begin triaging within our committed SLA window.

### Benefits of Private Vulnerability Reporting:
- **Confidential Triage**: Maintainers and reporters collaborate privately in a secure advisory workspace.
- **Private Fork Collaboration**: Security patches can be developed, tested, and reviewed in temporary private forks before publication.
- **Automated CVE Assignment**: GitHub facilitates rapid CVE ID assignment and coordinated public disclosure upon patch release.

## Alternative Reporting Channels
If you cannot use GitHub Private Vulnerability Reporting, you may submit via encrypted email:

1. **Private Reporting**: Do **NOT** open a public GitHub issue or discussion.
2. **Encrypted Email**: Send full reproduction steps, affected package versions, and impact analysis to **security@bluewhale.stellar.org** encrypted with the PGP key above.
3. **Response Guarantee**: We will acknowledge your report within **48 hours** and coordinate a patch and advisory timeline.

Thank you for helping us keep the Stellar ecosystem safe.
