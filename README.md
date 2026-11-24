# TLS/SSL Certificate Watchdog | TAVARDT Australia

[![Scope of Perimeter Verification](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/au/security-headers-check/)
Automated monitoring of SSL/TLS certificate expiration, cryptographic chain integrity, and ACSC Essential Eight compliance in Australia.

Developed and maintained by the cybersecurity and cyber resilience division of **TAVARDT Australia**.

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

Audit your public infrastructure using the TAVARDT Australia diagnostic suite:

* HTTP Security Headers Checker
* [Consent Mode v2 & Privacy Act Validator](https://tools.tavardt.com/au/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/au/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/au/exposed-files-scanner/)
* [Full Australian Tools Portal](https://tools.tavardt.com/au/)

***

## 4. Technical Advisory & Remediation

For enterprise cryptographic auditing, ACSC Essential Eight alignment, and incident response in Australia, contact **TAVARDT Australia**.
