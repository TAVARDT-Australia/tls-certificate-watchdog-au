# TLS/SSL Certificate Watchdog

[![Scope of Perimeter Verification](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/au/security-headers-check/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Automated monitoring of SSL/TLS certificate expiration, cryptographic chain integrity, and ACSC Essential Eight compliance in Australia.

***

## 1. Scope of Perimeter Verification

This command-line tool audits certificate lifecycles, cryptographic suites, and trust chains for Australian infrastructure:

* **Preventative Expiry Alert:** Calculates remaining days before certificate expiry with automated alerting thresholds.
* **Cipher and Protocol Audit:** Verifies TLS 1.3 enforcement in alignment with ACSC Essential Eight baselines.
* **Certificate Authority (CA) Validation:** Inspects the root issuer trust chain and Subject Alternative Names (SAN).
* **Zero External Dependencies:** Runs entirely on Python native ssl and socket standard library modules.

***

## 2. Quick Start Guide

Run this tool directly via Python without installing third-party packages:

```bash
python watchdog.py example.com.au
```

***

## 3. Online Diagnostic Tools (Australia)

Audit your public infrastructure using the TAVARDT diagnostic suite:

* [Consent Mode v2 & Privacy Act Validator](https://tools.tavardt.com/au/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/au/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/au/exposed-files-scanner/)
* [Full Australian Tools Portal](https://tools.tavardt.com/au/)

***

## 4. Technical Advisory & Remediation

For enterprise cryptographic auditing, ACSC Essential Eight alignment, and incident response in Australia, contact **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/au/
* **Diagnostic Suite:** https://tools.tavardt.com/au/
* **Technical Contact:** https://ag.tavardt.com/au/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
