<!--
  Design notes (17 September 2026).
  Taken from github.com/Resourcio-Community/AI-ML-Resources: categorised link tables with
  fixed columns and a link column per row; emoji-led section headings.
  Taken from github.com/Resourcio-Community/Resourcio_Community-Website: centred logo header
  with a shields.io badge row under it, section icons, a screenshot, social badges and a
  "Getting involved" style contributing section.
-->

<p align="center">
  <a href="https://www.manchesteraiguild.org/"><img src="https://avatars.githubusercontent.com/u/319570462?v=4" alt="Manchester AI Guild" width="120"></a>
</p>

<h1 align="center">Manchester AI Guild</h1>

<p align="center"><strong>Two missions:</strong> help businesses adopt AI to grow, and build Manchester's AI capability, solutions and talent.</p>

<p align="center">
  <a href="https://github.com/Manchester-AI-Guild/manchester-ai-guild/actions/workflows/security-checks.yml"><img src="https://github.com/Manchester-AI-Guild/manchester-ai-guild/actions/workflows/security-checks.yml/badge.svg" alt="Security Checks"></a>
  <a href="https://github.com/Manchester-AI-Guild/manchester-ai-guild/actions/workflows/pages.yml"><img src="https://github.com/Manchester-AI-Guild/manchester-ai-guild/actions/workflows/pages.yml/badge.svg" alt="Deploy GitHub Pages"></a>
  <a href="#"><img src="https://img.shields.io/badge/Project-Active-2563EB" alt="Project Status - Active"></a>
  <a href="http://creativecommons.org/licenses/by/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey" alt="License - CC BY 4.0"></a>
  <img src="https://img.shields.io/badge/Guild--owned-Manchester%20AI%20Guild%20Ltd-F2C230" alt="Guild-owned">
  <img src="https://img.shields.io/badge/Branch-main%20only-2563EB" alt="main only">
</p>

<p align="center">
  <a href="https://www.manchesteraiguild.org/"><img src="https://img.shields.io/badge/Website-manchesteraiguild.org-0F172A" alt="Website"></a>
  <a href="https://www.linkedin.com/company/manchester-ai-guild"><img src="https://img.shields.io/badge/LinkedIn-Manchester%20AI%20Guild-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://manchester-ai-guild.github.io/manchester-ai-guild/"><img src="https://img.shields.io/badge/Docs-GitHub%20Pages-222?logo=github" alt="Docs microsite"></a>
</p>

This is the public home of Manchester AI Guild on GitHub: the two missions, purpose statement, operating model, participants and the docs microsite. Our goal is to mutually develop a practical framework and execution model that supports the onboarding, development, governance, and scaling of AI-based solutions across Manchester-region organisations.

## Review status and asset flow

This repository is the Guild's public layer, and it is one of three: `.github` holds the organisation configuration, this repository holds public content, and `manchester-ai-guild-operations` holds private operations. It should read cleanly from top to bottom: purpose first, then operating model, then ecosystem, then the published microsite.

- Owns: the two missions, the purpose statement, public commitments, and member-facing guidance
- Does not own: internal governance records, action tracking and the canonical Code of Conduct, which live in `manchester-ai-guild-operations`; organisation defaults and the published Code of Conduct mirror, which live in `.github`
- Review gate: before a change here is merged, the public wording must still match the published microsite and the Guild charter

## What's here

