# 📋 Weekly Changelog
**Period**: 2026-07-31 to 2026-08-07

## 📊 Quick Stats
- **Active Repositories**: 67/173
- 📦 **Commits**: 84 | 🔀 **Pull Requests**: 175 | ❗️ **Issues**: 78

## ✅ Added
*New features and additions*

### .github
- [Add all live pages under dsacms.github.io domain to org profile README](https://github.com/DSACMS/.github/pull/14)

### Esmd-fhir-client-python
- **Shared Utilities Package**: Created `esmd_shared` package to eliminate code duplication
- Enhanced `EsmdAuthClient` with token caching, better error handling, and type hints
- Improved `ConfigUtility` with environment variable support and validation
- Advanced `logger` module with file rotation and configurable formatting
- **Comprehensive Documentation**: Complete README.md with installation, usage, and API documentation
- *...and 19 more*

### automated-codejson-generator
- [Add end-to-end testing pipeline](https://github.com/DSACMS/automated-codejson-generator/pull/134)

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

### medicare_monthly_enrollment_dashboard
- [Format source with prettier, add format scripts, fix eslint and jest config](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/42)

### repo-scaffolder
- [Added AI usage section to tier 2, 3, and 4 PR templates](https://github.com/DSACMS/repo-scaffolder/pull/398)
- [Added AI usage section to PR template](https://github.com/DSACMS/repo-scaffolder/pull/396)

### super-changelog
- Initial release of super-changelog
- Weekly pipeline (`run_weekly.py`) producing full and condensed summary PRs
- Historical reporting with a custom date range
- Org-agnostic design &mdash; works with any public GitHub organization
- JSON data output for downstream dashboards and reporting
- *...and 1 more*

### year-in-review
- [Added metrics-data.js to load json data into onto the website](https://github.com/DSACMS/year-in-review/pull/1)

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

### iv-cbv-payroll
- [fix: patch Dockerfile for OS-level CVEs flagged by Trivy/Anchore](https://github.com/DSACMS/iv-cbv-payroll/pull/1944)

### medicare_monthly_enrollment_dashboard
- [Refactored CSS files and JS files for easier code maintenance, bug sweep](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard/pull/41)

### mint-app
- [[MINT-3838] Multi Fixes](https://github.com/CMS-Enterprise/mint-app/pull/2441)

### ztmf-ui
- [Code freeze batch: approved frontend fixes (OpDiv scope, system edit required fields, confirm guidance)](https://github.com/CMS-Enterprise/ztmf-ui/pull/674)

## 🔧 Changed
*Updates and modifications*

### Esmd-fhir-client-python
- **Type Hints**: Added comprehensive type annotations throughout shared utilities
- **Error Handling**: Standardized and improved error handling patterns
- **Logging**: Enhanced logging with structured output and rotation
- **Code Structure**: Better separation of concerns and modularity
- **Dependency Security**: Pinned versions to prevent security vulnerabilities
- *...and 7 more*

### MedicareClaimsPricerSource
- [Update README.md](https://github.com/DSACMS/MedicareClaimsPricerSource/pull/4)

### batcave-workflow-engine
- Upgrade omnibus base image to v1.5.1
- Move existing CLI package to v0
- Task Run pattern
- refactored CLI for readability and maintenance
- upgraded to go 1.22.0
- *...and 19 more*

### code-book
- [improved formatting for the codebook txt](https://github.com/DSACMS/code-book/pull/5)

### power-platform-webres
- [Ppe 73/ux improvements](https://github.com/CMS-Enterprise/power-platform-webres/pull/34)

### super-changelog
- [Weekly Changelog Summary: 2026-07-03 to 2026-07-10](https://github.com/DSACMS/super-changelog/pull/130)
- [removed logic to only append repos with activity to changelog](https://github.com/DSACMS/super-changelog/pull/126)
- [Weekly Changelog Summary: 2026-05-28 to 2026-06-04](https://github.com/DSACMS/super-changelog/pull/124)

## 🗑️ Removed
*Deprecations and removals*

### mint-app
- [removed accidentally commited csv doc report](https://github.com/CMS-Enterprise/mint-app/pull/2442)

### power-platform-webres
- [removing a requirement that Edit Requests have to move the request to…](https://github.com/CMS-Enterprise/power-platform-webres/pull/35)

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

### year-in-review
- [code.json documentation](https://github.com/DSACMS/year-in-review/pull/2)

## 🚀 Active Repositories

- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 7 commits, 28 pulls, 28 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 9 commits, 25 pulls
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 8 commits, 24 pulls, 31 issues
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 5 commits, 15 pulls
- **[year-in-review](https://github.com/DSACMS/year-in-review)**: 13 commits, 2 pulls
- **[power-platform-webres](https://github.com/CMS-Enterprise/power-platform-webres)**: 12 commits, 2 pulls
- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 3 commits, 8 pulls, 2 issues
- **[repo-scaffolder](https://github.com/DSACMS/repo-scaffolder)**: 4 commits, 4 pulls, 1 issues
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 2 commits, 5 pulls, 4 issues
- **[medicare_monthly_enrollment_dashboard](https://github.com/DSACMS/medicare_monthly_enrollment_dashboard)**: 4 commits, 3 pulls
- *...and 57 more repositories*

---
*🤖 Generated automatically on 2026-08-07T02:33:49.538656+00:00*