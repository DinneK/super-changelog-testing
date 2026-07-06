# 📋 Weekly Changelog
**Period**: 2026-06-29 to 2026-07-06

## 📊 Quick Stats
- **Active Repositories**: 60/168
- 📦 **Commits**: 74 | 🔀 **Pull Requests**: 151 | ❗️ **Issues**: 35

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
- [Add agency template variables for accenture agency](https://github.com/DSACMS/iv-cbv-payroll/pull/1875)
- [Deduplicate and harden process for adding new agencies](https://github.com/DSACMS/iv-cbv-payroll/pull/1874)

### ospo-guide
- [DSAC Engineering Handbook: Add LaunchDarkly and edit access request instructions](https://github.com/DSACMS/ospo-guide/pull/128)

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

### ospo-guide
- [Minor doc fixes](https://github.com/DSACMS/ospo-guide/pull/125)

### ztmf-ui
- [fix(login): distinguish lookup outages from unknown-email; enable withCredentials](https://github.com/CMS-Enterprise/ztmf-ui/pull/444)
- [Bug/disable grant save button](https://github.com/CMS-Enterprise/ztmf-ui/pull/442)

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

### emmy-agent-marketplace
- [[codex] Update Jira ticket conventions](https://github.com/DSACMS/emmy-agent-marketplace/pull/13)

### medicare_monthly_enrollment_dashboard
- [updated the logic in the backend functions](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/18)

### mint-app
- [[MINT-3785] bulk custom date updates](https://github.com/CMS-Enterprise/mint-app/pull/2378)
- [[MINT-3763] Update LDG solution](https://github.com/CMS-Enterprise/mint-app/pull/2376)

### super-changelog
- [📋 Changelog Summary: 2026-06-26 to 2026-07-03](https://github.com/DSACMS/super-changelog/pull/114)
- [Weekly Changelog Summary: 2025-10-24 to 2025-10-31](https://github.com/DSACMS/super-changelog/pull/113)
- [Update code.json](https://github.com/DSACMS/super-changelog/pull/112)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 22 commits, 29 pulls, 1 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 9 commits, 17 pulls, 8 issues
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 7 commits, 15 pulls, 6 issues
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 9 commits, 12 pulls, 1 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 3 commits, 16 pulls
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 3 commits, 4 pulls, 1 issues
- **[medicare_monthly_enrollment_dashboard](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard)**: 5 commits, 2 pulls, 1 issues
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 4 commits, 2 pulls
- **[testing-repository](https://github.com/DSACMS/testing-repository)**: 4 commits, 8 issues
- **[emmy-agent-marketplace](https://github.com/DSACMS/emmy-agent-marketplace)**: 1 commits, 3 pulls
- *...and 50 more repositories*

---
*🤖 Generated automatically on 2026-07-06T18:53:43.645441+00:00*