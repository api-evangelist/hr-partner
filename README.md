# HR Partner

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

HR Partner is a cloud-based human resources management SaaS platform from HR Partner Software Pty Ltd (Australia), aimed at organizations of roughly 20 to 500 employees. The platform covers employee records, recruitment and applicant tracking, onboarding and training checklists, leave requests and accruals, an employee self-service portal, performance reviews and goals, electronic signatures, expense claims, timesheets, document library, organizational chart, company calendar, and HR reports. HR Partner exposes a single public REST API at api.hrpartner.io, authenticated via per-account API key (x-api-key header), with rate limits of 60 requests/second and a 900 requests-per-minute burst ceiling. The API is read-mostly with selected write endpoints for employees, applicants, applications, timesheets, and reminders, and is described as being in an early release phase.

**Areas:** Human Resources · HRIS · Employee Records · Leave Management · Recruiting · Applicant Tracking · Onboarding · Performance Management · Timesheets · Expense Management · Document Library · E-Signature

## HR Partner on APIs.io

Everything profiled for HR Partner is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hr-partner/](https://apis.io/providers/hr-partner/)** — or go straight to one of the APIs or properties below.

### APIs (31)

- [HR Partner Absences API](https://apis.io/apis/hr-partner/hr-partner-absences-api/) — Read employee absence records.
- [HR Partner Addresses API](https://apis.io/apis/hr-partner/hr-partner-addresses-api/) — List employee address records.
- [HR Partner Applicants API](https://apis.io/apis/hr-partner/hr-partner-applicants-api/) — Read, create, and update job applicants.
- [HR Partner Application Stage Tracking API](https://apis.io/apis/hr-partner/hr-partner-application-stage-tracking-api/) — Read application stage history and tracking data.
- [HR Partner Applications API](https://apis.io/apis/hr-partner/hr-partner-applications-api/) — Read, create, and update job applications and stage data.
- [HR Partner Assets API](https://apis.io/apis/hr-partner/hr-partner-assets-api/) — Read company assets issued to employees.
- [HR Partner Attachments API](https://apis.io/apis/hr-partner/hr-partner-attachments-api/) — Read attachments stored against any HR Partner module.
- [HR Partner Benefits API](https://apis.io/apis/hr-partner/hr-partner-benefits-api/) — Read employee benefit assignments.
- [HR Partner Checklists API](https://apis.io/apis/hr-partner/hr-partner-checklists-api/) — Read onboarding and offboarding checklists.
- [HR Partner Company API](https://apis.io/apis/hr-partner/hr-partner-company-api/) — Retrieve company-level information for the HR Partner account.
- [HR Partner Contacts API](https://apis.io/apis/hr-partner/hr-partner-contacts-api/) — List employee contact details (phone, email, emergency).
- [HR Partner Dependents API](https://apis.io/apis/hr-partner/hr-partner-dependents-api/) — Read employee dependent records.
- [HR Partner Education API](https://apis.io/apis/hr-partner/hr-partner-education-api/) — Read employee education and qualification records.
- [HR Partner Employees API](https://apis.io/apis/hr-partner/hr-partner-employees-api/) — Read, create, and update employee records.
- [HR Partner Expenses API](https://apis.io/apis/hr-partner/hr-partner-expenses-api/) — Read employee expense claims.
- [HR Partner Goals API](https://apis.io/apis/hr-partner/hr-partner-goals-api/) — Read performance and development goals.
- [HR Partner Grievances API](https://apis.io/apis/hr-partner/hr-partner-grievances-api/) — Read employee grievance records.
- [HR Partner Job Listings API](https://apis.io/apis/hr-partner/hr-partner-job-listings-api/) — Read open job listings published by the organization.
- [HR Partner Leave Balances API](https://apis.io/apis/hr-partner/hr-partner-leave-balances-api/) — Read leave entitlement balances and accruals.
- [HR Partner Leave Requests API](https://apis.io/apis/hr-partner/hr-partner-leave-requests-api/) — Read leave and PTO requests submitted by employees.
- [HR Partner Library API](https://apis.io/apis/hr-partner/hr-partner-library-api/) — Read document library files and categories.
- [HR Partner Lookups API](https://apis.io/apis/hr-partner/hr-partner-lookups-api/) — Read system lookup definitions for configurable fields.
- [HR Partner Notes API](https://apis.io/apis/hr-partner/hr-partner-notes-api/) — Retrieve internal HR notes attached to employees.
- [HR Partner Positions API](https://apis.io/apis/hr-partner/hr-partner-positions-api/) — Read employee position history and remuneration.
- [HR Partner Projects API](https://apis.io/apis/hr-partner/hr-partner-projects-api/) — Read projects and activities used by timesheets.
- [HR Partner Reminders API](https://apis.io/apis/hr-partner/hr-partner-reminders-api/) — Read, update, and delete user reminders.
- [HR Partner Renewables API](https://apis.io/apis/hr-partner/hr-partner-renewables-api/) — Read renewable items such as certifications and licenses.
- [HR Partner Reviews API](https://apis.io/apis/hr-partner/hr-partner-reviews-api/) — Read performance reviews and scoring.
- [HR Partner Skills API](https://apis.io/apis/hr-partner/hr-partner-skills-api/) — Read employee skills and competency ratings.
- [HR Partner Timesheets API](https://apis.io/apis/hr-partner/hr-partner-timesheets-api/) — Read and create timesheets and timeclock entries.
- [HR Partner Training API](https://apis.io/apis/hr-partner/hr-partner-training-api/) — Read employee training and course completion records.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hr Partner Agentic Access](https://apis.io/agentic-access/hr-partner/hr-partner-agentic-access/)

#### JSON Schema (17)

The data models the API reads and writes.

- [Absence](https://apis.io/schemas/hr-partner/hr-partner-absence/)
- [Applicant](https://apis.io/schemas/hr-partner/hr-partner-applicant/)
- [Application](https://apis.io/schemas/hr-partner/hr-partner-application/)
- [Attachment](https://apis.io/schemas/hr-partner/hr-partner-attachment/)
- [Checklist](https://apis.io/schemas/hr-partner/hr-partner-checklist/)
- [Company](https://apis.io/schemas/hr-partner/hr-partner-company/)
- [Employee](https://apis.io/schemas/hr-partner/hr-partner-employee/)
- [EmployeeRef](https://apis.io/schemas/hr-partner/hr-partner-employee-ref/)
- [Expense](https://apis.io/schemas/hr-partner/hr-partner-expense/)
- [Goal](https://apis.io/schemas/hr-partner/hr-partner-goal/)
- [JobListing](https://apis.io/schemas/hr-partner/hr-partner-job-listing/)
- [LeaveBalance](https://apis.io/schemas/hr-partner/hr-partner-leave-balance/)
- [LeaveRequest](https://apis.io/schemas/hr-partner/hr-partner-leave-request/)
- [Project](https://apis.io/schemas/hr-partner/hr-partner-project/)
- [Reminder](https://apis.io/schemas/hr-partner/hr-partner-reminder/)
- [Review](https://apis.io/schemas/hr-partner/hr-partner-review/)
- [Timesheet](https://apis.io/schemas/hr-partner/hr-partner-timesheet/)

#### JSON Structure (16)

Data models expressed in JSON Structure.

- [Hr Partner Absence Structure](https://apis.io/json-structure/hr-partner/hr-partner-absence-structure/)
- [Hr Partner Applicant Structure](https://apis.io/json-structure/hr-partner/hr-partner-applicant-structure/)
- [Hr Partner Application Structure](https://apis.io/json-structure/hr-partner/hr-partner-application-structure/)
- [Hr Partner Attachment Structure](https://apis.io/json-structure/hr-partner/hr-partner-attachment-structure/)
- [Hr Partner Checklist Structure](https://apis.io/json-structure/hr-partner/hr-partner-checklist-structure/)
- [Hr Partner Company Structure](https://apis.io/json-structure/hr-partner/hr-partner-company-structure/)
- [Hr Partner Employee Structure](https://apis.io/json-structure/hr-partner/hr-partner-employee-structure/)
- [Hr Partner Expense Structure](https://apis.io/json-structure/hr-partner/hr-partner-expense-structure/)
- [Hr Partner Goal Structure](https://apis.io/json-structure/hr-partner/hr-partner-goal-structure/)
- [Hr Partner Job Listing Structure](https://apis.io/json-structure/hr-partner/hr-partner-job-listing-structure/)
- [Hr Partner Leave Balance Structure](https://apis.io/json-structure/hr-partner/hr-partner-leave-balance-structure/)
- [Hr Partner Leave Request Structure](https://apis.io/json-structure/hr-partner/hr-partner-leave-request-structure/)
- [Hr Partner Project Structure](https://apis.io/json-structure/hr-partner/hr-partner-project-structure/)
- [Hr Partner Reminder Structure](https://apis.io/json-structure/hr-partner/hr-partner-reminder-structure/)
- [Hr Partner Review Structure](https://apis.io/json-structure/hr-partner/hr-partner-review-structure/)
- [Hr Partner Timesheet Structure](https://apis.io/json-structure/hr-partner/hr-partner-timesheet-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hr Partner Context](https://apis.io/jsonld/hr-partner/hr-partner-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [HR Partner Domain Vocabulary](https://apis.io/vocabularies/hr-partner/hr-partner-vocabulary/)

#### Examples (16)

Example requests and responses.

- [Hr Partner Absence Example](https://apis.io/examples/hr-partner/hr-partner-absence-example/)
- [Hr Partner Applicant Example](https://apis.io/examples/hr-partner/hr-partner-applicant-example/)
- [Hr Partner Application Example](https://apis.io/examples/hr-partner/hr-partner-application-example/)
- [Hr Partner Attachment Example](https://apis.io/examples/hr-partner/hr-partner-attachment-example/)
- [Hr Partner Checklist Example](https://apis.io/examples/hr-partner/hr-partner-checklist-example/)
- [Hr Partner Company Example](https://apis.io/examples/hr-partner/hr-partner-company-example/)
- [Hr Partner Employee Example](https://apis.io/examples/hr-partner/hr-partner-employee-example/)
- [Hr Partner Expense Example](https://apis.io/examples/hr-partner/hr-partner-expense-example/)
- [Hr Partner Goal Example](https://apis.io/examples/hr-partner/hr-partner-goal-example/)
- [Hr Partner Job Listing Example](https://apis.io/examples/hr-partner/hr-partner-job-listing-example/)
- [Hr Partner Leave Balance Example](https://apis.io/examples/hr-partner/hr-partner-leave-balance-example/)
- [Hr Partner Leave Request Example](https://apis.io/examples/hr-partner/hr-partner-leave-request-example/)
- [Hr Partner Project Example](https://apis.io/examples/hr-partner/hr-partner-project-example/)
- [Hr Partner Reminder Example](https://apis.io/examples/hr-partner/hr-partner-reminder-example/)
- [Hr Partner Review Example](https://apis.io/examples/hr-partner/hr-partner-review-example/)
- [Hr Partner Timesheet Example](https://apis.io/examples/hr-partner/hr-partner-timesheet-example/)

#### Collections (62)

Postman and Open Collection request collections.

- [HR Partner REST Absences API](https://apis.io/collections/hr-partner/open-hr-partner-absences-api/)
- [HR Partner REST Absences Addresses API](https://apis.io/collections/hr-partner/open-hr-partner-addresses-api/)
- [HR Partner REST Absences Applicants API](https://apis.io/collections/hr-partner/open-hr-partner-applicants-api/)
- [HR Partner REST Absences Application Stage Tracking API](https://apis.io/collections/hr-partner/open-hr-partner-application-stage-tracking-api/)
- [HR Partner REST Absences Applications API](https://apis.io/collections/hr-partner/open-hr-partner-applications-api/)
- [HR Partner REST Absences Assets API](https://apis.io/collections/hr-partner/open-hr-partner-assets-api/)
- [HR Partner REST Absences Attachments API](https://apis.io/collections/hr-partner/open-hr-partner-attachments-api/)
- [HR Partner REST Absences Benefits API](https://apis.io/collections/hr-partner/open-hr-partner-benefits-api/)
- [HR Partner REST Absences Checklists API](https://apis.io/collections/hr-partner/open-hr-partner-checklists-api/)
- [HR Partner REST Absences Company API](https://apis.io/collections/hr-partner/open-hr-partner-company-api/)
- [HR Partner REST Absences Contacts API](https://apis.io/collections/hr-partner/open-hr-partner-contacts-api/)
- [HR Partner REST Absences Dependents API](https://apis.io/collections/hr-partner/open-hr-partner-dependents-api/)
- [HR Partner REST Absences Education API](https://apis.io/collections/hr-partner/open-hr-partner-education-api/)
- [HR Partner REST Absences Employees API](https://apis.io/collections/hr-partner/open-hr-partner-employees-api/)
- [HR Partner REST Absences Expenses API](https://apis.io/collections/hr-partner/open-hr-partner-expenses-api/)
- [HR Partner REST Absences Goals API](https://apis.io/collections/hr-partner/open-hr-partner-goals-api/)
- [HR Partner REST Absences Grievances API](https://apis.io/collections/hr-partner/open-hr-partner-grievances-api/)
- [HR Partner REST Absences Job Listings API](https://apis.io/collections/hr-partner/open-hr-partner-job-listings-api/)
- [HR Partner REST Absences Leave Balances API](https://apis.io/collections/hr-partner/open-hr-partner-leave-balances-api/)
- [HR Partner REST Absences Leave Requests API](https://apis.io/collections/hr-partner/open-hr-partner-leave-requests-api/)
- [HR Partner REST Absences Library API](https://apis.io/collections/hr-partner/open-hr-partner-library-api/)
- [HR Partner REST Absences Lookups API](https://apis.io/collections/hr-partner/open-hr-partner-lookups-api/)
- [HR Partner REST Absences Notes API](https://apis.io/collections/hr-partner/open-hr-partner-notes-api/)
- [HR Partner REST Absences Positions API](https://apis.io/collections/hr-partner/open-hr-partner-positions-api/)
- [HR Partner REST Absences Projects API](https://apis.io/collections/hr-partner/open-hr-partner-projects-api/)
- …and 37 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [HR Partner — jsonschema rules](https://apis.io/rules/hr-partner/hr-partner-jsonschema-spectral-rules/)
- [HR Partner — rest api rules](https://apis.io/rules/hr-partner/hr-partner-rest-api-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hr Partner Authentication](https://apis.io/security/hr-partner/hr-partner-authentication/)
- [Hr Partner Domain Security](https://apis.io/security/hr-partner/hr-partner-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hr Partner Plans Pricing](https://apis.io/plans/hr-partner/hr-partner-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hr Partner Rate Limits](https://apis.io/rate-limits/hr-partner/hr-partner-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hr Partner Finops](https://apis.io/finops/hr-partner/hr-partner-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hrpartner.io)
- [Documentation](https://developer.hrpartner.io/)
- [API reference](https://developer.hrpartner.io/)
- [Pricing](https://hrpartner.io/pricing.html)
- [Support](https://help.hrpartner.io)
- [Blog](https://blog.hrpartner.io)
- [GitHub](https://github.com/HR-Partner)
- [Status](https://status.hrpartner.io)

## API Evangelist rating

**Kin Score 40.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 54.4 |
| Contract governance | 23.5 |
| Operational transparency | 15.8 |
| Developer ergonomics | 40.5 |
| Access clarity | 31.6 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hr-partner/](https://apis.io/providers/hr-partner/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HR Partner: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hr-partner/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
