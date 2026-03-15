# Migration Granularity Notes

- Repository: `fintechbankx-openfinance-personal-financial-data-service`
- Source monorepo: `enterprise-loan-management-system`
- Sync date: `2026-03-15`
- Sync branch: `chore/granular-source-sync-20260313`

## Applied Rules

- dir: `services/openfinance-personal-financial-data-service` -> `.`
- file: `api/openapi/personal-financial-data-service.yaml` -> `api/openapi/personal-financial-data-service.yaml`
- dir: `infra/terraform/services/personal-financial-data-service` -> `infra/terraform/personal-financial-data-service`
- file: `docs/architecture/open-finance/capabilities/hld/personal-financial-management-hld.md` -> `docs/hld/personal-financial-management-hld.md`
- file: `docs/architecture/open-finance/capabilities/test-suites/account-information-test-suite.md` -> `docs/test-suites/account-information-test-suite.md`

## Notes

- This is an extraction seed for bounded-context split migration.
- Follow-up refactoring may be needed to remove residual cross-context coupling.
- Build artifacts and local machine files are excluded by policy.

