# 🔒 Security Policy

Thank you for taking the time to help keep this project and its users safe. This document explains which versions receive security updates and how to responsibly report a vulnerability.

---

## 🧩 Supported Versions

Security fixes are applied only to the versions listed below. Please make sure you are using a supported version before reporting an issue.

| Version                   | Supported |
| ------------------------- | :-------: |
| `main` (latest)           |    ✅     |
| Tagged releases (latest)  |    ✅     |
| Older / archived releases |    ❌     |

If you're on an unsupported version, please update to the latest release first — the issue may already be fixed.

---

## 🎯 Scope

This policy covers security issues in the source code, configuration, and dependencies of this repository. Examples of in-scope reports:

- Remote code execution, injection, or deserialization flaws
- Authentication / authorization bypass
- Exposure of secrets, credentials, or sensitive data
- Cryptographic weaknesses (e.g. weak key handling, insecure randomness)
- Path traversal, arbitrary file read/write
- Supply-chain issues in a bundled dependency

**Out of scope:** issues that require physical access to a user's device, purely theoretical attacks with no practical exploit path, and general bugs with no security impact (please open a normal issue for those instead).

---

## 🐞 Reporting a Vulnerability

If you discover a **security vulnerability** or **potential risk**, please report it privately and responsibly — **do not** open a public issue, pull request, or discussion describing it, as this could put users at risk before a fix is available.

### 📬 How to Report

Choose whichever channel you're most comfortable with:

1. **GitHub Private Security Advisory** _(preferred)_

   Go to the repository's **Security** tab → **Report a vulnerability** to open a private advisory directly with me.
2. **Email**

   Send details to **<shakalbhau007@gmail.com>**

### 📝 What to Include

To help me triage and fix the issue quickly, please include as much of the following as possible:

- A clear description of the vulnerability and its potential impact
- Steps to reproduce it (proof-of-concept code or a minimal example, if possible)
- The affected version, file, or commit
- Any suggested fix or mitigation (optional)

---

## 🛠️ What Happens Next

| Stage                                                                          | Timeline                                |
| ------------------------------------------------------------------------------ | --------------------------------------- |
| **Acknowledgment** — I confirm your report has been received                   | Within **24–48 hours**                  |
| **Initial assessment** — I confirm whether it's a valid issue and its severity | Within **5 business days**              |
| **Fix & release** — a patch is developed and released                          | Timeline depends on severity/complexity |
| **Disclosure** — you're notified, and credited if desired, once resolved       | After the fix is released               |

If you don't hear back within 48 hours, please feel free to follow up — it's possible the report was missed.

---

## 💖 Responsible Disclosure

I genuinely appreciate ethical hackers, researchers, and contributors who help make this project safer. In return, I ask that you:

- Give me a reasonable amount of time to investigate and patch the issue before any public disclosure
- Avoid accessing, modifying, or deleting data that isn't yours while testing
- Avoid exploits that could degrade the experience of other users (e.g. denial-of-service testing on live/shared instances)
- Report issues **privately first** — no public exploits or leaks before a patch is released 🙏

With your permission, security researchers who responsibly report valid vulnerabilities will be credited in the release notes or an acknowledgments section.

---

Thank you for helping keep this project secure! 🙌

---
