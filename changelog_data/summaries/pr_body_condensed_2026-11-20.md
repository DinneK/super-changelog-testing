# 📋 Weekly Changelog
**Period**: 2026-11-13 to 2026-11-20

## 📊 Quick Stats
- **Active Repositories**: 19/181
- 📦 **Commits**: 168 | 🔀 **Pull Requests**: 175 | ❗️ **Issues**: 22

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

### emmy-app
- [Add seasonal worker guidance accordion (FFS-4969)](https://github.com/CMS-Enterprise/emmy-app/pull/116)

### esmd-ext-fhir-client-python
- **Shared Utilities Package**: Created `esmd_shared` package to eliminate code duplication
- Enhanced `EsmdAuthClient` with token caching, better error handling, and type hints
- Improved `ConfigUtility` with environment variable support and validation
- Advanced `logger` module with file rotation and configurable formatting
- **Comprehensive Documentation**: Complete README.md with installation, usage, and API documentation
- *...and 19 more*

### libyears
- Accept explicitly supplied, byte-bound Maven parent/BOM documents through
- Automatically report independent Maven Declared / Observed dependency-age views
- Automatically select qualified current NuGet repository project/lock snapshots
- Accept an explicitly bound resolved NuGet snapshot as a population fallback when
- Accept explicit per-project supplier witnesses with repeatable
- *...and 10 more*

### mint-app
- [[NOREF] Add Add Final ICIP document type](https://github.com/CMS-Enterprise/mint-app/pull/2670)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

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
- Keep every retained unmeasurable Maven Declared occurrence individually visible
- Align ordinary Maven Declared measurements in a module-qualified table with
- Align human-readable dependency tables using the displayed headers and values,

### super-changelog
- [Fix stale merged prs](https://github.com/DSACMS/super-changelog/pull/186)
- [Fix full summary filename mismatch and stale fallback](https://github.com/DSACMS/super-changelog/pull/185)

### ztmf
- [fix(misc#350): narrow the GitHub OIDC deploy role trust per account](https://github.com/CMS-Enterprise/ztmf/pull/651)
- [fix(misc#421): stop the pr-env reaper when an AWS list call fails](https://github.com/CMS-Enterprise/ztmf/pull/648)

### ztmf-ui
- [feat: frostfall v1.6.1 keyboard audit, with the focus fixes it found](https://github.com/CMS-Enterprise/ztmf-ui/pull/776)
- [fix(misc#439): label each radar tooltip row with its own data call](https://github.com/CMS-Enterprise/ztmf-ui/pull/775)

## 🔧 Changed
*Updates and modifications*

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### emmy-app
- [FFS-5103 Update Education Review page to surface enrollment certification status and self-attested labels](https://github.com/CMS-Enterprise/emmy-app/pull/117)

### esmd-ext-fhir-client-python
- **Type Hints**: Added comprehensive type annotations throughout shared utilities
- **Error Handling**: Standardized and improved error handling patterns
- **Logging**: Enhanced logging with structured output and rotation
- **Code Structure**: Better separation of concerns and modularity
- **Dependency Security**: Pinned versions to prevent security vulnerabilities
- *...and 7 more*

### iv-cbv-payroll
- [1092: Summary View Updates](https://github.com/DSACMS/iv-cbv-payroll/pull/105)

### libyears
- Keep ordinary directory reports focused on positively relevant ecosystems, with
- Document durable private storage for explicitly supplied approved CA bundles,
- Ordinary NuGet scans can date qualified selected versions against a disclosed
- Measure accepted NuGet project/lock snapshots with explicit package-specific
- Ordinary directory scans automatically attempt bounded NuGet project sources.
- *...and 2 more*

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

## 📚 Documentation
*Documentation updates*

### ztmf
- [Apply artifact/documentation in the documentation request form](https://github.com/CMS-Enterprise/ztmf/pull/649)

### ztmf-ui
- [Apply artifact/documentation in the documentation request form](https://github.com/CMS-Enterprise/ztmf-ui/pull/778)

## 🚀 Active Repositories

- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 42 commits, 63 pulls, 1 issues
- **[gov-codejson-mcp](https://github.com/DSACMS/gov-codejson-mcp)**: 54 commits, 16 pulls
- **[libyears](https://github.com/DSACMS/libyears)**: 42 commits
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 8 commits, 22 pulls, 10 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 2 commits, 26 pulls, 1 issues
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 9 commits, 18 pulls, 10 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 3 commits, 15 pulls
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 2 commits, 5 pulls
- **[nist-decoder-ring-cisa](https://github.com/CMS-Enterprise/nist-decoder-ring-cisa)**: 1 commits, 4 pulls
- **[ohtp-join](https://github.com/DSACMS/ohtp-join)**: 3 commits
- *...and 9 more repositories*

---
*🤖 Generated automatically on 2026-11-20T05:43:54.421596+00:00*