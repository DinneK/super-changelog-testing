# 📋 Weekly Changelog
**Period**: 2026-09-25 to 2026-10-02

## 📊 Quick Stats
- **Active Repositories**: 64/175
- 📦 **Commits**: 68 | 🔀 **Pull Requests**: 166 | ❗️ **Issues**: 8

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
- [No ticket: Update PR template to include new test deployment job link](https://github.com/DSACMS/iv-cbv-payroll/pull/2127)
- [FFS-4850: Add Mixpanel events for employment month selection page](https://github.com/DSACMS/iv-cbv-payroll/pull/2126)

### metrics_frontend
- [Add missing changelog file](https://github.com/DSACMS/metrics_frontend/pull/9)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

### ztmf-ui
- [fix(systems): list OpDivs in the dashboard Add system modal and make the selector searchable](https://github.com/CMS-Enterprise/ztmf-ui/pull/743)

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
- [fix(scores): qualify functionOptionColumns so ?include=functionoption is not ambiguous](https://github.com/CMS-Enterprise/ztmf/pull/605)

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

### iv-cbv-payroll
- [update readme to keep testing flow up to date](https://github.com/DSACMS/iv-cbv-payroll/pull/2128)

### mint-app
- [Build(deps): bump the other group with 10 updates](https://github.com/CMS-Enterprise/mint-app/pull/2558)

### power-platform-webres
- [[PPE-52] Changes for reopening request to go back to step before close](https://github.com/CMS-Enterprise/power-platform-webres/pull/51)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 28 commits, 37 pulls, 1 issues
- **[codejson-action-e2e](https://github.com/DSACMS/codejson-action-e2e)**: 14 commits, 9 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 3 commits, 15 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 5 commits, 13 pulls, 3 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 6 commits, 11 pulls, 3 issues
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 2 commits, 8 pulls
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 8 pulls, 1 issues
- **[metrics](https://github.com/DSACMS/metrics)**: 3 commits, 3 pulls
- **[share-it-act-lp](https://github.com/DSACMS/share-it-act-lp)**: 2 commits, 2 pulls
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 2 commits, 2 pulls
- *...and 54 more repositories*

---
*🤖 Generated automatically on 2026-10-02T04:04:36.881089+00:00*