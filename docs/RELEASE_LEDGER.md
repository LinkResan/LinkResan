# LinkResan — Public Release Ledger

> Canonical public repository: `LinkResan/LinkResan`
>
> Canonical Production source: `AmirMotefaker/LinkResan-Production` (private)
>
> This ledger records public-safe product milestones only. It intentionally excludes proprietary source code, credentials, customer data, database URLs, migration SQL, private deployment topology, gateway secrets and internal operational evidence.

## Current synchronization status

Public product truth in this repository is synchronized through **2026-09-06**.

## 2026-09-06 — CRM360 analytics & Bio traffic

### Public-safe release summary
- Completed real analytics visibility in CRM360.
- Added Bio traffic tracking.
- Production database migration was applied with site health verified before and after the migration.

### Confidentiality boundary
The migration SQL, database identifiers, customer-level records, admin implementation and operational evidence remain private.

---

## 2026-09-05 — CRM360 resources, original QR and Bio lookup

### Public-safe release summary
- Improved CRM360 visibility into user link resources.
- Added deterministic original QR preview/download support.
- Added case-insensitive Bio slug lookup.

### Confidentiality boundary
Internal CRM queries, authorization implementation, customer identifiers and storage details remain private.

---

## 2026-09-04 — Analytics Pro P0 & Smart Links knowledge

### Public-safe release summary
- Released Analytics Pro P0 after exact-head Preview validation.
- Published the Smart Links routing guide after Preview QA, CI and public/knowledge guards.

### Confidentiality boundary
Production telemetry internals, private analytics implementation and deployment evidence remain private.

---

## 2026-09-03 — SEO/GEO foundation & Knowledge intelligence refresh

### Public-safe release summary
- Established canonical SEO/GEO entity and schema foundations.
- Enriched structured data on product landing surfaces.
- Published indexable comparison surfaces for major URL-management alternatives.
- Published a QR campaign tracking guide.
- Refreshed analytics intelligence content covering UTM, referrer, conversion and period-comparison concepts.
- Enforced Knowledge freshness guardrails.

### Confidentiality boundary
Internal ranking research, automation credentials, private content-generation configuration and operational logs remain private.

---

## 2026-08-25 — Android delivery pipeline

### Public-safe release summary
- Added a GitHub-based Android APK build workflow to the private Production delivery pipeline.

### Status
Native/mobile delivery remains **Preview / Partial** publicly until the complete mobile release gate is satisfied.

### Confidentiality boundary
Signing material, credentials, CI secrets and private distribution configuration remain private.

---

## 2026-08-24 — Usage intelligence & Knowledge hardening

### Public-safe release summary
- Added server-authoritative usage meters.
- Added a read-only usage dashboard.
- Hardened the multi-stage Knowledge planner.
- Expanded curated research coverage.

### Confidentiality boundary
Usage enforcement internals, private analytics queries, provider credentials and automation internals remain private.

---

## 2026-08-22 — Growth, product landing and Preview-origin hardening

### Public-safe release summary
- Redesigned product landing pages around server-rendered Product Truth, canonical metadata, sitemap coverage and conversion-focused internal linking.
- Added privacy-safe activation funnel instrumentation.
- Added support for explicitly approved Preview origins under strict CORS controls.

### Confidentiality boundary
Private growth-event transport, infrastructure origins, environment configuration and runtime security implementation remain private.

---

## 2026-08-20 — CRM360 public-safe milestone

### Public-safe release summary
- CRM360 founder/customer intelligence surface became available as a sanitized, read-only administrative capability.
- Public showcase synchronization was moved to the `LinkResan` GitHub organization.

### Confidentiality boundary
CRM implementation, customer data and private operational detail remain private.

---

## 2026-08-19 — Official GitHub brand presence

### Public-safe release summary
- Established the public showcase security boundary.
- Added product, brand, architecture, developer, FAQ and roadmap documentation.
- Added fail-closed public snapshot controls.
- Preserved Production as the private canonical source.

---

## 2026-08-13 — Production-grade Zarinpal monetization closure

### Public-safe release summary
- Server-authoritative payment plan/amount selection.
- Idempotent checkout and verification lifecycle.
- Verified-payment subscription activation and renewal.
- Durable billing ledger and reconciliation contracts.
- Payment visibility in administrative CRM surfaces.

### Confidentiality boundary
Merchant credentials, Authority/RefID values, tokens, database URLs, account identifiers and payment operational evidence remain private.

---

## Historical public releases

The public repository also contains earlier historical tags/releases such as `v7.7.0`, `v7.8.0`, `v7.9.0`, the monetization closure release and `v1.0.0-public-showcase`.

Some historical Production releases (`v7.10.0`–`v7.13.0`) were restored as documentation backfill in the private repository and are represented publicly through release-history documentation rather than by exposing the proprietary implementation.

## Release publication policy

Every future meaningful Production release should update the public record through:

`Production milestone → public-safe sanitization → Issue → Branch → Commits → Pull Request → Review → Merge → public release/tag when supported`

A public release note must never include:
- secrets, credentials or tokens;
- customer/user data or identifiers;
- database URLs, migration SQL or private schema evidence;
- private infrastructure topology;
- payment-provider credentials or transaction identifiers;
- internal admin implementation details that weaken the security boundary.

For the current verified product state, see the root `README.md` and `docs/RELEASE_HISTORY_2026-09.md`.