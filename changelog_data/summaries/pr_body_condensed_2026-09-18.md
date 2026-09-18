# 📋 Weekly Changelog
**Period**: 2026-09-11 to 2026-09-18

## 📊 Quick Stats
- **Active Repositories**: 27/176
- 📦 **Commits**: 63 | 🔀 **Pull Requests**: 236 | ❗️ **Issues**: 13

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

### codejson-generator
- [Adding Local AI Generation](https://github.com/DSACMS/codejson-generator/pull/141)

### fdsh-utils
- [[FFS-4823] Add labels of which is REST vs SOAP and experiment with adding a SOAP schema](https://github.com/DSACMS/fdsh-utils/pull/28)

### iv-cbv-payroll
- [FFS-4804: Add month selection page to Emmy CE Employment flow](https://github.com/DSACMS/iv-cbv-payroll/pull/2071)

### mint-app
- [[MINT-3737] add waivers to DB](https://github.com/CMS-Enterprise/mint-app/pull/2532)
- [[MINT-3844] Adding OA Presentation to Tasks Section](https://github.com/CMS-Enterprise/mint-app/pull/2531)

### ospo-guide
- [Outbound: Add new section on AI Action Plan to AI at CMS guide](https://github.com/DSACMS/ospo-guide/pull/143)
- [Outbound: Add CMS AI CCI snippet to AI Guide](https://github.com/DSACMS/ospo-guide/pull/142)

### repo-scaffolder
- [Templates & Outbound Checklists: Add PRA, 508, and Plain Language Policy Guidance](https://github.com/DSACMS/repo-scaffolder/pull/406)

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

### codejson-generator
- [AI Fix for Production](https://github.com/DSACMS/codejson-generator/pull/145)

### iv-cbv-payroll
- [fix: app/analytics/requirements.txt to reduce vulnerabilities](https://github.com/DSACMS/iv-cbv-payroll/pull/2072)

### ztmf
- [fix(#587): reject duplicate system acronyms within an OpDiv](https://github.com/CMS-Enterprise/ztmf/pull/589)
- [fix(misc#384): scope the data-call export to the catalog the dashboard scores](https://github.com/CMS-Enterprise/ztmf/pull/588)

### ztmf-ui
- [fix(ui#714): clear the frostfall 508 findings and enforce the gate](https://github.com/CMS-Enterprise/ztmf-ui/pull/737)

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

### power-platform-webres
- [PPE-92 Updating Local Tools](https://github.com/CMS-Enterprise/power-platform-webres/pull/45)

### repo-scaffolder
- [Outbound Checklists: Update with AI Policy Guidance and Recommended Practices](https://github.com/DSACMS/repo-scaffolder/pull/408)

### super-changelog
- [📋 Changelog Summary: 2026-09-04 to 2026-09-11](https://github.com/DSACMS/super-changelog/pull/163)
- [Weekly Changelog Summary: 2026-03-27 to 2026-04-03](https://github.com/DSACMS/super-changelog/pull/162)
- [Weekly Changelog Summary: 2026-05-28 to 2026-06-04](https://github.com/DSACMS/super-changelog/pull/161)

## 🗑️ Removed
*Deprecations and removals*

### ztmf
- [chore(rollover): remove the FY2026 hard-code, carry its dedup forward (ztmf#502)](https://github.com/CMS-Enterprise/ztmf/pull/590)

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

- **[super-changelog](https://github.com/DSACMS/super-changelog)**: 7 commits, 136 pulls
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 17 commits, 27 pulls, 1 issues
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 3 commits, 21 pulls
- **[ztmf](https://github.com/CMS-Enterprise/ztmf)**: 7 commits, 9 pulls, 4 issues
- **[ztmf-ui](https://github.com/CMS-Enterprise/ztmf-ui)**: 6 commits, 9 pulls, 6 issues
- **[codejson-generator](https://github.com/DSACMS/codejson-generator)**: 4 commits, 5 pulls
- **[fast-facts-2.0](https://github.com/DSACMS/fast-facts-2.0)**: 7 commits, 2 pulls
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 4 commits, 3 pulls
- **[repo-scaffolder](https://github.com/DSACMS/repo-scaffolder)**: 3 commits, 3 pulls
- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 5 pulls
- *...and 17 more repositories*

---
*🤖 Generated automatically on 2026-09-18T03:12:49.420094+00:00*