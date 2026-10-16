# 📋 Weekly Changelog
**Period**: 2026-10-09 to 2026-10-16

## 📊 Quick Stats
- **Active Repositories**: 22/177
- 📦 **Commits**: 114 | 🔀 **Pull Requests**: 198 | ❗️ **Issues**: 11

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

### codejson-action-e2e
- [Add AGENCY and AI enrichment scenarios](https://github.com/DSACMS/codejson-action-e2e/pull/53)
- [Add code.json fixture with blank enrichable fields](https://github.com/DSACMS/codejson-action-e2e/pull/52)

### codejson-generator
- [Add webllm feature to README](https://github.com/DSACMS/codejson-generator/pull/153)

### medicare_monthly_enrollment_dashboard
- [Added download CSV button to trend data table](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/53)

### power-platform-webres
- [[PPE-130] Updated business case solution logic to add error handling if submit attempted without correct solutions](https://github.com/CMS-Enterprise/power-platform-webres/pull/53)

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

### batcave-workflow-engine
- Viper config key names
- Specified CLI command parameters for custom input and output for easier unit testing in the future

## 🔧 Changed
*Updates and modifications*

### Esmd-fhir-client-python
- **Type Hints**: Added comprehensive type annotations throughout shared utilities
- **Error Handling**: Standardized and improved error handling patterns
- **Logging**: Enhanced logging with structured output and rotation
- **Code Structure**: Better separation of concerns and modularity
- **Dependency Security**: Pinned versions to prevent security vulnerabilities
- *...and 7 more*

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### codejson-action-e2e
- [Updating docs](https://github.com/DSACMS/codejson-action-e2e/pull/50)

### codejson-generator
- [docs: update contributors information](https://github.com/DSACMS/codejson-generator/pull/152)

### gov-codejson
- [Repository Hygiene: Update documentation to reflect current state of the repository](https://github.com/DSACMS/gov-codejson/pull/61)
- [Update code.json](https://github.com/DSACMS/gov-codejson/pull/60)
- [Update faq.md](https://github.com/DSACMS/gov-codejson/pull/55)

### iv-cbv-payroll
- [Commit schema update](https://github.com/DSACMS/iv-cbv-payroll/pull/2182)
- [FFS-4896 Update schema to match implementation](https://github.com/DSACMS/iv-cbv-payroll/pull/2181)
- [FFS-4871: Update Education Review, Review and Submit, PDF](https://github.com/DSACMS/iv-cbv-payroll/pull/2179)

### share-it-act-lp
- [Update code.json](https://github.com/DSACMS/share-it-act-lp/pull/59)

### ztmf
- [feat(misc#378): log the TLS key exchange group on the SMTP and Kion hops](https://github.com/CMS-Enterprise/ztmf/pull/614)
- [feat(misc#377): log the TLS key exchange group of each API handshake](https://github.com/CMS-Enterprise/ztmf/pull/613)

## 🗑️ Removed
*Deprecations and removals*

### mint-app
- [[NOREF] Remove old text](https://github.com/CMS-Enterprise/mint-app/pull/2601)

## 🔒 Security
*Security improvements*

### Esmd-fhir-client-python
- **Dependency Pinning**: All dependencies are pinned to specific versions
- **Environment Variables**: Sensitive configuration moved to environment variables
- **Token Security**: Improved token handling and storage
- **Input Validation**: Better validation of configuration and input data
- **Token Caching**: Reduced authentication overhead with intelligent caching
- *...and 13 more*

## 🚀 Active Repositories

- **[codejson-action-e2e](https://github.com/DSACMS/codejson-action-e2e)**: 32 commits, 37 pulls
- **[gov-codejson](https://github.com/DSACMS/gov-codejson)**: 11 commits, 51 pulls, 3 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 25 commits, 32 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 6 commits, 19 pulls
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 8 commits, 10 pulls, 2 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 7 commits, 11 pulls
- **[index-generator-website](https://github.com/DSACMS/index-generator-website)**: 1 commits, 13 pulls, 2 issues
- **[codejson-generator](https://github.com/DSACMS/codejson-generator)**: 6 commits, 4 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 3 commits, 7 pulls, 2 issues
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 5 commits, 4 pulls
- *...and 12 more repositories*

---
*🤖 Generated automatically on 2026-10-16T03:08:48.026076+00:00*