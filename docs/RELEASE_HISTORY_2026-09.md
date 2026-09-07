# LinkResan — Public Release History · September 2026

This document records public-safe product milestones verified in the private canonical Production repository. It intentionally excludes source code, credentials, deployment topology, customer data, migration SQL, private audit evidence and internal operational identifiers.

Canonical Production source: `AmirMotefaker/LinkResan-Production` (private)

## 2026-09-06 — CRM360 analytics and Bio traffic tracking

### Product changes
- Completed real analytics coverage in the founder/admin CRM360 experience.
- Added Bio traffic tracking so Link-in-bio activity can be represented in product analytics.
- Extended customer intelligence visibility without exposing private customer records in this repository.

### Release evidence
- Local backend and frontend quality gates passed.
- A required Production database migration was applied successfully.
- Site health was verified as HTTP 200 before and after migration.
- GitHub Actions jobs were blocked by account billing/spending-limit infrastructure rather than test failures; this exception was documented in the private release record.

## 2026-09-05 — CRM360 links, QR and Bio lookup

### Product changes
- Added richer CRM360 user-link visibility for authorized admin workflows.
- Added deterministic original QR preview/download support.
- Hardened Bio slug lookup with case-insensitive behavior.

### Validation
- Local QA completed.
- Cloudflare Preview validation completed before release.

## 2026-09-04 — Analytics Pro P0

### Product changes
- Released Analytics Pro P0.
- Strengthened the analytics product surface for professional users.

### Validation
- Exact-head Preview validation completed.
- A GitHub Actions runner failure was treated as an infrastructure exception and documented separately from product/test quality.

## 2026-09-04 — Smart Links knowledge refresh

- Published the Smart Links routing guide.
- Completed Preview QA, CI, Public Showcase Guard and Knowledge Freshness Guard before publication.

## 2026-09-03 — SEO/GEO entity foundation

### Product changes
- Established canonical LinkResan entity/schema foundations for SEO and generative-engine discoverability.
- Added SEO/GEO guardrails.
- Enriched product landing structured data.
- Published indexable comparison surfaces covering major URL-management alternatives.

## 2026-09-03 — Knowledge intelligence refresh

- Published a QR campaign tracking guide.
- Added a seven-day Knowledge freshness SLA guard.
- Refreshed analytics guidance around UTM, referrer, conversion, period comparison, related content and canonical product links.

## 2026-08-25 — Android delivery automation

- Added a GitHub Android APK build workflow to the private Production delivery pipeline.
- Mobile remains represented publicly as a Preview/Partial surface unless a separate release gate promotes it.

## 2026-08-24 — Usage intelligence

- Added server-authoritative usage meters.
- Added a read-only usage dashboard.
- Added privacy-safe upgrade-intent handling.

## 2026-08-24 — Knowledge engine hardening

- Split planner decisions from candidate generation.
- Added two-stage planning and regression gates.
- Expanded curated research breadth.
- Hardened failure recovery for schema/provider edge cases.

## 2026-08-22 — Growth and conversion foundation

- Redesigned product landing pages around server-rendered product truth.
- Added canonical metadata, sitemap coverage and conversion-focused internal linking.
- Added privacy-safe activation-funnel instrumentation.
- Added strict CORS support for explicitly approved Preview origins.

## Public/private boundary

The public repository documents the product, architecture at a high level, releases, roadmap, developer entry points and selected public-safe technical material. The private Production repository remains the sole canonical source for runtime implementation, operational configuration, customer data, billing/payment internals and private evidence.

## Governance

Public refreshes follow:

`Issue → Branch → Commits → Pull Request → Code Review → Merge`

This history is linked to public sync Issue #13.
