<a href="https://aman-agarwal6.github.io/"><img src="assets/banner.png" alt="Aman Agarwal: identity security, security operations and applied AI. Iowa State MIS, CompTIA Security+, former HNI cybersecurity intern. Open to entry-level security roles from January 2027." width="100%"></a>

I build identity and detection controls, test them against real systems, and publish what failed alongside what passed. MIS senior at Iowa State with a Cybersecurity Engineering minor, graduating December 2026; CompTIA Security+; former cybersecurity intern at HNI. **Open to entry-level security roles from January 2027.**

**[Portfolio](https://aman-agarwal6.github.io/)** · [Recruiter summary](https://aman-agarwal6.github.io/overview.html) · [LinkedIn](https://www.linkedin.com/in/aman-agarwal6/) · [Email](mailto:aagarwalcollege@gmail.com)

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://aman-agarwal6.github.io/projects/accessops.html"><img src="assets/accessops.png" alt="AccessOps public demo with synthetic data: a departure case, its next step and the evidence source of each required action"></a>

### [AccessOps](https://aman-agarwal6.github.io/projects/accessops.html)

**Disabled isn't done.** Leaver automation that proves access ended: a signed HR event ends a departing employee's access across Keycloak, Microsoft Entra ID and an AD-compatible directory, and each system is read back before the case can close on independent review.

- **2.6 s** from a signed HR event to sessions ended and tokens refused
- **6** gaps disabling left open, found by live runs and closed or stated
- **20 s** for Microsoft Graph to confirm Entra containment in a test tenant

[Case study](https://aman-agarwal6.github.io/projects/accessops.html) · [Live demo](https://aman-agarwal6.github.io/AccessOps/) · [Source](https://github.com/aman-agarwal6/AccessOps)

</td>
<td width="50%" valign="top">

<a href="https://aman-agarwal6.github.io/projects/signalbridge.html"><img src="assets/signalbridge.png" alt="SignalBridge evidence viewer: recorded Wazuh runs from an isolated local lab with synthetic data"></a>

### [SignalBridge](https://aman-agarwal6.github.io/projects/signalbridge.html)

**Catch the access that should have ended.** A detection lab that ties each permission change to what an account could actually read. Five versioned detection rules, also written as Sigma, feed an analyst console that takes a finding to an independently verified fix.

- **8/8** Wazuh alerts raised exactly once, with nothing lost after a collector stop
- **14/14** PostgreSQL race and crash-recovery checks, including a killed worker
- **48**-scenario detection evaluation that keeps its misses and false alerts

[Case study](https://aman-agarwal6.github.io/projects/signalbridge.html) · [Source](https://github.com/aman-agarwal6/signalbridge)

</td>
</tr>
</table>

The two work as a pair: AccessOps signs an event for each offboarding step, and SignalBridge verifies those events and opens a critical case if a departed account is used anyway.

## More projects

| Project | What it is | Highlight |
| --- | --- | --- |
| [BetTail](https://aman-agarwal6.github.io/projects/bettail.html) | Live web app where private groups share sports picks and track results | Row-level security on every exposed table, no service-role key; 1,002 unit and database tests |
| [Netted](https://aman-agarwal6.github.io/projects/netted.html) | Personal-finance beta for realized profit, pooled funds and budgeting | MFA enforced in the database; 506/506 journal records restored in a recovery drill |
| [Downfield](https://aman-agarwal6.github.io/projects/downfield.html) | Local LLM research worker that writes structured NFL reports | Allowlisted tools and environment; every report validated and versioned |
| [Sailday](https://aman-agarwal6.github.io/projects/sailday.html) | Installable cruise planner with price tracking | Hourly public-rate collection, opt-in Web Push alerts, offline sync |

BetTail, Netted, Downfield and Sailday stay private; their case studies link [selected source excerpts and tests](https://github.com/aman-agarwal6/aman-agarwal6.github.io/blob/main/docs/PROJECTS.md).

## Experience

**Cybersecurity Intern, HNI Corporation** · May–July 2026  
Automated triage for 3 identity-alert types in **Cortex XSIAM** (30+ alerts handled without manual review), supported phishing response and data-loss investigations with Proofpoint, built Python threat-intelligence integrations, and wrote Rego controls and Wiz queries for Azure.

## Toolkit

**Identity & access:** Keycloak (OIDC, SCIM, MFA) · Microsoft Entra ID and Graph · Samba AD (LDAPS, Kerberos) · OPA and Rego · Shared Signals (CAEP, RISC)  
**Detection & response:** Cortex XSIAM · Wazuh · Sigma · Shuffle SOAR · Proofpoint TRAP and DLP · OWASP ZAP  
**Engineering:** Python · Django · PostgreSQL · TypeScript · React · Next.js · Supabase · Docker · GitHub Actions  
**Applied AI:** LLM research workflows · tool and environment allowlists · JSON Schema validation · AI coding agents

<details>
<summary>How I build</summary>

I build with AI coding agents under my direction. I set the requirements and threat model, decide what to measure, and review each finding and fix. Each case study states my role, its recorded checks and what they don't prove; assessments are my own, not independent reviews.

</details>
