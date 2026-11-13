# 📋 Weekly Changelog
**Period**: 2026-11-06 to 2026-11-13

## 📊 Quick Stats
- **Active Repositories**: 17/179
- 📦 **Commits**: 185 | 🔀 **Pull Requests**: 128 | ❗️ **Issues**: 5

## ✅ Added
*New features and additions*

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

### esmd-ext-fhir-client-python
- **Shared Utilities Package**: Created `esmd_shared` package to eliminate code duplication
- Enhanced `EsmdAuthClient` with token caching, better error handling, and type hints
- Improved `ConfigUtility` with environment variable support and validation
- Advanced `logger` module with file rotation and configurable formatting
- **Comprehensive Documentation**: Complete README.md with installation, usage, and API documentation
- *...and 19 more*

### libyears
- Automatically report independent Maven Declared / Observed dependency-age views
- Automatically select qualified current NuGet repository project/lock snapshots
- Accept an explicitly bound resolved NuGet snapshot as a population fallback when
- Accept explicit per-project supplier witnesses with repeatable
- Measure explicitly selected NuGet project snapshots with `--nuget-project`
- *...and 9 more*

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

### ztmf-ui
- [feat(misc#311): add Help page and sign-in help](https://github.com/CMS-Enterprise/ztmf-ui/pull/769)

## 🪲 Fixed
*Bug fixes and corrections*

### batcave-workflow-engine
- Viper config key names
- Specified CLI command parameters for custom input and output for easier unit testing in the future

### esmd-ext-fhir-client-python
- **Code Duplication**: Eliminated duplicate files across modules
- **Import Issues**: Fixed circular imports and dependency issues
- **Configuration Loading**: Improved config file discovery and error handling
- **Token Refresh**: Fixed token expiration and refresh logic
- **Package Structure**: Proper Python package hierarchy
- *...and 5 more*

### libyears
- Align human-readable dependency tables using the displayed headers and values,

### ospo-guide
- [Resources: Fixes for the Packaging Guides](https://github.com/DSACMS/ospo-guide/pull/153)

## 🔧 Changed
*Updates and modifications*

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### esmd-ext-fhir-client-python
- **Type Hints**: Added comprehensive type annotations throughout shared utilities
- **Error Handling**: Standardized and improved error handling patterns
- **Logging**: Enhanced logging with structured output and rotation
- **Code Structure**: Better separation of concerns and modularity
- **Dependency Security**: Pinned versions to prevent security vulnerabilities
- *...and 7 more*

### iv-cbv-payroll
- [FFS-5024: Update JSON for the NSC partially self-attested flow](https://github.com/DSACMS/iv-cbv-payroll/pull/2331)

### libyears
- Ordinary NuGet scans can date qualified selected versions against a disclosed
- Measure accepted NuGet project/lock snapshots with explicit package-specific
- Ordinary directory scans automatically attempt bounded NuGet project sources.
- Upgrade JSON output from schema v2 to schema v3. This is an intentional
- Improve human-readable measurement diagnostics while keeping the JSON

### mint-app
- [[MINT-3982] Update UI For Create Model Plan](https://github.com/CMS-Enterprise/mint-app/pull/2661)

### super-changelog
- [📋 Changelog Summary: 2026-10-30 to 2026-11-06](https://github.com/DSACMS/super-changelog/pull/184)
- [Weekly Changelog Summary: 2026-07-31 to 2026-08-07](https://github.com/DSACMS/super-changelog/pull/183)

## 🔒 Security
*Security improvements*

### esmd-ext-fhir-client-python
- **Dependency Pinning**: All dependencies are pinned to specific versions
- **Environment Variables**: Sensitive configuration moved to environment variables
- **Token Security**: Improved token handling and storage
- **Input Validation**: Better validation of configuration and input data
- **Token Caching**: Reduced authentication overhead with intelligent caching
- *...and 13 more*

### libyears
- Prevent pathological backtracking when classifying npm registry versions,

## 🚀 Active Repositories

- **[libyears](https://github.com/DSACMS/libyears)**: 100 commits
- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 35 commits, 33 pulls
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 25 commits, 37 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 7 commits, 21 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 6 commits, 10 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 4 commits, 9 pulls, 1 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 1 commits, 7 pulls, 4 issues
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 2 commits, 5 pulls
- **[gov-codejson-mcp](https://github.com/DSACMS/gov-codejson-mcp)**: 2 commits, 2 pulls
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 1 commits, 1 pulls
- *...and 7 more repositories*

---
*🤖 Generated automatically on 2026-11-13T05:05:07.766389+00:00*