---
title: Product Backlog
---

[Overview](index.html) · [Team Charter](team-charter.html) · [User Stories & Tasks](user-stories-and-tasks.html) · [Product Backlog](product-backlog.html) · [Sprint Backlog](sprint-backlog.html) · [Agile Logbook](logbook.html) · [Main portfolio](../)

---

# Product Backlog

*CareerCraft | Items in delivery order*

The product backlog lists every story the team worked on, in the order they were pulled into the plan: discovery and validation first, then the business case and pitch, then design, then the working product.

## Evidence

### Delivered backlog items

| ID | Backlog item | Period | Outcomes recorded on the taskboard |
|---|---|---|---|
| PB-01 | **Initiation Week 1**: Project kickoff and problem discovery | 1–5 June 2026 | • The team aligned around a student-first career platform rather than a collection of disconnected tools. |
| PB-02 | **Initiation Week 2**: User needs and value proposition | 8–12 June 2026 | • User needs supported a guided, reusable career profile that could feed multiple professional outputs. |
| PB-03 | **Initiation Week 3**: Business model and technical feasibility | 15–19 June 2026 | • The team confirmed that a staged web MVP was feasible if data reuse and scope control were treated as core architecture decisions. |
| PB-04 | **Initiation Week 4**: Agile setup and sprint readiness | 22–26 June 2026 | • The project entered delivery with assigned roles, a prioritised backlog and agreed Agile ceremonies. |
| PB-05 | **Sprint 1**: Establish a shared understanding of the student career-readiness problem and define the first testable CareerCraft product direction. | 30 June–3 July 2026 | • Problem statement and target-user definition<br>• Initial feature map<br>• Team working agreement and prioritised discovery backlog |
| PB-06 | **Sprint 2**: Convert the validated concept into a defensible business and marketing proposition and prepare an investor-style presentation. | 7–10 July 2026 | • Draft Business and Marketing Plan<br>• Draft investor-style pitch deck<br>• Market and competitor evidence notes<br>• Pitch rehearsal schedule |
| PB-07 | **Sprint 3**: Finalise and deliver the investor-style pitch, then strengthen Deliverable 2 with verified market and competitor evidence. | 14–17 July 2026 | • Final 16-slide pitch deck<br>• Deliverable 2 submission<br>• Investor-style pitch delivered on 15 July<br>• Research notes on market data and competitor platforms<br>• Pitch retrospective |
| PB-08 | **Sprint 4**: Translate lecturer feedback into a prioritised, owned and implementation-ready Product Backlog. | 21–24 July 2026 | • Refined Product Backlog<br>• Updated priorities and statuses<br>• Assigned task ownership<br>• Implementation-ready design backlog |
| PB-09 | **Sprint 5**: Design the core CareerCraft experience in Figma, obtain lecturer feedback and revise the interface toward a brighter, accessible visual system. | 28–31 July 2026 | • Low-fidelity wireframes for core screens<br>• Interactive Figma prototype<br>• Bright revised colour palette<br>• Colour-contrast reference guide<br>• Updated prototyping backlog |
| PB-10 | **Sprint 6**: Demonstrate the website prototype and implement the lecturer feedback on branding, pricing access, visual tone and functional links. | 4–7 August 2026 | • First class showcase of the website prototype<br>• Bright colour system applied<br>• CareerCraft logo<br>• Free Tier subscription option<br>• Brand Guideline<br>• Functional GitHub repository links |
| PB-11 | **Sprint 7**: Turn the approved visual direction into reusable implementation rules and close the remaining mobile and accessibility gaps. | 11–14 August 2026 | • Implementation-ready brand guide<br>• Responsive-layout issue list<br>• Reusable style-token specification<br>• Mobile sign-up verification notes |
| PB-12 | **Sprint 8**: Create the multi-page front-end foundation and make the core CareerCraft journeys reachable through consistent navigation. | 18–21 August 2026 | • Branded landing page<br>• Core HTML page set<br>• Consistent navigation and CTAs<br>• Responsive smoke-test checklist |
| PB-13 | **Sprint 9**: Enable account creation and establish the user-owned career profile that will feed CVs, portfolios and AI tools. | 25–28 August 2026 | • Authentication flow<br>• Career-profile form<br>• Session-aware navigation<br>• Initial backend profile mapping<br>• Authentication test cases |
| PB-14 | **Sprint 10**: Allow users to create or update a CV using modular sections and select an appropriate layout. | 1–4 September 2026 | • My CV editor<br>• Modular resume sections<br>• Live preview<br>• Template selector<br>• Draft validation checklist |
| PB-15 | **Sprint 11**: Connect the CV editor to Supabase so authenticated users can save, retrieve and continue editing their documents. | 7–11 September 2026 | • CV persistence functions<br>• Saved-CV profile listing<br>• Resume ownership controls<br>• Visible save-state feedback<br>• Persistence test evidence |
| PB-16 | **Sprint 12**: Deliver usable LinkedIn Profile Makeover and Post Generator journeys while stabilising serverless deployment and environment configuration. | 14–18 September 2026 | • LinkedIn Profile Makeover prototype<br>• LinkedIn Post Generator prototype<br>• Consent language<br>• Serverless AI endpoint<br>• Hosted configuration checklist |
| PB-17 | **Sprint 13**: Improve AI reliability by standardising the provider adapter, validating configuration and making failures diagnosable without exposing secrets. | 21–25 September 2026 | • Gemini-backed AI adapter<br>• Provider response parser<br>• Structured function logs<br>• User-safe error messages<br>• AI regression test matrix |
| PB-18 | **Sprint 14**: Connect plan access to product tools, allow GitHub portfolio projects to appear in the selected CV and prepare the package-payment journey for controlled testing. | 28–30 September 2026 | • Portfolio project selector<br>• Selected projects rendered in the CV<br>• Plan entitlement matrix<br>• Locked-tool interface states<br>• Payment-ready checkout and verification design |

### Open and deferred items

| Item | Status | Source |
|---|---|---|
| Map selected projects into the resume preview and saved CV data | In progress at the end of Sprint 14 | Sprint 14 taskboard |
| Define Free, Starter and Pro entitlements and visible lock states | In progress at the end of Sprint 14 | Sprint 14 taskboard |
| Native Android and iOS applications | Deferred beyond the project | Team charter |
| Guaranteed placement or automated job applications | Deferred beyond the project | Team charter |
| Full recruiter marketplace | Deferred beyond the project | Team charter |
| Institution analytics before a validated pilot | Deferred beyond the project | Team charter |
| Pilot readiness: pilot plan, consent language and feedback instrument (milestone M5) | Planned | Team charter |

## Reflection

*[DRAFT: edit in your own words]* The backlog shows the product being built in a deliberate order: understand the problem, validate the business model, design the experience, then build authentication, the profile, the CV editor, persistence, AI tools and subscriptions. Each item depends on the one before it, so the ordering mattered more than I expected.

The earliest retrospective said the initial concept was too broad, and the backlog is where we acted on that. We narrowed the first release to a reusable career profile and a guided CV workflow and recorded everything else as deferred in the charter. That discipline kept later sprints focused, although the open items at the end of Sprint 14 show how much remained.

*[Add what you would change, for example: add estimates and explicit priority labels such as MoSCoW to each item so the order is justified, not just recorded.]*
