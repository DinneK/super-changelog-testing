# 📋 Weekly Changelog
**Period**: 2026-08-28 to 2026-09-04

## 📊 Quick Stats
- **Active Repositories**: 63/175
- 📦 **Commits**: 137 | 🔀 **Pull Requests**: 152 | ❗️ **Issues**: 22

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

### fdsh-utils
- [Adding bug and feature request templates](https://github.com/DSACMS/fdsh-utils/pull/18)
- [Add more FDSH connection examples](https://github.com/DSACMS/fdsh-utils/pull/16)

### ospo-guide
- [Resources: Moved usability testing guides to new usability-testing folder](https://github.com/DSACMS/ospo-guide/pull/139)
- [Adding usability testing guide and templates](https://github.com/DSACMS/ospo-guide/pull/138)

### ospo-utils
- [Add r package checks](https://github.com/DSACMS/ospo-utils/pull/1)

### power-platform-webres
- [Add Gitleaks Scanner](https://github.com/CMS-Enterprise/power-platform-webres/pull/44)
- [adding batch id bypass to the activity log plugins](https://github.com/CMS-Enterprise/power-platform-webres/pull/42)

### repo-sunsetter
- [Archival Checklist: Add repository owners tasks to checklist + other feedback](https://github.com/DSACMS/repo-sunsetter/pull/29)

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
- [Resources: Updated rest of usability testing templates to include front matter + markdown fixes](https://github.com/DSACMS/ospo-guide/pull/140)

### ztmf
- [fix(misc#356): let OpDiv admins write system attributes on systems in their OpDivs](https://github.com/CMS-Enterprise/ztmf/pull/574)

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
- [Update code.json](https://github.com/DSACMS/fast-facts-2.0/pull/58)

### fdsh-utils
- [Update code.json](https://github.com/DSACMS/fdsh-utils/pull/17)

### ztmf-ui
- [Improve test coverage for the largest views](https://github.com/CMS-Enterprise/ztmf-ui/pull/717)

## 🗑️ Removed
*Deprecations and removals*

### iv-cbv-payroll
- [FFS-4289 Remove chromedriver dependency](https://github.com/DSACMS/iv-cbv-payroll/pull/2030)

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

- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 20 commits, 28 pulls, 1 issues
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 31 commits, 4 pulls
- **[uswds](https://github.com/DSACMS/uswds)**: 34 commits
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 7 commits, 21 pulls
- **[power-platform-webres](https://github.com/CMS-Enterprise/power-platform-webres)**: 11 commits, 8 pulls
- **[fdsh-utils](https://github.com/DSACMS/fdsh-utils)**: 10 commits, 5 pulls, 3 issues
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 9 commits, 5 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 3 commits, 7 pulls, 7 issues
- **[repo-sunsetter](https://github.com/DSACMS/repo-sunsetter)**: 6 commits, 2 pulls
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 2 commits, 6 pulls, 4 issues
- *...and 53 more repositories*

---
*🤖 Generated automatically on 2026-09-04T02:56:01.827066+00:00*