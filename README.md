# HR Partner (hr-partner)

API Evangelist profile of [HR Partner](https://hrpartner.io), a cloud-based human resources management SaaS platform from HR Partner Software Pty Ltd (Australia), targeted at organizations of roughly 20 to 500 employees.

> "HR Partner gives teams of 20-500 the tools to run HR properly, with transparent pricing, no contracts, and real human support." — hrpartner.io

This repo started as a generic stub for "HR partner" and was profiled as the SaaS company after verifying hrpartner.io.

## Surface area

- **APIs documented**: 1 (HR Partner REST API)
- **Base URL**: `https://api.hrpartner.io`
- **Authentication**: API key in `x-api-key` request header (provisioned by an admin in Setup → Configure → Integrations)
- **Rate limits**: 60 requests/second, 900 requests/minute burst, 60-second response timeout, HTTPS required
- **Webhooks**: Not documented at developer.hrpartner.io as of this run
- **Status**: Documentation notes the API is in an "early release phase with potential breaking changes"

## Artifacts

| Folder | Count | Notes |
| --- | --- | --- |
| `openapi/` | 1 | `hr-partner-rest-api-openapi.yml` — full OpenAPI 3.1 spec covering ~40 operations across 28 tagged resources |
| `rules/` | 1 | Spectral rules enforcing title-case summaries, required `x-api-key` scheme, `api.hrpartner.io` server, etc. |
| `capabilities/` | 11 | Per-domain Naftiko capabilities plus an onboarding-workflow composition |
| `json-schema/` | 17 | JSON Schema for Employee, Leave Request/Balance, Absence, Timesheet, Applicant, Application, Job Listing, Review, Goal, Checklist, Expense, Attachment, Company, Project, Reminder, EmployeeRef |
| `json-structure/` | 16 | JSON Structure parallels of the schemas |
| `json-ld/` | 1 | `hr-partner-context.jsonld` mapping core entities to schema.org and `hrp:` namespace |
| `examples/` | 17 | Hand-crafted illustrative payloads (Employee, Leave, Timesheet, Applicant, Application, Review, Goal, Checklist, Expense, Attachment, Company, Project, Reminder, etc.) |
| `vocabulary/` | 1 | Tag-derived domain vocabulary |
| `rate-limits/` | 1 | API Commons rate-limit profile |
| `plans/` | 1 | API Commons plans profile capturing Core / Premium / VIP plan structure (exact monthly prices are rendered client-side and are not captured here) |
| `finops/` | 1 | FOCUS-aligned FinOps view |

## Naftiko capabilities

- `hr-partner-company.yaml`
- `hr-partner-employees.yaml`
- `hr-partner-employee-records.yaml` (contacts, addresses, notes, education, skills, training, assets, benefits, dependents, grievances, positions, renewables, attachments)
- `hr-partner-leave.yaml` (leave requests, balances, absences)
- `hr-partner-timesheets.yaml` (timesheets, timesheet entry create, projects)
- `hr-partner-recruitment.yaml` (job listings, applicants, applications, application-stage tracking)
- `hr-partner-performance.yaml` (reviews, goals)
- `hr-partner-checklists.yaml` (checklists, reminders with update/delete)
- `hr-partner-expenses.yaml`
- `hr-partner-library.yaml` (library documents, library categories, lookups)
- `hr-partner-onboarding-workflow.yaml` — composition wiring Employees + Checklists + Library + Reminders

## Common properties

- **Website**: https://hrpartner.io
- **Developer portal / docs**: https://developer.hrpartner.io
- **Support**: https://help.hrpartner.io
- **Blog**: https://blog.hrpartner.io
- **Status page**: https://status.hrpartner.io (powered by Better Stack)
- **GitHub org**: https://github.com/HR-Partner (27 public repos, mostly vendored Ruby gems — Padrino, DataMapper, plus a Slate fork for the API docs; no first-party SDK)
- **Pricing**: https://hrpartner.io/pricing.html

## Notable findings

- HR Partner Software Pty Ltd is based in Australia; the product is positioned for 20–500-employee teams.
- The public REST API surface is broad (employees, sub-modules, leave, timesheets, recruitment, performance, checklists, reminders, library, lookups) but read-heavy; write endpoints are limited to employee upsert, timesheet entry creation, applicant/application create-or-update, and reminder update/delete.
- The HR Partner GitHub org publishes a Slate-based fork that powers developer.hrpartner.io and many vendored Ruby dependencies, suggesting the platform is implemented on Padrino + DataMapper.
- A blog at blog.hrpartner.io publishes roughly every 1–2 days (e.g., "New Zealand's Leave Laws Are Changing. Here's What Small Businesses Need to Know.", 2026-05-18).
- The status page lists Application Server, Web Site, Marketing Blog, Documentation, Development Blog, Developer Portal, and API Service as services; all currently marked "All services are online" / not actively monitored at run time.

## Notable absences

- No public OpenAPI/Swagger or AsyncAPI artifact published by HR Partner.
- No documented webhook surface.
- No first-party SDKs published — only Ruby/Node/cURL snippets in the developer portal.
- No public per-tier pricing in static HTML (calculator-driven only).
- No public changelog/release-notes URL discovered.
- No RSS feed exposed on the blog.

## Index

The machine-readable index of this profile lives in [`apis.yml`](apis.yml).
