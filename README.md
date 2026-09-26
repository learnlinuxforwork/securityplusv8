<div align="center">

<img src="https://free.learnlinuxforwork.com/assets/img/ST-Brain-Logo.png" alt="Shea's Tech" width="120">

# CompTIA Security+ SY0-801 V8 Course

### Zero to CompTIA Security+

**Fifteen weeks. Fifteen hands-on lab guides. Every domain, every objective.**
Built directly from CompTIA's official SY0-801 V8 Exam Objectives document.

[**securityplusv8.learnlinuxforwork.com**](https://securityplusv8.learnlinuxforwork.com) · [Why I built this](https://securityplusv8.learnlinuxforwork.com/#story)

[![Exam](https://img.shields.io/badge/exam-SY0--801%20V8-b45309?style=flat-square)](https://www.comptia.org/certifications/security)
[![License](https://img.shields.io/badge/license-AGPL--3.0--or--later-b45309?style=flat-square)](https://learnlinuxforwork.com/license)
[![Cost](https://img.shields.io/badge/cost-%240-b45309?style=flat-square)](#what-it-costs)
[![Tracking](https://img.shields.io/badge/tracking-none-b45309?style=flat-square)](#features)
[![PRs](https://img.shields.io/badge/PRs-welcome-b45309?style=flat-square)](#contributing)

<br>

| 15 | 15 | 5 | $0 |
|:--:|:--:|:--:|:--:|
| **weeks** | **lab guides** | **exam domains** | **to start** |

</div>

---

## Quick start

```bash
git clone https://github.com/learnlinuxforwork/securityplusv8.git && cd securityplusv8
python3 -m http.server 8000       # read the course at localhost:8000
```

Then open [Lab Guide 1](lab/week-01.html).

---

## Why this course is longer than its siblings

Security+ isn't a single-product exam. CompTIA's own SY0-801 V8 objectives document
spans **five domains and 27 numbered sub-objectives** — general security concepts,
threats/vulnerabilities/attacks, security architecture, security operations, and
governance/risk/compliance. That's genuinely broader than [RHCSA](https://rhcsa.learnlinuxforwork.com)
or [LFCS](https://lfcs.learnlinuxforwork.com), which is why this course runs 15
weeks instead of 12.

At the time this course was written, CompTIA's own objectives document (version 1.4)
listed the exam's **question count and test length as "TBD"** — SY0-801 had not
fully launched. Everything else — the five domains, their published weightings, and
every sub-objective — comes straight from that document.

---

## Ethics, once, clearly

Every scanning, exploitation, or attack-simulation step in this course's labs runs
on VMs you build yourself, on a network isolated from the internet and from anyone
else's systems. Running the same tools against anything else — without explicit
written authorization — is illegal in most jurisdictions. This isn't a formality.

---

## What's inside

**Fourteen sections**, built to the same shape as the
[RHCSA](https://rhcsa.learnlinuxforwork.com), [LFCS](https://lfcs.learnlinuxforwork.com),
[LPI Linux Essentials](https://lpi.learnlinuxforwork.com), and
[AWS DevOps](https://free.learnlinuxforwork.com) courses:

| # | Section | What it gives you |
|:--|:--|:--|
| 01 | How This Course Works | Pacing options, the 50/35/15 rhythm |
| 02 | What CompTIA Security+ V8 SY0-801 Actually Is | Format, all 5 domains with published weightings |
| 03 | Build Your Home Lab | Two VMs — secure-target and kali-tools |
| 04 | No Machine to Install On? Rent One | A single cloud instance option |
| 05 | The Certification Ladder | CySA+, RHCSA (cloud/DevOps path), LFCS, PenTest+ |
| 06 | Exam Objective Coverage Map | All 27 sub-objectives mapped to weeks |
| 07 | The 15-Week Plan | Checkable tasks, progress saved in your browser |
| 08 | Lab Guides | Fifteen standalone guides |
| 09 | Employer Verification | An optional paid track for a certificate |
| 10 | Core Resource List | CompTIA, MITRE ATT&CK, NIST, OWASP, and more |
| 11 | Estimated Costs | Honest numbers |
| 12 | Exam Day | Habits and the morning-of checklist |
| 13 | Why I Built This Guide | The reason this is free |
| 14 | Credits and Trademarks | CompTIA, Kali/OffSec, MITRE, NIST, and everyone else |

---

## The five domains

| Domain | Weight | Weeks |
|:--|:--:|:--|
| 1.0 General Security Concepts | 16% | 1–2 |
| 2.0 Threats, Vulnerabilities, and Attacks | 24% | 3–6 |
| 3.0 Security Architecture | 19% | 7–8 |
| 4.0 Security Operations | 27% | 9–12 |
| 5.0 Security Program Management and Oversight | 14% | 13–14 |
| Mock exam, remediation, exam day | — | 15 |

---

## What it costs

| Item | Estimate |
|:--|:--|
| This course and all 15 lab guides | **$0** |
| Rocky Linux / Ubuntu Server + Kali Linux | **$0** |
| Two lab VMs on hardware you already own | **$0** |
| [CompTIA Security+ exam (SY0-801 V8)](https://www.comptia.org/certifications/security) | ~$404 (check CompTIA's current pricing) |
| Cloud instance, if you can't install locally | ~$6/month |

---

## Deployment

Push to `main` → [`.github/workflows/pages.yml`](.github/workflows/pages.yml) validates
`data/securityplus.json`, confirms all fifteen lab guides exist, runs the scope check,
and deploys to GitHub Pages at
[securityplusv8.learnlinuxforwork.com](https://securityplusv8.learnlinuxforwork.com).

First-time setup:

1. **Settings → Pages → Source:** GitHub Actions
2. **Settings → Pages → Custom domain:** `securityplusv8.learnlinuxforwork.com`, then tick *Enforce HTTPS*
3. DNS (managed in Squarespace for this domain): add a **CNAME** record — host `securityplusv8`, pointing to `learnlinuxforwork.github.io`

The [`CNAME`](CNAME) file keeps the domain set across deploys — don't delete it.

---

## Content and licensing

All course text and lab guides are **original work**, written for this repository,
built directly from
[CompTIA's SY0-801 V8 Exam Objectives](https://www.comptia.org/certifications/security)
(version 1.4) — the authoritative statement of what the exam covers.

Licensed under the **[GNU AGPL v3.0 or later](https://learnlinuxforwork.com/license)**. See also [LICENSE](LICENSE). Free forever.

---

## Credits and trademarks

Not affiliated with, sponsored by, endorsed by, or certified by CompTIA, Inc. or any
other organization named here. Full credit table in
[section 14](https://securityplusv8.learnlinuxforwork.com/#credits).

If you own one of these marks and want the wording changed,
[open an issue](https://github.com/learnlinuxforwork/securityplusv8/issues).

---

<div align="center">

### Related

[**RHCSA Course**](https://rhcsa.learnlinuxforwork.com) · 12 weeks, Red Hat–specific<br>
[**LFCS Course**](https://lfcs.learnlinuxforwork.com) · 12 weeks, distro-neutral, performance-based<br>
[**LPI Linux Essentials Course**](https://lpi.learnlinuxforwork.com) · 6 weeks, your first Linux certification<br>
[**AWS DevOps Course**](https://free.learnlinuxforwork.com) · 54 weeks, Linux to AWS DevOps<br>
[**Learn Linux For Work**](https://www.learnlinuxforwork.com) · structured, work-focused Linux training

<br>

Built by **Shea** · [Shea's Tech](https://www.sheastech.io) · [LinkedIn](https://www.linkedin.com/in/sheastech/) · [YouTube](https://www.youtube.com/@sheastech?sub_confirmation=1)

*If anything here is wrong, report it and we'll fix it.*

</div>
