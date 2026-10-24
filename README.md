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

This is the Guild's public home on GitHub: the two missions, purpose statement, operating model, participants and the docs microsite. Our goal is to mutually develop a practical framework and execution model that supports the onboarding, development, governance, and scaling of AI-based solutions across Manchester-region organisations.

Tip: Ctrl-click (Cmd-click on Mac) a link to open it in a new tab.

## Review status and asset flow

This repository is the Guild's public layer, and it is one of five repositories: `.github` (public) holds the organisation configuration, this repository (public) holds public content, `manchester-ai-guild-operations` (private) holds private operations, `website` (private) is the source of www.manchesteraiguild.org and the draft policy register, and `manchester-ai-guild-assets` (private) holds official brand assets. It should read cleanly from top to bottom: purpose first, then operating model, then ecosystem, then the published microsite.

- Owns: the two missions, the purpose statement, public commitments, and member-facing guidance
- Does not own: internal governance records, action tracking and the canonical Code of Conduct, which live in `manchester-ai-guild-operations`; organisation defaults and the published Code of Conduct mirror, which live in `.github`
- Review gate: before a change here is merged, the public wording must still match the published microsite and the Guild charter

## What's here

| Folder or file | What it is |
|---|---|
| This README | The two missions, purpose statement, who we serve, what we offer, charter direction, FAQ |
| [`docs/operating-model.md`](docs/operating-model.md) | How the Guild runs: working groups, cadence, ownership |
| [`docs/participants-and-ecosystem.md`](docs/participants-and-ecosystem.md) | Guild Senior Leadership Team (SLT), founding members, consenting participants and ecosystem entities |
| [`docs/security-maintenance.md`](docs/security-maintenance.md), [`SECURITY.md`](SECURITY.md) | Security maintenance notes and how to report a vulnerability |
| [`docs/index.md`](docs/index.md) · [View](https://manchester-ai-guild.github.io/manchester-ai-guild/) · [Source](docs/index.html) | The docs microsite, published by the Deploy GitHub Pages workflow to [manchester-ai-guild.github.io/manchester-ai-guild](https://manchester-ai-guild.github.io/manchester-ai-guild/) |
| [`CONTRIBUTING.md`](CONTRIBUTING.md), [`.github/`](.github/) | Contributing guide, issue template (`guild-task`), pull request template, CODEOWNERS |
| [`issues-seed.json`](issues-seed.json) | Seed of the action-owner issue backlog |
| [`.github/workflows/`](.github/workflows/) | Security Checks (gitleaks `secret-scan`) and Deploy GitHub Pages |

## Our two missions

**Mission 1: Help businesses adopt AI.** Help SMEs and enterprises adopt AI to drive growth, improve efficiency and solve real business problems.

**Mission 2: Build Manchester's AI capability.** Bring business, academia, government and the AI community together to build the next generation of AI capability, solutions and talent needed to support that growth.

**Build capability. Create opportunity. Grow prosperity.**

**Make Manchester a place where AI is not just talked about, it gets done.**

The Guild brings together founders, practitioners, researchers and ecosystem partners to unlock AI value safely and at speed. We focus on practical delivery and clear governance so teams can move from discussion to implementation with confidence.

### **Purpose statement**

Agreed by the Guild Senior Leadership Team (SLT) on 11 September 2026. Live source: the Guild's [LinkedIn page](https://www.linkedin.com/company/manchester-ai-guild) and [manchesteraiguild.org](https://www.manchesteraiguild.org/).

The Manchester AI Guild is a not-for-profit built to make AI work for good in Manchester and the UK. We grow people, strengthen solution providers and connect the Manchester ecosystem to drive lasting change through the ethical use of AI.

### **Who we serve**

Live source: [manchesteraiguild.org](https://www.manchesteraiguild.org/).

We support SMEs, founders, public-sector teams and regional partners that want to adopt AI but lack the expertise, confidence or resources to do so safely and effectively. We create a trusted space for practical collaboration: identifying valuable use cases, understanding the risk and governance implications, connecting people to the right expertise, and helping organisations move from experimentation to measurable outcomes.

Our role is not to replace existing capabilities, but to connect them. We aim to help members and partners identify where AI can create real operational value, where it should not be used, and how to implement it responsibly.

### **What we offer**

Live source: [manchesteraiguild.org](https://www.manchesteraiguild.org/) and the [docs microsite](https://manchester-ai-guild.github.io/manchester-ai-guild/).

- Practical support to identify valuable AI use cases
- Guidance on risk, governance, and implementation trade-offs
- Access to trusted expertise and delivery partners
- A route to shared learning, better decisions, and practical pilot delivery
- A sustainable operating model that connects social value with real delivery capacity

### **Charter direction**

Live source: [operating model](./docs/operating-model.md).

The Guild is designed to create value for SMEs and organisations across Greater Manchester and the North West that want to adopt AI but do not yet have a clear path. We will offer practical support to help them understand the opportunity, assess real-world constraints, and implement solutions with confidence.

We also recognise that members and contributors need a sustainable operating model. Where appropriate, the Guild may act as a channel for public funding, grant support, or collaborative commissioning so that trusted members can deliver services to SMEs while the Guild remains rooted in its social mission.

**Charter status:** the purpose statement above is agreed. The Guild charter is still being drafted by the working group, building on it. Detailed governance and structural decisions are being worked through in private before a finalised, agreed version is published here.

## The Manchester Way

The Manchester Way is the Manchester AI Guild's method for SMEs. It uses a band as the picture of a business. The core band is your product, your specialist expertise, your data, your systems, your commercial backing, your customers and their feedback. Each role comes with one plain question. The aim is the AI Supernova: the intent to amplify what makes your business exceptional through ethical, sustainable and human-centred AI. Keep what makes you distinctive, find where the performance goes wrong, and test one small change.

The core band, in order:

1. **Lead singer / songwriter**: the product or service and its distinctive voice. *What makes your offering yours?*
2. **Lead guitarist**: specialist expertise, craft and innovation. *Which capabilities make you exceptional?*
3. **Bass guitarist**: data. *Is your data reliable, accessible and understood?*
4. **Sound engineer**: systems integration, quality and delivery. *Does the right information reach the right people?*
5. **Record label**: commercial backing, investment and business model. *How do you fund and support your offering?*
6. **Audience**: customers and users. *Who are you performing for?*
7. **Reviews, applause and repeat bookings**: customer insight and measured results. *How do you hear the response?*

**AI Supernova** is the intent to amplify what makes your business exceptional through ethical, sustainable and human-centred AI. It has positive cultural and financial impact: it pays back in people and in profit.

The microsite's [Manchester Way section](https://manchester-ai-guild.github.io/manchester-ai-guild/#programmes) sets out the method in full.

## Services

- **SME Workshops**: The Manchester Way workshop, an afternoon (13:00 to 17:15) for SMEs with three exercises: the false notes, start your band, and improve one performance. Proposed dates: 18 November and 10 December 2026, at Ada, National College for Digital Skills. A one-company workshop runs the same method for a single organisation, in more depth.
- **AI Consultancy**: help after the workshop, including setting up AI policies and working with a company's IT team, whose job is to keep data safe. The Guild's consultancy acts as an external critical friend, at the right time.

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

The Guild Senior Leadership Team (SLT) was proposed at the 28 August meeting and reviewed again at the 4 September SLT meeting. Founding members and consenting participants are listed in [participants-and-ecosystem.md](./docs/participants-and-ecosystem.md).

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

Draft Guild policies (privacy notice, responsible AI use and others) are kept in the website repository's policy register: [`docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only). Their status is **Draft, under SLT review**. The canonical Code of Conduct is [`policies/public/code-of-conduct.md`](https://github.com/Manchester-AI-Guild/manchester-ai-guild-operations/blob/main/policies/public/code-of-conduct.md) in the operations repository; the copy in [`.github`](https://github.com/Manchester-AI-Guild/.github/blob/main/CODE_OF_CONDUCT.md) is the published mirror.

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
- **Ask for help**: contact the Guild via [www.manchesteraiguild.org](https://www.manchesteraiguild.org/) or [LinkedIn](https://www.linkedin.com/company/manchester-ai-guild).

## Connect

- Website: [www.manchesteraiguild.org](https://www.manchesteraiguild.org/)
- LinkedIn: [Manchester AI Guild](https://www.linkedin.com/company/manchester-ai-guild)

## Repository

- Purpose: the Guild's public home on GitHub: mission, purpose statement, operating model, participants and the docs microsite (`docs/`, published by the Deploy GitHub Pages workflow).
- Owner: Edwin Luther, Risk & Governance Director
- Policies index: [website `docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only)
- Only `main` exists; changes go through pull requests and the `secret-scan` check.

## FAQ

### Are you building foundation models?
No. The Guild is focused on practical adoption, governance, and implementation pathways.

### Is this only for Generative AI?
No. Generative AI is a major focus area, but governance and delivery patterns are applicable across broader AI systems.

### Is this only for large enterprises?
No. A core focus is enabling SMEs and startups with practical, right-sized governance and implementation support.
