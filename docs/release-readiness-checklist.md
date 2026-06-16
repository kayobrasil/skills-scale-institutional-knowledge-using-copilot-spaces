# Release Readiness Checklist

Use this checklist before promoting to production.

Pre-release
- [ ] All PRs merged and linked to issues with acceptance criteria
- [ ] CI passed, linting and security scans completed
- [ ] Release notes drafted and reviewed
- [ ] Telemetry instrumentation and dashboards validated (Data Analyst)
- [ ] UX sign-off for customer-facing changes (Designer)
- [ ] QA sign-off on test coverage and exploratory test results
- [ ] SRE/Platform confirms environment readiness and rollback plan
- [ ] Delivery Lead confirmed cutover plan and cross-team dependencies

Deployment
- [ ] Backup/snapshot taken (if applicable)
- [ ] Deployment automated and validated in staging
- [ ] Smoke tests executed in staging and results validated
- [ ] Communication sent to stakeholders and support

Post-release
- [ ] Smoke tests executed in production
- [ ] Monitor dashboards and alerts for anomalies
- [ ] Post-release debrief and capture action items
- [ ] Update risk register if any incidents occurred
