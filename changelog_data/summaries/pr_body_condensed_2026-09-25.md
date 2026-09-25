# 📋 Weekly Changelog
**Period**: 2026-09-18 to 2026-09-25

## 📊 Quick Stats
- **Active Repositories**: 23/176
- 📦 **Commits**: 85 | 🔀 **Pull Requests**: 137 | ❗️ **Issues**: 5

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
- [No ticket: add asset to allow PDF to render](https://github.com/DSACMS/iv-cbv-payroll/pull/2100)

### metrics
- [Add missing auto-changelog file](https://github.com/DSACMS/metrics/pull/441)

### repodive-tools
- [Add auto-changelog to tools](https://github.com/DSACMS/repodive-tools/pull/26)

### share-it-act-lp
- [Add auto-changelog to share-it](https://github.com/DSACMS/share-it-act-lp/pull/57)

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

### easi-app
- [Noref/quay minio image fix](https://github.com/CMS-Enterprise/easi-app/pull/3557)

### metrics-dash-backend-tools
- [Fix auto-changelog](https://github.com/DSACMS/metrics-dash-backend-tools/pull/10)

### ospo-guide
- [Fix checkbox indentation](https://github.com/DSACMS/ospo-guide/pull/145)

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
- [No ticket: update AI attestation template](https://github.com/DSACMS/iv-cbv-payroll/pull/2103)

### mint-app
- [changed to silo host for minIO](https://github.com/CMS-Enterprise/mint-app/pull/2551)

### ospo-guide
- [Improve formatting of post-activity usability survey](https://github.com/DSACMS/ospo-guide/pull/144)

### power-platform-webres
- [data changes to test fields that previously had no test data to migrate](https://github.com/CMS-Enterprise/power-platform-webres/pull/50)
- [Various Data Migration Improvements](https://github.com/CMS-Enterprise/power-platform-webres/pull/49)

### repodive-tools
- [Update code.json](https://github.com/DSACMS/repodive-tools/pull/25)

### share-it-act-lp
- [Update code.json](https://github.com/DSACMS/share-it-act-lp/pull/56)
- [Update code.json](https://github.com/DSACMS/share-it-act-lp/pull/55)

## 🗑️ Removed
*Deprecations and removals*

### mint-app
- [[NOREF] Removed Unused Packages and CRA Leftovers](https://github.com/CMS-Enterprise/mint-app/pull/2549)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 26 commits, 35 pulls, 1 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 10 commits, 25 pulls
- **[codejson-action-e2e](https://github.com/DSACMS/codejson-action-e2e)**: 20 commits, 10 pulls
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 14 pulls, 2 issues
- **[repodive-tools](https://github.com/DSACMS/repodive-tools)**: 3 commits, 10 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 4 commits, 8 pulls
- **[share-it-act-lp](https://github.com/DSACMS/share-it-act-lp)**: 7 commits, 4 pulls
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 5 commits, 2 pulls
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 7 pulls
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 3 commits, 2 pulls
- *...and 13 more repositories*

---
*🤖 Generated automatically on 2026-09-25T03:27:20.705942+00:00*