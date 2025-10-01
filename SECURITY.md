# Security Policy

We take the security of our systems and our customers’ data seriously. Thank you for taking the time to responsibly report a vulnerability.

---

## 🔐 How to Report a Vulnerability (Private Only)

Please DO NOT open a public issue for security problems.

Use one of the following private reporting channels:

1. Preferred: Click the “Report a vulnerability” button in the repository’s **Security** tab (GitHub Private Vulnerability Reporting is enabled).  
   - Direct link (adjust if in another repo): https://github.com/LuxTronic/.github/security/advisories/new
2. Alternate (if GitHub is unavailable): Email us at security@luxtronic.ai
3. (Optional) PGP encrypted reports: (Add your team’s PGP key fingerprint or link here if/when available)

Include (as applicable):
- A clear description of the issue and potential impact
- Steps to reproduce ( PoC scripts, requests, payloads )
- Affected endpoints, files, or components
- Any mitigation or exploit prerequisites
- Suggested remediation ideas (if you have them)

We will acknowledge receipt promptly (see timeline below).

---

## ✅ Supported & Maintained

We prioritize security fixes for:
- Production services and APIs currently in active use
 - Repositories under the LuxTronic GitHub organization that are not archived
- Latest major release lines of any published SDKs or libraries

Out-of-support:
- Deprecated or archived repositories
- Experimental branches not marked stable
- Forks we do not maintain

---

## 🕒 Response & Disclosure Timeline (Target)

| Phase | Target SLA |
|-------|------------|
| Acknowledge report | ≤ 2 business days |
| Initial assessment / triage | ≤ 5 business days |
| Status update cadence | Weekly (or sooner on progression) |
| Fix development (severity dependent) | Critical: ≤ 14 days, High: ≤ 30 days, Medium: ≤ 60 days, Low: Best effort |
| Coordinated disclosure | Mutually agreed; typically after fix & deployment |

If you do not hear back within the acknowledgement window, please gently follow up (different channel if possible).

---

## 🧪 Scope

In scope (examples):
- Production web apps & APIs operated by LuxTronic
- Authentication, authorization, session handling
- Data exposure or access control flaws
- Injection (SQLi, command, deserialization)
- RCE, privilege escalation, SSRF, IDOR
- Significant logic flaws affecting integrity or confidentiality
- Dependency confusion or supply-chain risks affecting our published packages

Out of scope (unless demonstrably exploitable):
- Denial of Service via excessive valid requests (volumetric only)
- SPF/DMARC/ DKIM suggestions without exploit chain
- Clickjacking on non-sensitive endpoints
- Missing security headers with no practical impact
- Use of outdated libraries without a proven exploit path
- Self XSS (affecting only the reporting user)
- Email enumeration or generic error messages
- Rate limiting requests unless they directly enable an exploit
- Vulnerabilities requiring physical access or rooted devices under the user’s control

---

## 🛡️ Safe Harbor / Good Faith

We will not pursue legal action against researchers who:
- Make a good faith effort to follow this policy
- Avoid privacy violations, destruction of data, or service disruption
- Do not exfiltrate more data than necessary to demonstrate the issue
- Provide us reasonable time to remediate before any disclosure
- Do not publicly disclose details without coordination

If you are unsure whether something is in scope, ask first.

---

## 🤝 Coordination & Disclosure

We prefer coordinated disclosure. After remediation we may:
- Publish a GitHub Security Advisory
- Credit you (with consent) in an acknowledgements section
- Provide CVE assignment (if applicable)

Let us know how you’d like to be credited (name, handle, link). Anonymous credit is welcome.

---

## 🔄 Remediation Approach

We assess vulnerabilities using a combination of CVSS, exploitability context, and business impact. Remediation may include:
- Patch / code change
- Configuration or infrastructure updates
- Rotation of secrets / credentials
- Dependency upgrades
- Compensating controls (monitoring, WAF rules) if immediate fix is complex

---

## 🧾 Reporting Template (Optional)

You can copy/paste this into the private advisory form:

```
Title: [Short summary of the issue]

Summary:
[Describe the vulnerability and impact]

Steps to Reproduce:
1.
2.
3.

Proof of Concept:
[Code / payload / request / screenshot]

Affected Components / Repos:
[List]

Impact Assessment:
[Confidentiality / Integrity / Availability implications]

Suggested Remediation:
[Ideas]

Researcher Contact / Credit Preference:
[Name / Handle / Email / Anonymous]
```

---

## 🙏 Acknowledgements

We appreciate the security research community’s efforts to help keep our ecosystem safe.

(We will list credited researchers here.)

---

## 📬 Contact

security@luxtronic.ai  
Primary Channel: GitHub Private Vulnerability Reporting

Thank you for helping us protect our users and systems.