| Folder or file | What it is |
|---|---|
| This README | The two missions, purpose statement, who we serve, what we offer, operating model, what members contribute, FAQ |
| [`docs/operating-model/`](docs/operating-model/README.md) | The operating model folder: purpose statement, charter draft and Code of Conduct, with the status of each |
| [`docs/operating-model.md`](docs/operating-model.md) | How Manchester AI Guild runs: funding approach, member delivery, sustainability |
| [`docs/participants-and-ecosystem.md`](docs/participants-and-ecosystem.md) | Senior Leadership Team (SLT), founding members, consenting participants and ecosystem entities |
| [`docs/security-maintenance.md`](docs/security-maintenance.md), [`SECURITY.md`](SECURITY.md) | Security maintenance notes and how to report a vulnerability |
| [`docs/index.md`](docs/index.md), [`docs/index.html`](docs/index.html) | The docs microsite, published by the Deploy GitHub Pages workflow to [manchester-ai-guild.github.io/manchester-ai-guild](https://manchester-ai-guild.github.io/manchester-ai-guild/) |
| [`CONTRIBUTING.md`](CONTRIBUTING.md), [`.github/`](.github/) | Contributing guide, issue template (`guild-task`), pull request template, CODEOWNERS |
| [`issues-seed.json`](issues-seed.json) | Seed of the action-owner issue backlog |
| [`.github/workflows/`](.github/workflows/) | Security Checks (gitleaks `secret-scan`) and Deploy GitHub Pages |

## Our two missions

**Mission 1: Help businesses adopt AI.** Help SMEs and enterprises adopt AI to drive growth, improve efficiency and solve real business problems.

**Mission 2: Build Manchester's AI capability.** Bring business, academia, government and the AI community together to build the next generation of AI capability, solutions and talent needed to support that growth.

**Build capability. Create opportunity. Grow prosperity.**

**Make Manchester a place where AI is not just talked about, it gets done.**

Manchester AI Guild brings together founders, practitioners, researchers and ecosystem partners to unlock AI value safely and at speed. We focus on practical delivery and clear governance so teams can move from discussion to implementation with confidence.

### **[Purpose statement](./docs/operating-model/purpose-statement.md)**

The Manchester AI Guild is a not-for-profit built to make AI work for good in Manchester and the UK. We grow people, strengthen solution providers and connect the Manchester ecosystem to drive lasting change through the responsible adoption of AI.

### **Who we serve**

Manchester AI Guild serves two audiences, one for each mission.

- **Mission 1: businesses adopting AI.** SMEs, partnerships and enterprise organisations that want to adopt AI to grow and solve real business problems, but lack the expertise, confidence or resources to do so safely and effectively.
- **Mission 2: Manchester's AI capability.** Community organisations, grassroots and place-based groups, charities and not-for-profits, and the people whose skills, employment and communities can benefit from the responsible and practical adoption of AI.

Our wider community, as set out in the [charter draft](./docs/operating-model/charter-draft.md), is businesses, entrepreneurs, professionals, educational institutions and community organisations in Greater Manchester and the wider North West, particularly SMEs.

Our role is not to replace existing capabilities, but to connect them. We aim to help members and partners identify where AI can create real operational value, where it should not be used, and how to implement it responsibly.

Live source: [manchesteraiguild.org](https://www.manchesteraiguild.org/).

### **What we offer**

Our primary offer is **AI workshops for SMEs and enterprise businesses on adopting AI safely**, drawing on the Manchester Way, which the Guild develops and shares alongside its professional standards.

We also offer support across the adoption journey:

- Practical support to identify valuable AI use cases for your business
- Guidance on the risk, governance and implementation trade-offs of adopting AI
- Access to trusted expertise and delivery partners for AI adoption
- Shared learning and practical AI pilots that help organisations move from experimentation to measurable outcomes
- Team engagement: building practical, responsible AI skills across teams through workshops, mentoring and events
- Organisational embedding: a supplier-neutral AI readiness assessment and business-improvement support, so AI fits real operations
- Innovation: convening business, education, technology and community partners to develop locally useful AI solutions

Live source: [manchesteraiguild.org](https://www.manchesteraiguild.org/) and the [docs microsite](https://manchester-ai-guild.github.io/manchester-ai-guild/).

### **[Operating Model](./docs/operating-model/README.md)**

Live source: [operating model](./docs/operating-model.md).

Manchester AI Guild is designed to create value for SMEs and organisations across Greater Manchester and the North West that want to adopt AI but do not yet have a clear path. We will offer practical support to help them understand the opportunity, assess real-world constraints, and implement solutions with confidence.

**Under review, not yet live.** We also recognise that members and contributors need a sustainable operating model. The Guild may, where appropriate, act as a channel for public funding, grant support or collaborative commissioning so that trusted members can deliver services to SMEs, while remaining rooted in its social mission. Members may also be shortlisted for paid engagements allocated through a skills-match workflow. None of these arrangements is live yet.

**Charter (Draft):** the purpose statement above is agreed. The [Manchester AI Guild charter, draft v0.2](./docs/operating-model/charter-draft.md), is open for working-group review and awaits Senior Leadership Team (SLT) approval. Detailed governance and structural decisions are being worked through in private before a finalised, agreed version is published here.

### **What members contribute**

Members contribute to Manchester AI Guild through these routes:

- Suggest AI Manchester events
- Join the Practitioner Program
- Join the Ambassador Program
- Help develop the Manchester AI Guild Industry Guide and Research
- Help develop the Manchester AI Guild Digital Tools

The status and detail of each route are under review. For how to contribute on GitHub, see [Getting involved](#getting-involved).

## Strategic context

Recent AI advances have created broad opportunity across products, operations, and productivity. They have also introduced new categories of risk, including hallucinations, prompt injection, compliance uncertainty, and uneven controls.  

Many organisations already have technology governance processes, but AI introduces additional complexity that often needs specific adaptation. This repository exists to make that adaptation practical.

## Current approach

- **Focus on concrete use cases**  
  We prioritize narrow, high-value slices over broad abstract frameworks.
- **Leverage existing governance**  
  We build on existing enterprise and SME controls wherever possible.
- **Threat-model-informed controls**  
  We identify practical mitigations and implementation patterns for real architectures.
- **Community-first iteration**  
  We refine outputs through live working sessions and measurable pilot outcomes.

## What this repository contains

- Charter and mission narrative
- Working group definitions
- Delivery roadmap and milestones
- Action-owner issue backlog
- Participant and ecosystem roster

## Participants and ecosystem

See [participants-and-ecosystem.md](./docs/participants-and-ecosystem.md) for the full list of attendees, contributors, and meetup/ecosystem entities.

## Senior Leadership Team (SLT)

The Manchester AI Guild Senior Leadership Team (SLT) was proposed at the 28 August meeting and reviewed again at the 4 September SLT meeting. Founding members and consenting participants are listed in [participants-and-ecosystem.md](./docs/participants-and-ecosystem.md).

| Name | SLT Role |
|---|---|
| Adrian Quayle | President |
| Mihran Hovnanian | Chairman & Secretary |
| Edwin Luther | Risk & Governance Director; owner of this repository |
| Simon Ellis | Engagement & Projects Lead |
| Fernando Torres | Events & Marketing Director |
| Rufus Curnow | Communications Director |
| Marek Kurczynski | Website & Platform |
| Trevor Roberts | Data Protection Lead |
| Tom Parson | Events & Community Partnerships |
| Donald McIntosh | Treasurer & CFO |
| Phil Davies | Operations Director |

## Policies

Draft Guild policies (privacy notice, responsible AI use and others) are kept in the website repository's policy register: [`docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only). Their status is **Draft, awaiting SLT 10 Oct 2026**. The canonical Code of Conduct is [`policies/public/code-of-conduct.md`](https://github.com/Manchester-AI-Guild/manchester-ai-guild-operations/blob/main/policies/public/code-of-conduct.md) in the operations repository; the copy in [`.github`](https://github.com/Manchester-AI-Guild/.github/blob/main/CODE_OF_CONDUCT.md) is the published mirror. A working draft (v2.8, 12 October 2026) is kept in this repository at [`docs/operating-model/code-of-conduct.md`](./docs/operating-model/code-of-conduct.md) pending SLT sign-off.

Manchester AI Guild Ltd is registered with the Information Commissioner's Office as a data controller (registration ZC266348).

## Getting involved

1. Review open issues and milestones.
2. Join the appropriate workstream label.
3. Contribute practical artefacts (templates, controls, checklists, implementation examples).
4. Participate in session cadence and action reviews.

### How to contribute

- **Contribute work**: read [`CONTRIBUTING.md`](CONTRIBUTING.md), then open a pull request against `main`. The `secret-scan` check must pass before merge.
- **Raise a task or idea**: open an issue using the `guild-task` template.
- **Report a security problem**: follow [`SECURITY.md`](SECURITY.md); do not open a public issue.
- **Ask for help**: contact Manchester AI Guild via [www.manchesteraiguild.org](https://www.manchesteraiguild.org/) or [LinkedIn](https://www.linkedin.com/company/manchester-ai-guild).

## Connect

- Website: [www.manchesteraiguild.org](https://www.manchesteraiguild.org/)
- LinkedIn: [Manchester AI Guild](https://www.linkedin.com/company/manchester-ai-guild)

## Repository

- Purpose: the Manchester AI Guild public home on GitHub: mission, purpose statement, operating model, participants and the docs microsite (`docs/`, published by the Deploy GitHub Pages workflow).
- Owner: Edwin Luther, Risk & Governance Director
- Policies index: [website `docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only)
- Only `main` exists; changes go through pull requests and the `secret-scan` check.

## FAQ

### Are you building foundation models?
No. Manchester AI Guild is focused on practical adoption, governance, and implementation pathways.

### Is this only for Generative AI?
No. Generative AI is a major focus area, but governance and delivery patterns are applicable across broader AI systems.

### Is this only for large enterprises?
No. A core focus is enabling SMEs and startups with practical, right-sized governance and implementation support.
