# HR Partner (hr-partner)

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
