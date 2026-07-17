# 📋 Weekly Changelog
**Period**: 2026-07-10 to 2026-07-17

## 📊 Quick Stats
- **Active Repositories**: 26/171
- 📦 **Commits**: 105 | 🔀 **Pull Requests**: 151 | ❗️ **Issues**: 88

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

### iv-cbv-payroll
- [FFS-4465: Add configurable household setup to launcher](https://github.com/DSACMS/iv-cbv-payroll/pull/1906)

### medicare_monthly_enrollment_dashboard
- [Add All Areas and county enrollment data grids below the state map](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/25)
- [Adding map cards for front-end and wiring up buttons](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/23)
- [Add pie chart card section with dashboard selection buttons](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/22)

### ospo-guide
- [[DRAFT] Outbound: Create new Generative AI Usage policy](https://github.com/DSACMS/ospo-guide/pull/130)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

### ztmf-ui
- [Add an opdiv field to the system details page](https://github.com/CMS-Enterprise/ztmf-ui/pull/557)

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

### ztmf
- [fix(model): make users_fismasystems Save idempotent on duplicate assignment (#429)](https://github.com/CMS-Enterprise/ztmf/pull/438)
- [fix(api): return 400 not 500 for malformed list-endpoint query params (#420)](https://github.com/CMS-Enterprise/ztmf/pull/430)

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

### easi-app
- [[EASI-5043] Modify System Intake Contract Questions](https://github.com/CMS-Enterprise/easi-app/pull/3501)

## 🗑️ Removed
*Deprecations and removals*

### mint-app
- [[MINT-3797] Remove custom date](https://github.com/CMS-Enterprise/mint-app/pull/2402)

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

- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 24 commits, 59 pulls, 40 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 15 commits, 19 pulls, 1 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 9 commits, 21 pulls, 24 issues
- **[medicare_monthly_enrollment_dashboard](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard)**: 18 commits, 7 pulls, 2 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 3 commits, 21 pulls
- **[testing-repository](https://github.com/DSACMS/testing-repository)**: 13 commits
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 6 commits, 6 pulls, 7 issues
- **[code-book](https://github.com/DSACMS/code-book)**: 8 commits, 2 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 2 commits, 7 pulls
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 3 pulls
- *...and 16 more repositories*

---
*🤖 Generated automatically on 2026-07-17T02:29:01.991620+00:00*