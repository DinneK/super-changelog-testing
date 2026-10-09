# 📋 Weekly Changelog
**Period**: 2026-10-02 to 2026-10-09

## 📊 Quick Stats
- **Active Repositories**: 29/177
- 📦 **Commits**: 98 | 🔀 **Pull Requests**: 195 | ❗️ **Issues**: 6

## ✅ Added
*New features and additions*

### Esmd-fhir-client-python
- **Shared Utilities Package**: Created `esmd_shared` package to eliminate code duplication
- Enhanced `EsmdAuthClient` with token caching, better error handling, and type hints
- Improved `ConfigUtility` with environment variable support and validation
- Advanced `logger` module with file rotation and configurable formatting
- **Comprehensive Documentation**: Complete README.md with installation, usage, and API documentation
- *...and 19 more*

### automated-codejson-generator
- [Adding Local AI Generation](https://github.com/DSACMS/automated-codejson-generator/pull/156)

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

### fdsh-utils
- [ [FFS-4823] add tracking tags](https://github.com/DSACMS/fdsh-utils/pull/31)
- [ [FFS-4823] add analytics](https://github.com/DSACMS/fdsh-utils/pull/30)

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

### mint-app
- [[NOREF] Fix broken link](https://github.com/CMS-Enterprise/mint-app/pull/2585)

### ztmf-ui
- [fix(ui#750): state the email length rule and stop claiming sends that did not happen](https://github.com/CMS-Enterprise/ztmf-ui/pull/752)

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
- [Update code.json](https://github.com/DSACMS/archival-identifier/pull/26)

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### codejson-generator
- [docs(contributor): contributors readme action update](https://github.com/DSACMS/codejson-generator/pull/150)
- [Update code.json](https://github.com/DSACMS/codejson-generator/pull/149)

### iv-cbv-payroll
- [FFS-4867: Update Education self-attestation flow school info page](https://github.com/DSACMS/iv-cbv-payroll/pull/2153)
- [Bump the pip group across 1 directory with 3 updates](https://github.com/DSACMS/iv-cbv-payroll/pull/2152)

### ospo-guide
- [Update code.json](https://github.com/DSACMS/ospo-guide/pull/146)

### super-changelog
- [Weekly Changelog Summary: 2026-02-20 to 2026-02-27](https://github.com/DSACMS/super-changelog/pull/169)
- [📋 Changelog Summary: 2026-09-25 to 2026-10-02](https://github.com/DSACMS/super-changelog/pull/170)
- [Update code.json](https://github.com/DSACMS/super-changelog/pull/168)

### ztmf
- [perf(misc#426): persist scores.last_updated_at and index scores by data call](https://github.com/CMS-Enterprise/ztmf/pull/609)

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

### ospo-guide
- [Expand plain language documentation with best practices](https://github.com/DSACMS/ospo-guide/pull/127)

## 🚀 Active Repositories

- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 16 commits, 47 pulls
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 25 commits, 33 pulls
- **[codejson-generator](https://github.com/DSACMS/codejson-generator)**: 3 commits, 46 pulls, 1 issues
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 9 commits, 15 pulls
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 8 commits, 7 pulls
- **[eng-cop-scheduler](https://github.com/DSACMS/eng-cop-scheduler)**: 11 commits, 1 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 3 commits, 8 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 4 commits, 7 pulls, 1 issues
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 2 commits, 7 pulls
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 3 commits, 4 pulls, 3 issues
- *...and 19 more repositories*

---
*🤖 Generated automatically on 2026-10-09T04:35:15.405683+00:00*