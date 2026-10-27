---
title: Agile Team Charter
---

[Overview](index.html) · [Team Charter](team-charter.html) · [User Stories & Tasks](user-stories-and-tasks.html) · [Product Backlog](product-backlog.html) · [Sprint Backlog](sprint-backlog.html) · [Agile Logbook](logbook.html) · [Main portfolio](../)

---

# Agile Team Charter

*CareerCraft | Version 1.0 | Approved 4 May 2026*

The full signed charter is available as a PDF: [CareerCraft_Agile_Team_Charter.pdf](evidence/CareerCraft_Agile_Team_Charter.pdf). Key content is summarised below. Version 1.0 was approved by all four members on 4 May 2026.

## Evidence

### 1. Team purpose

**Objective.** Design, develop and validate a South Africa-first digital career platform that helps students and graduates maintain one credible career profile and turn it into consistent CVs, portfolios, LinkedIn content and application documents.

**Vision.** Give every student and graduate a guided, accessible workspace for presenting verified skills and experience with confidence.

**Definition of success**

- A user can register, sign in and maintain a reusable career profile.
- A user can create, edit, save and retrieve a modular CV.
- At least two resume layouts are available to Free users, with other access rules clearly explained.
- A user can select GitHub projects and include them in a portfolio or CV.
- AI-assisted tools return editable results, communicate failures clearly and do not invent achievements.
- The core journey works on mobile and desktop and protects secrets through environment configuration.

### 2. Roles and responsibilities

| Team member | Primary role | Core responsibilities |
|---|---|---|
| Lwandile Mangali | Product Owner and Project Manager | Owns product vision and backlog, prioritises user value, coordinates sprints, approves increments, manages stakeholders and risks. |
| Sello Makhunyane | Lead Developer and Technical Coordinator | Guides technical implementation, integrates front-end and back-end work, reviews code, supports deployment, security and defect resolution. |
| Livhuwani Madavha (me) | UX/UI Designer and Front-end Developer | Maps user journeys, creates accessible interfaces, keeps visual consistency, builds responsive components and usability improvements. |
| Lerato Motsweni | Business Analyst and Quality Assurance Lead | Refines requirements and acceptance criteria, maintains traceability, coordinates testing, documents defects and review outcomes. |

### 3. Values and working agreements

Our values are collaboration, respect, transparency, user value, quality and learning. Key working agreements:

- Acknowledge a direct project message within 24 hours on working days.
- Record major scope or architecture decisions and consult the relevant role owner.
- Use descriptive commits and review code before treating it as complete.
- Escalate blockers lasting longer than one working day to the Product Owner.
- Resolve disagreements using user evidence, acceptance criteria and project constraints rather than hierarchy alone.

### 4. Communication plan

| Interaction | Method | Frequency | Owner |
|---|---|---|---|
| Sprint planning | In person or Microsoft Teams | Start of each sprint | Product Owner |
| Team check-in | WhatsApp or Teams call | Twice weekly | Project Manager |
| Development coordination | GitHub and short call | As required | Lead Developer |
| Backlog refinement | Shared document and meeting | Weekly | Product Owner and Business Analyst |
| Sprint review | Live demonstration | End of each sprint | Whole team |
| Retrospective | Facilitated discussion | After each sprint review | QA Lead |

### 5. SMART goals

| Goal | Measure | Target | Owner |
|---|---|---|---|
| Reliable authenticated profile and CV saving workflow | A new and existing CV can be created, saved, reopened and edited without silent errors | Sprint 1 | Lwandile and Sello |
| Usable resume layout choice | At least two Free layouts work and the choice persists with the CV | Sprint 1 | Livhuwani and Sello |
| Connect portfolio evidence to the CV | A user can select GitHub projects and see them in the CV | Sprint 2 | Sello and Lerato |
| Stabilise AI-assisted career tools | Text-only and supported image requests return editable output or a clear error | Sprint 2 | Sello and Lerato |
| Validate the end-to-end student journey | Mobile, desktop, keyboard and critical-path tests with documented results | Sprint 3 | Livhuwani and Lerato |
| Prepare an institution-ready pilot package | Pilot scope, consent approach, feedback method and demonstration approved | Sprint 3 | Lwandile and team |

### 6. Definition of Ready and Done

**Ready:** clear user value, testable acceptance criteria, known dependencies, small enough for the sprint, understood estimate and owner.

**Done:** acceptance criteria pass and the main error path is tested, works at mobile and desktop widths, no credentials committed, documentation and backlog updated, and the increment reviewed by another member.

### 7. Priority risks

| Risk | Impact | Response | Owner |
|---|---|---|---|
| CV or profile data does not persist | High | Test create/read/update paths, expose database errors, validate access policies | Sello |
| AI provider fails, hits a limit or returns invalid output | High | Validate responses, give clear errors, keep provider logic server-side | Sello and Lerato |
| User information or credentials are exposed | High | Environment variables, least privilege, secure policies, secret scanning | Whole team |
| Scope growth delays the core workflow | Medium | Protect the sprint goal and defer low-value work in backlog refinement | Lwandile |
| Interface is hard to use on mobile or by keyboard | Medium | Apply responsive standards and complete accessibility checks before release | Livhuwani and Lerato |
| Uneven workload or missed communication | Medium | Review capacity, reassign early, escalate blockers after one working day | Whole team |

### 8. Approval

Approved by Lwandile Mangali, Sello Makhunyane, Livhuwani Madavha and Lerato Motsweni on 4 May 2026 (version 1.0). See the PDF for the signed record.

## Reflection

*[DRAFT: edit in your own words]* The charter turned a project idea into a working contract. It told each of us what we owned, how we would communicate and what "done" meant before any building started. My role as UX/UI Designer and Front-end Developer meant I owned the user experience and the responsive interface, and the charter made me co-owner of the layout-choice goal and the end-to-end journey validation.

The charter proved useful because it was tested by what happened later. Our first logbook retrospective noted that the initial concept was too broad, and the charter's scope boundaries and deferred list (native apps, recruiter marketplace, institution analytics) gave us a basis for cutting scope. Its risk table also predicted problems we later hit, such as AI provider failures and credential exposure, and the Definition of Done pushed us to test error paths and mobile widths rather than only the happy path.

*[Add one honest point about what you would change, for example: the charter should have set sprint dates and estimates more precisely, or been revisited after the first retrospective, as it allows.]*
