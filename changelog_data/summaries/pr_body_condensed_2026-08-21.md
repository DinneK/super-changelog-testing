# 📋 Weekly Changelog
**Period**: 2026-08-14 to 2026-08-21

## 📊 Quick Stats
- **Active Repositories**: 36/175
- 📦 **Commits**: 151 | 🔀 **Pull Requests**: 222 | ❗️ **Issues**: 84

## ✅ Added
*New features and additions*

### Esmd-fhir-client-python
- **Shared Utilities Package**: Created `esmd_shared` package to eliminate code duplication
- Enhanced `EsmdAuthClient` with token caching, better error handling, and type hints
- Improved `ConfigUtility` with environment variable support and validation
- Advanced `logger` module with file rotation and configurable formatting
- **Comprehensive Documentation**: Complete README.md with installation, usage, and API documentation
- *...and 19 more*

### batcave-tf-gatus
- Changelog
- pre-commit

### batcave-workflow-engine
- GitHub action auth support
- settings package for config and metaconfig values
- settings package marshalling / unmarshalling
- Grype Image Scan Task
- Task pattern instead of pipeline pattern for simplicity Note: currently the new experimental is behind a build flag
- *...and 50 more*

### caseworkerportal
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/caseworkerportal/pull/16)

### easi-app
- [[EASI-5057] Implementing New Okta Login Page Based on Environmental Variable](https://github.com/CMS-Enterprise/easi-app/pull/3536)

### fdsh-utils
- [9 add jsonschema for nscrequest object](https://github.com/DSACMS/fdsh-utils/pull/12)
- [Add mock-service Sub Project](https://github.com/DSACMS/fdsh-utils/pull/8)

### income-reporting-playbook
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/income-reporting-playbook/pull/17)

### iv-delivery
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/iv-delivery/pull/3)

### iv-doc-uploader
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/iv-doc-uploader/pull/40)

### iv-verify
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/iv-verify/pull/100)
- [Metadata: Add code.json](https://github.com/DSACMS/iv-verify/pull/99)

### metrics_frontend
- [Add project type tag styles and update layout for project type display](https://github.com/DSACMS/metrics_frontend/pull/8)

### mint-app
- [Add TWO_PAGER plan task key, seeded on model plan creation](https://github.com/CMS-Enterprise/mint-app/pull/2470)

### power-platform-webres
- [Added PAC CLI scripts](https://github.com/CMS-Enterprise/power-platform-webres/pull/38)

### repo-scaffolder
- [Outbound Checklists and Docs: Add instructions for installing dependencies](https://github.com/DSACMS/repo-scaffolder/pull/400)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

## 🪲 Fixed
*Bug fixes and corrections*

### Esmd-fhir-client-python
- **Code Duplication**: Eliminated duplicate files across modules
- **Import Issues**: Fixed circular imports and dependency issues
- **Configuration Loading**: Improved config file discovery and error handling
- **Token Refresh**: Fixed token expiration and refresh logic
- **Package Structure**: Proper Python package hierarchy
- *...and 5 more*

### automated-codejson-generator
- [fix(deps): resolve all 47 open Dependabot alerts](https://github.com/DSACMS/automated-codejson-generator/pull/140)

### batcave-workflow-engine
- Viper config key names
- Specified CLI command parameters for custom input and output for easier unit testing in the future

### easi-app
- [fix bug in cedar publish](https://github.com/CMS-Enterprise/easi-app/pull/3537)

### iv-cbv-payroll
- [fix: patch Dockerfile for OS-level CVEs flagged by Trivy/Anchore](https://github.com/DSACMS/iv-cbv-payroll/pull/1994)

### power-platform-webres
- [Ppe 81/final business case reset bug](https://github.com/CMS-Enterprise/power-platform-webres/pull/39)

### repo-scaffolder
- [Templates: Fix typo in PR templates](https://github.com/DSACMS/repo-scaffolder/pull/402)

## 🔧 Changed
*Updates and modifications*

### Esmd-fhir-client-python
- **Type Hints**: Added comprehensive type annotations throughout shared utilities
- **Error Handling**: Standardized and improved error handling patterns
- **Logging**: Enhanced logging with structured output and rotation
- **Code Structure**: Better separation of concerns and modularity
- **Dependency Security**: Pinned versions to prevent security vulnerabilities
- *...and 7 more*

### archival-identifier
- [Update code.json](https://github.com/DSACMS/archival-identifier/pull/23)

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### mint-app
- [[MINT-3859] CTAT text update](https://github.com/CMS-Enterprise/mint-app/pull/2468)

### ospo-guide
- [Update code.json](https://github.com/DSACMS/ospo-guide/pull/135)

### repo-scaffolder
- [Update maturity-model-tiers.md](https://github.com/DSACMS/repo-scaffolder/pull/384)

### super-changelog
- [docs: update contributors information](https://github.com/DSACMS/super-changelog/pull/140)
- [docs: update contributors information](https://github.com/DSACMS/super-changelog/pull/139)
- [docs: update contributors information](https://github.com/DSACMS/super-changelog/pull/138)

### testing-repository
- [Update code.json](https://github.com/DSACMS/testing-repository/pull/88)

## 🗑️ Removed
*Deprecations and removals*

### easi-app
- [[NOREF] Remove the Hardcoded False in build_static](https://github.com/CMS-Enterprise/easi-app/pull/3538)

### ztmf-ui
- [Stop deleting drafts on a version mismatch (rollback destroys them)](https://github.com/CMS-Enterprise/ztmf-ui/pull/713)

## 🔒 Security
*Security improvements*

### Esmd-fhir-client-python
- **Dependency Pinning**: All dependencies are pinned to specific versions
- **Environment Variables**: Sensitive configuration moved to environment variables
- **Token Security**: Improved token handling and storage
- **Input Validation**: Better validation of configuration and input data
- **Token Caching**: Reduced authentication overhead with intelligent caching
- *...and 13 more*

## 📚 Documentation
*Documentation updates*

### iv-cbv-payroll
- [FFS-4688: Clean up order and styling of components on doc upload page](https://github.com/DSACMS/iv-cbv-payroll/pull/1993)

## 🚀 Active Repositories

- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 5 commits, 53 pulls, 20 issues
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 14 commits, 26 pulls, 1 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 14 commits, 20 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 6 commits, 24 pulls, 29 issues
- **[power-platform-webres](https://github.com/CMS-Enterprise/power-platform-webres)**: 20 commits, 4 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 5 commits, 18 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 17 commits, 5 pulls
- **[codejson-action-e2e](https://github.com/DSACMS/codejson-action-e2e)**: 14 commits, 7 pulls
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 4 commits, 12 pulls, 4 issues
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 7 commits, 6 pulls, 2 issues
- *...and 26 more repositories*

---
*🤖 Generated automatically on 2026-08-21T01:09:09.903948+00:00*