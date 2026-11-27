# 📋 Weekly Changelog
**Period**: 2026-11-20 to 2026-11-27

## 📊 Quick Stats
- **Active Repositories**: 18/182
- 📦 **Commits**: 114 | 🔀 **Pull Requests**: 92 | ❗️ **Issues**: 6

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
- Add an explicit extended SBOM metadata budget for larger local inventories,
- Measure a separate local CycloneDX JSON 1.5 SBOM inventory using supported exact
- Accept explicitly supplied, byte-bound Maven parent/BOM documents through
- Automatically report independent Maven Declared / Observed dependency-age views
- Automatically select qualified current NuGet repository project/lock snapshots
- *...and 12 more*

### mint-app
- [[NOREF] Add Approved ICIP Cypress coverage and TaskCard mutation tests](https://github.com/CMS-Enterprise/mint-app/pull/2676)

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

### easi-app
- [[NOREF] Fixing TRB assign lead modal submit not firing](https://github.com/CMS-Enterprise/easi-app/pull/3600)

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

### ztmf
- [fix(misc#415, misc#416): skip fork PRs and publish main's test image in order](https://github.com/CMS-Enterprise/ztmf/pull/652)

### ztmf-ui
- [fix(misc#416): publish ztmf_ui_tag one at a time from main's tip](https://github.com/CMS-Enterprise/ztmf-ui/pull/779)

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

### fast-facts-2.0
- [Update code.json](https://github.com/DSACMS/fast-facts-2.0/pull/68)

### libyears
- Keep ordinary directory reports focused on positively relevant ecosystems, with
- Document durable private storage for explicitly supplied approved CA bundles,
- Ordinary NuGet scans can date qualified selected versions against a disclosed
- Measure accepted NuGet project/lock snapshots with explicit package-specific
- Ordinary directory scans automatically attempt bounded NuGet project sources.
- *...and 2 more*

### ztmf
- [chore(ci): bump the github-actions group with 2 updates](https://github.com/CMS-Enterprise/ztmf/pull/653)

## 🗑️ Removed
*Deprecations and removals*

### ztmf-ui
- [Migrate ScoreDiffModal onto queries and delete its cache](https://github.com/CMS-Enterprise/ztmf-ui/pull/770)

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

### gov-codejson-mcp
- [doc: final README edits](https://github.com/DSACMS/gov-codejson-mcp/pull/27)
- [doc: final-inventory local-client check](https://github.com/DSACMS/gov-codejson-mcp/pull/26)
- [ci: verify Docker build and HTTP health](https://github.com/DSACMS/gov-codejson-mcp/pull/25)

## 🚀 Active Repositories

- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 24 commits, 31 pulls, 1 issues
- **[gov-codejson-mcp](https://github.com/DSACMS/gov-codejson-mcp)**: 23 commits, 11 pulls
- **[libyears](https://github.com/DSACMS/libyears)**: 27 commits
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 4 commits, 16 pulls
- **[easi-app](https://github.com/CMS-Enterprise/easi-app)**: 6 commits, 12 pulls
- **[indelegible](https://github.com/DSACMS/indelegible)**: 12 commits
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 4 commits, 8 pulls, 1 issues
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 8 commits, 3 pulls, 2 issues
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 3 commits, 6 pulls, 2 issues
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 2 pulls
- *...and 8 more repositories*

---
*🤖 Generated automatically on 2026-11-27T06:44:37.793164+00:00*