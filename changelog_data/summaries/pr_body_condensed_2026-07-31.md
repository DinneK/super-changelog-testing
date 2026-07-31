# 📋 Weekly Changelog
**Period**: 2026-07-24 to 2026-07-31

## 📊 Quick Stats
- **Active Repositories**: 26/172
- 📦 **Commits**: 96 | 🔀 **Pull Requests**: 220 | ❗️ **Issues**: 133

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
- [FFS-4495: Add one more URL to Accenture iframe](https://github.com/DSACMS/iv-cbv-payroll/pull/1943)
- [FFS-4496: Add logging to JsonTransmitter and HttpPdfTransmitter](https://github.com/DSACMS/iv-cbv-payroll/pull/1940)

### medicare_monthly_enrollment_dashboard
- [Added accessible design to visuals, added mobile bar graph and grid to trend card](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/40)

### mint-app
- [[MINT-3804] Part 1 - Add CTAT feature flag](https://github.com/CMS-Enterprise/mint-app/pull/2427)

### ospo-guide
- [Adding repodiving.md to inbound section of OSPO-guide](https://github.com/DSACMS/ospo-guide/pull/134)

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

### ztmf
- [fix(auth): scope the session cookie to the issuing host](https://github.com/CMS-Enterprise/ztmf/pull/497)
- [fix(infra): route alarm notifications to the shared ISPG inbox](https://github.com/CMS-Enterprise/ztmf/pull/496)

### ztmf-ui
- [fix(dashboard): scope average system score to the selected data call (#633)](https://github.com/CMS-Enterprise/ztmf-ui/pull/637)

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
- [Build(deps): bump the other group with 6 updates](https://github.com/CMS-Enterprise/mint-app/pull/2425)

### power-platform-webres
- [text changes to remove EASI phrasing](https://github.com/CMS-Enterprise/power-platform-webres/pull/32)

### repodive-tools
- [Updating repodive-tools README.md and CONTRIBUTING.md to match the OSPO guides improved docs!](https://github.com/DSACMS/repodive-tools/pull/23)

## 🗑️ Removed
*Deprecations and removals*

### easi-app
- [remove unused script](https://github.com/CMS-Enterprise/easi-app/pull/3530)
- [removed references to cedar proxy](https://github.com/CMS-Enterprise/easi-app/pull/3527)

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

- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 11 commits, 115 pulls, 77 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 9 commits, 30 pulls, 34 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 14 commits, 17 pulls
- **[medicare_monthly_enrollment_dashboard](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard)**: 21 commits, 8 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 5 commits, 21 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 9 commits, 11 pulls
- **[power-platform-webres](https://github.com/CMS-Enterprise/power-platform-webres)**: 8 commits, 3 pulls
- **[code-book](https://github.com/DSACMS/code-book)**: 7 commits
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 5 commits, 1 pulls, 3 issues
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 5 pulls, 5 issues
- *...and 16 more repositories*

---
*🤖 Generated automatically on 2026-07-31T02:37:43.374724+00:00*