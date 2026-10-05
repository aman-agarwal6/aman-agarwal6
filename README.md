<a href="https://aman-agarwal6.github.io/"><img src="assets/banner.png" alt="Aman Agarwal: security engineering and applied AI. Iowa State MIS, CompTIA Security+, former HNI cybersecurity intern. Open to entry-level security and AI roles from January 2027." width="100%"></a>

I build security controls and AI-powered tools, test them against real systems, and publish what failed alongside what passed. MIS senior at Iowa State with a Cybersecurity Engineering minor, graduating December 2026; CompTIA Security+; former cybersecurity intern at HNI. **Open to entry-level roles in security engineering, security operations or identity and access management, and AI engineering or automation roles, from January 2027.**

**[Portfolio](https://aman-agarwal6.github.io/)** · [Recruiter summary](https://aman-agarwal6.github.io/overview.html) · [LinkedIn](https://www.linkedin.com/in/aman-agarwal6/) · [Email](mailto:aagarwalcollege@gmail.com)

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://aman-agarwal6.github.io/projects/accessops.html"><img src="assets/accessops.png" alt="AccessOps public demo with synthetic data: a departure case, its next step and the evidence source of each required action"></a>

### [AccessOps](https://aman-agarwal6.github.io/projects/accessops.html)

**Disabled isn't done.** Automated employee offboarding that proves the person's access is really gone. An HR event shuts off their access in Microsoft Entra ID, Keycloak and an Active Directory-compatible directory, and each system is checked to confirm the change.

- **2.6 s** from the HR event to the person signed out and their tokens blocked
- **6** gaps found by live testing, each fixed or documented
- **20 s** for Microsoft Entra ID to confirm the change, in a test tenant

[Case study](https://aman-agarwal6.github.io/projects/accessops.html) · [Live demo](https://aman-agarwal6.github.io/AccessOps/) · [Source](https://github.com/aman-agarwal6/AccessOps)

</td>
<td width="50%" valign="top">

<a href="https://aman-agarwal6.github.io/projects/signalbridge.html"><img src="assets/signalbridge.png" alt="SignalBridge evidence viewer: Wazuh runs from an isolated local lab with synthetic data"></a>

### [SignalBridge](https://aman-agarwal6.github.io/projects/signalbridge.html)

**Catch the access that should have ended.** A detection lab where five detection rules, also written as Sigma, SPL and KQL, flag access that continues after a permission was removed. Tested against real Keycloak, Wazuh, OWASP ZAP and Shuffle.

- **4** writes a removed user could still make, until I found and fixed the race
- **5** detection rules run in Splunk and a Kusto emulator against the same 48 scenarios
- **0** events lost or duplicated when I stopped the Wazuh collector mid-run

[Case study](https://aman-agarwal6.github.io/projects/signalbridge.html) · [Source](https://github.com/aman-agarwal6/signalbridge)

</td>
</tr>
</table>

The two work as a pair: AccessOps sends a signed event for each offboarding step, and SignalBridge verifies those events and opens a critical case if a departed account is used anyway.

## More projects

| Project | What it is | Highlight |
| --- | --- | --- |
| [BetTail](https://aman-agarwal6.github.io/projects/bettail.html) | Live web app where private groups share sports picks and track results | Profit, ROI and leaderboards calculated in the database; row-level security on every exposed table; 6 fixes from my security review |
| [Netted](https://aman-agarwal6.github.io/projects/netted.html) | Personal-finance app for trade profit, shared funds and budgeting | Accounting rules written before any code; MFA enforced in the database; 7-item risk register |
| [Downfield](https://aman-agarwal6.github.io/projects/downfield.html) | Local AI research agent that writes structured NFL reports for BetTail | 32 games across two NFL weeks and 415 saved reports so far; every report checked by code; forecasts graded after each game |

BetTail, Netted and Downfield are private; their case studies link [selected code and tests](https://github.com/aman-agarwal6/aman-agarwal6.github.io/blob/main/docs/PROJECTS.md).

## Experience

**Cybersecurity Intern, HNI Corporation** · May–July 2026  
Automated triage for 3 identity-alert types in **Cortex XSIAM** (30+ alerts handled without manual review), supported phishing response and data-loss investigations with Proofpoint, built Python threat-intelligence integrations, and wrote Rego controls and Wiz queries for Azure.

## Toolkit

**Identity & access**  
![Keycloak: OIDC, SCIM, MFA](https://img.shields.io/badge/Keycloak%3A%20OIDC%2C%20SCIM%2C%20MFA-161D2A?style=flat-square&logo=keycloak&logoColor=white) ![Microsoft Entra ID and Graph](https://img.shields.io/badge/Microsoft%20Entra%20ID%20and%20Graph-161D2A?style=flat-square) ![Samba AD: LDAPS, Kerberos](https://img.shields.io/badge/Samba%20AD%3A%20LDAPS%2C%20Kerberos-161D2A?style=flat-square) ![OPA and Rego](https://img.shields.io/badge/OPA%20and%20Rego-161D2A?style=flat-square) ![Shared Signals: CAEP, RISC](https://img.shields.io/badge/Shared%20Signals%3A%20CAEP%2C%20RISC-161D2A?style=flat-square&logo=openid&logoColor=F78C40)

**Detection & response**  
![Cortex XSIAM](https://img.shields.io/badge/Cortex%20XSIAM-161D2A?style=flat-square&logo=paloaltonetworks&logoColor=F04E23) ![Wazuh SIEM](https://img.shields.io/badge/Wazuh%20SIEM-161D2A?style=flat-square) ![Sigma rules](https://img.shields.io/badge/Sigma%20rules-161D2A?style=flat-square) ![Splunk SPL](https://img.shields.io/badge/Splunk%20SPL-161D2A?style=flat-square&logo=splunk&logoColor=white) ![KQL](https://img.shields.io/badge/KQL-161D2A?style=flat-square) ![Shuffle SOAR](https://img.shields.io/badge/Shuffle%20SOAR-161D2A?style=flat-square) ![Proofpoint TRAP and DLP](https://img.shields.io/badge/Proofpoint%20TRAP%20and%20DLP-161D2A?style=flat-square) ![VirusTotal](https://img.shields.io/badge/VirusTotal-161D2A?style=flat-square&logo=virustotal&logoColor=394EFF) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-161D2A?style=flat-square&logo=zap&logoColor=00549E)

**Cloud security**  
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-161D2A?style=flat-square) ![Wiz Security Graph](https://img.shields.io/badge/Wiz%20Security%20Graph-161D2A?style=flat-square) ![Rego cloud controls](https://img.shields.io/badge/Rego%20cloud%20controls-161D2A?style=flat-square)

**Engineering**  
![Python](https://img.shields.io/badge/Python-161D2A?style=flat-square&logo=python&logoColor=3776AB) ![Django](https://img.shields.io/badge/Django-161D2A?style=flat-square&logo=django&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161D2A?style=flat-square&logo=postgresql&logoColor=4169E1) ![TypeScript](https://img.shields.io/badge/TypeScript-161D2A?style=flat-square&logo=typescript&logoColor=3178C6) ![React](https://img.shields.io/badge/React-161D2A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-161D2A?style=flat-square&logo=nextdotjs&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-161D2A?style=flat-square&logo=supabase&logoColor=3FCF8E) ![Docker](https://img.shields.io/badge/Docker-161D2A?style=flat-square&logo=docker&logoColor=2496ED)

**Delivery**  
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-161D2A?style=flat-square&logo=githubactions&logoColor=2088FF) ![CodeQL and dependency review](https://img.shields.io/badge/CodeQL%20and%20dependency%20review-161D2A?style=flat-square&logo=github&logoColor=white) ![Signed releases with SBOM](https://img.shields.io/badge/Signed%20releases%20with%20SBOM-161D2A?style=flat-square)

**Applied AI**  
![LLM agents (Claude)](https://img.shields.io/badge/LLM%20agents%20%28Claude%29-161D2A?style=flat-square&logo=claude&logoColor=D97757) ![Structured output with JSON Schema](https://img.shields.io/badge/Structured%20output%20with%20JSON%20Schema-161D2A?style=flat-square&logo=json&logoColor=white) ![Tool and environment allowlists](https://img.shields.io/badge/Tool%20and%20environment%20allowlists-161D2A?style=flat-square) ![Source provenance](https://img.shields.io/badge/Source%20provenance-161D2A?style=flat-square)
