# HR Partner (hr-partner)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hr-partner/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hr-partner/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- HR
- HRIS
- Human Resources
- Employee Records
- Leave Management
- Recruitment
- Applicant Tracking
- Onboarding
- Performance Management
- Timesheets
- Expense Management
- Document Library
- eSignature
- SaaS
- Australia

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-23

## APIs

### HR Partner REST API

Public REST API for HR Partner, covering employee records and sub-modules (contacts, addresses, notes, education, skills, training, assets, benefits, dependents, grievances, positions, renewables, attachments), leave management (requests, balances, absences), timesheets and projects, expenses, recruitment (job listings, applicants, applications, application-stage tracking, interviews), performance (reviews, goals), checklists, reminders, document library, lookups, and company information. Authentication is via API key passed in the x-api-key header. Rate limits are 60 GET/POST requests per second and 900 requests per one-minute burst, with HTTPS required.

- **Human URL:** [https://developer.hrpartner.io/](https://developer.hrpartner.io/)
- **Base URL:** `https://api.hrpartner.io`

#### Tags

- HR
- HRIS
- Employee Records
- Leave Management
- Recruitment
- Applicant Tracking
- Performance Management
- Timesheets
- Expense Management
- REST

#### Properties

- [Documentation](https://developer.hrpartner.io/)
- [API Reference](https://developer.hrpartner.io/)
- [Authentication](https://developer.hrpartner.io/#authentication)
- [Rate Limits](https://developer.hrpartner.io/#rate-limits)
- [OpenAPI](openapi/hr-partner-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hr-partner-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hr-partner-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/hr-partner-rest-api-rules.yml)

## Common Properties

- [Website](https://hrpartner.io)
- [Documentation](https://developer.hrpartner.io/)
- [Developer Portal](https://developer.hrpartner.io/)
- [API Reference](https://developer.hrpartner.io/)
- [Sign Up](https://hrpartner.io/sign-up)
- [Pricing](https://hrpartner.io/pricing.html)
- [Support](https://help.hrpartner.io)
- [Blog](https://blog.hrpartner.io)
- [Status Page](https://status.hrpartner.io)
- [GitHub Organization](https://github.com/HR-Partner)
- [LinkedIn](https://www.linkedin.com/company/hr-partner-software)
- [Plans](plans/hr-partner-plans-pricing.yml)
- [Rate Limits](rate-limits/hr-partner-rate-limits.yml)
- [Fin Ops](finops/hr-partner-finops.yml)
- [Vocabulary](vocabulary/hr-partner-vocabulary.yml)
- [J S O N L D Context](json-ld/hr-partner-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
