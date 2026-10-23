# 📋 Weekly Changelog
**Period**: 2026-10-16 to 2026-10-23

## 📊 Quick Stats
- **Active Repositories**: 19/179
- 📦 **Commits**: 72 | 🔀 **Pull Requests**: 216 | ❗️ **Issues**: 6

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

### libyears
- Scan direct npm production dependencies from the root `package.json`, using
- Scan npm and PyPI dependencies together, with repository-wide and
- Report source discovery failures separately from dependency-level
- Use shared verified HTTPS registry transport for PyPI and npm metadata
- Support resolved version snapshots as exact version evidence for declared
- *...and 1 more*

### share-it-act-lp
- [Metadata & FAQ: Add content on code.json fields that can be auto-generated](https://github.com/DSACMS/share-it-act-lp/pull/60)

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
- [fix(backend): build with Go 1.27.3 for the crypto/x509 revocation fix](https://github.com/CMS-Enterprise/ztmf/pull/619)

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

### fast-facts-2.0
- [Update code.json](https://github.com/DSACMS/fast-facts-2.0/pull/65)

### iv-cbv-payroll
- [FFS-4929: Update Activity Hub heading elements](https://github.com/DSACMS/iv-cbv-payroll/pull/2222)
- [Update AI options](https://github.com/DSACMS/iv-cbv-payroll/pull/2221)

### libyears
- Upgrade JSON output from schema v2 to schema v3. This is an intentional
- Improve human-readable measurement diagnostics while keeping the JSON

### share-it-act-lp
- [Docs: Content Updates to Exemptions, FAQs, and Metadata Schema Tables](https://github.com/DSACMS/share-it-act-lp/pull/61)
- [Update code.json](https://github.com/DSACMS/share-it-act-lp/pull/59)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 36 commits, 81 pulls, 2 issues
- **[share-it-act-lp](https://github.com/DSACMS/share-it-act-lp)**: 7 commits, 51 pulls
- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 4 commits, 34 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 10 commits, 26 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 1 commits, 9 pulls
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 7 commits, 2 pulls, 4 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 2 commits, 4 pulls
- **[gov-codejson-mcp](https://github.com/DSACMS/gov-codejson-mcp)**: 3 commits
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 2 pulls
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 2 pulls
- *...and 9 more repositories*

---
*🤖 Generated automatically on 2026-10-23T03:24:04.917042+00:00*