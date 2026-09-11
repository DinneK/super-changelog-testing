# 📋 Weekly Changelog
**Period**: 2026-09-04 to 2026-09-11

## 📊 Quick Stats
- **Active Repositories**: 20/175
- 📦 **Commits**: 51 | 🔀 **Pull Requests**: 116 | ❗️ **Issues**: 17

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

### easi-app
- [[EASI-5059] add cedar fields](https://github.com/CMS-Enterprise/easi-app/pull/3548)

### iv-cbv-payroll
- [FFS-4802 & FFS-4803: Update content on "Choose how you want to add your work" page on Emmy CE Employment flow, Update helper text on employment information page for paid work in Emmy CE manual reporting flow](https://github.com/DSACMS/iv-cbv-payroll/pull/2052)
- [FFS-4794: Add environment selection to deploy script](https://github.com/DSACMS/iv-cbv-payroll/pull/2049)

### power-platform-webres
- [PPE-85 Validate migration of multi-select Additional Contact Roles [WIP]](https://github.com/CMS-Enterprise/power-platform-webres/pull/41)

### repo-scaffolder
- [docs(templates): add PRA, Plain Language and Section 508 guidance to the README templates](https://github.com/DSACMS/repo-scaffolder/pull/401)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

### ztmf
- [fix(misc#297): add the READONLY_ADMIN mass-email group and widen massemails.group](https://github.com/CMS-Enterprise/ztmf/pull/580)

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

### fdsh-utils
- [ [FFS-4823] fix misnamed services and introduce a schema viewer for NSC data](https://github.com/DSACMS/fdsh-utils/pull/27)

### power-platform-webres
- [PPE-114 Edit Request Submit Bug](https://github.com/CMS-Enterprise/power-platform-webres/pull/48)

### ztmf-ui
- [hotfix(misc#386): carry the system id from System Info to the questionnaire and refuse ambiguous acronyms](https://github.com/CMS-Enterprise/ztmf-ui/pull/734)

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

### mint-app
- [Mint 3879/change history 6 pager](https://github.com/CMS-Enterprise/mint-app/pull/2516)

### ztmf
- [chore(ci): bump the github-actions group with 2 updates](https://github.com/CMS-Enterprise/ztmf/pull/579)

## 🗑️ Removed
*Deprecations and removals*

### iv-cbv-payroll
- [Remove bencalegari from reviewer lottery](https://github.com/DSACMS/iv-cbv-payroll/pull/2056)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 21 commits, 30 pulls, 2 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 8 commits, 27 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 6 commits, 11 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 5 commits, 10 pulls, 4 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 3 commits, 10 pulls, 3 issues
- **[fdsh-utils](https://github.com/DSACMS/fdsh-utils)**: 5 commits, 5 pulls
- **[power-platform-webres](https://github.com/CMS-Enterprise/power-platform-webres)**: 3 commits, 5 pulls
- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 6 pulls
- **[medicare_monthly_enrollment_dashboard](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard)**: 3 pulls, 1 issues
- **[repo-scaffolder](https://github.com/DSACMS/repo-scaffolder)**: 2 pulls
- *...and 10 more repositories*

---
*🤖 Generated automatically on 2026-09-11T03:01:10.253789+00:00*