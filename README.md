# CareLink Modular OS — Monorepo (V6 • 1000/1000)

Enterprise monorepo scaffold with Turbo+PNPM, 4 Next.js apps, shared packages, CI gates (lint, typecheck, unit, e2e, axe, Lighthouse), SAST/DAST/SBOM, bundle budgets, OpenAPI contracts, k6 load tests, OTel tracing, feature flags, audit trail, data retention job, and compliance matrix.

## Quick start
pnpm i
pnpm -w build
pnpm --filter @carelink/web dev

## CI
See .github/workflows/*.yml. Scans are blocking on High/Critical. Bundle budgets fail on >250 KB gzip/route.
