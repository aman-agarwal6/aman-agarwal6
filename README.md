# Aman Agarwal

**Security operations · Security engineering · Applied AI**

MIS senior at Iowa State University, with a Cybersecurity Engineering minor and CompTIA Security+. Graduating **December 2026** and available for junior roles in **January 2027**.

[Explore my portfolio](https://aman-agarwal6.github.io/) · [Recruiter summary](https://aman-agarwal6.github.io/overview.html) · [LinkedIn](https://www.linkedin.com/in/aman-agarwal6/) · [Email](mailto:aagarwalcollege@gmail.com)

## Experience

At **HNI Corporation**, my cybersecurity internship covered identity-alert automation in **Cortex XSIAM**, phishing and DLP triage in Proofpoint, Python threat-intelligence integrations, and Rego/Wiz controls for Azure.

## Selected projects

My two security projects connect. AccessOps offboards a departing employee and signs an event for each step; SignalBridge verifies those events and opens a case if the person's account is used anyway.

| Project | What it does | Development and supporting work |
| --- | --- | --- |
| **[AccessOps](https://aman-agarwal6.github.io/projects/accessops.html)** | Employee and contractor offboarding: each HR departure becomes a case with an owner, a deadline and a required action for every system, including the automated agents the person sponsors. It closes only on independent review. | A signed HR event contains access, ends sessions and gets the person's tokens refused in 2.6 s; operator MFA, a live signing-key rotation drill and Kerberos limits are measured against real Keycloak and Samba. Signed v0.3.0 release (372 CI cases). [Live demo](https://aman-agarwal6.github.io/AccessOps/) · [Public source](https://github.com/aman-agarwal6/AccessOps). |
| **[SignalBridge](https://aman-agarwal6.github.io/projects/signalbridge.html)** | Access-assurance and detection lab: signed telemetry, five versioned rules and an analyst console that takes a finding to an independently verified fix. | Live runs against Keycloak (password and TOTP), Wazuh (8/8 alerts raised exactly once), OWASP ZAP, Shuffle and PostgreSQL (14/14 concurrency and crash-recovery checks), and a 48-scenario evaluation that keeps its misses. [Public source](https://github.com/aman-agarwal6/signalbridge). |
| **[BetTail](https://aman-agarwal6.github.io/projects/bettail.html)** | Deployed app for private groups to share and track sports picks. | AI-assisted full-stack development: shared feeds, ticket workflows and statistics. I also reviewed application security, including database access controls and private realtime updates. Private source. |
| **[Netted](https://aman-agarwal6.github.io/projects/netted.html)** | Personal-finance beta for realized profit, shared-fund accounting and budgeting. | Accounting requirements, exact money calculations, fund allocations and audited corrections. I also completed security and recovery reviews; full-service recovery remains open. Private source. |
| **[Downfield](https://aman-agarwal6.github.io/projects/downfield.html)** | Local AI research app with structured, versioned football reports. | Restricted research tools, retained source evidence, deterministic validators and limited report publishing. In development; model probabilities are uncalibrated. |

[Project documentation and public evidence](https://github.com/aman-agarwal6/aman-agarwal6.github.io/blob/main/docs/PROJECTS.md) — source excerpts and recorded checks for the security and AI work.

Interested in junior security analyst, SOC, threat intelligence, security engineering, AI security and applied AI roles.

<details>
<summary>Implementation and evidence</summary>

AI coding agents wrote substantial portions of the project code and documentation under my direction. I set requirements, directed security reviews and chose what to change. The case studies describe my role, recorded checks and open work. Assessments are builder-led, not independent reviews.

</details>
