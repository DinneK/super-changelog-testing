# 📋 Weekly Changelog
**Period**: 2026-08-21 to 2026-08-28

## 📊 Quick Stats
- **Active Repositories**: 36/176
- 📦 **Commits**: 74 | 🔀 **Pull Requests**: 306 | ❗️ **Issues**: 28

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
- [Auto-discover and verify new gov dependencie](https://github.com/DSACMS/automated-codejson-generator/pull/136)

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

### caseworkerportal
- [Documentation: Add Archive Notice to README](https://github.com/DSACMS/caseworkerportal/pull/19)

### codejson-core
- [Sachin/adding draft mode](https://github.com/DSACMS/codejson-core/pull/1)

### income-reporting-playbook
- [Documentation: Add Archive Notice to README](https://github.com/DSACMS/income-reporting-playbook/pull/20)
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/income-reporting-playbook/pull/17)

### iv-delivery
- [Documentation: Add Archive Notice to README](https://github.com/DSACMS/iv-delivery/pull/6)
- [Metadata: Add code.json](https://github.com/DSACMS/iv-delivery/pull/2)

### iv-doc-uploader
- [Documentation: Add Archive Notice to README](https://github.com/DSACMS/iv-doc-uploader/pull/43)
- [Archival: Add workflow to archive repository](https://github.com/DSACMS/iv-doc-uploader/pull/40)

### iv-verify
- [Documentation: Add Archive Notice to README](https://github.com/DSACMS/iv-verify/pull/104)

### mint-app
- [added another error or warn log](https://github.com/CMS-Enterprise/mint-app/pull/2483)

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

### fast-facts-2.0
- [fix: rename tab for clarity](https://github.com/DSACMS/fast-facts-2.0/pull/57)

### iv-cbv-payroll
- [FFS-3788: Investigate and fix undefined method 'identity' for an instance of CbvFlow](https://github.com/DSACMS/iv-cbv-payroll/pull/2009)

### repo-scaffolder
- [[Snyk] Fix for 8 vulnerabilities](https://github.com/DSACMS/repo-scaffolder/pull/379)

### web-form-template
- [Fix css dk](https://github.com/DSACMS/web-form-template/pull/5)

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

### caseworkerportal
- [Update code.json for archival](https://github.com/DSACMS/caseworkerportal/pull/18)

### income-reporting-playbook
- [Update code.json for archival](https://github.com/DSACMS/income-reporting-playbook/pull/19)

### iv-delivery
- [Update code.json for archival](https://github.com/DSACMS/iv-delivery/pull/5)

### iv-doc-uploader
- [Update code.json for archival](https://github.com/DSACMS/iv-doc-uploader/pull/42)

### iv-verify
- [Update code.json for archival](https://github.com/DSACMS/iv-verify/pull/103)

### mint-app
- [[MINT-3861] Update 2-pager content](https://github.com/CMS-Enterprise/mint-app/pull/2487)

### super-changelog
- [Weekly Changelog Summary: 2026-05-01 to 2026-05-08](https://github.com/DSACMS/super-changelog/pull/156)
- [📋 Changelog Summary: 2026-08-14 to 2026-08-21](https://github.com/DSACMS/super-changelog/pull/155)
- [Weekly Changelog Summary: 2026-07-24 to 2026-07-31](https://github.com/DSACMS/super-changelog/pull/154)

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

### fdsh-utils
- [docs: clean up and enhance Hub connection guide for external developers](https://github.com/DSACMS/fdsh-utils/pull/13)

## 🚀 Active Repositories

- **[repo-scaffolder](https://github.com/DSACMS/repo-scaffolder)**: 4 commits, 99 pulls
- **[iv-cbv-payroll](https://github.com/DSACMS/iv-cbv-payroll)**: 14 commits, 17 pulls
- **[mint-app](https://github.com/CMS-Enterprise/mint-app)**: 7 commits, 22 pulls
- **[iv-verify](https://github.com/DSACMS/iv-verify)**: 2 commits, 26 pulls, 2 issues
- **[iv-doc-uploader](https://github.com/DSACMS/iv-doc-uploader)**: 2 commits, 25 pulls, 1 issues
- **[automated-codejson-generator](https://github.com/DSACMS/automated-codejson-generator)**: 4 commits, 16 pulls, 1 issues
- **[ospo-guide](https://github.com/DSACMS/ospo-guide)**: 5 commits, 13 pulls
- **[caseworkerportal](https://github.com/DSACMS/caseworkerportal)**: 2 commits, 15 pulls, 1 issues
- **[income-reporting-playbook](https://github.com/DSACMS/income-reporting-playbook)**: 2 commits, 14 pulls, 2 issues
- **[emmy-app](https://github.com/CMS-Enterprise/emmy-app)**: 14 pulls, 1 issues
- *...and 26 more repositories*

---
*🤖 Generated automatically on 2026-08-28T09:32:59.875334+00:00*