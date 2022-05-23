## [v4.0.0](https://github.com/puppetlabs/device_manager/tree/v3.1.0) (2022-05-23)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/v3.1.0...v3.1.0)

### Changed

- \(maint\) Remove support for Puppet 5 [\#91](https://github.com/puppetlabs/device_manager/pull/91) ([david22swan](https://github.com/david22swan))
- OS support updated to match the current standard for supported modules [\#86](https://github.com/puppetlabs/device_manager/pull/86) ([tkishel](https://github.com/tkishel))

### Added

- Update for Puppet 7 compability [\#86](https://github.com/puppetlabs/device_manager/pull/86) ([tkishel](https://github.com/tkishel))

## [v3.1.0](https://github.com/puppetlabs/device_manager/tree/v3.1.0) (2020-12-02)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/v3.0.1...v3.1.0)

### Added

- \(MODULES-9191\) support a non-root user [\#46](https://github.com/puppetlabs/device_manager/pull/46) ([tkishel](https://github.com/tkishel))

### Fixed

- run\_user and run\_group for device\_manager::devices [\#76](https://github.com/puppetlabs/device_manager/pull/76) ([bFekete](https://github.com/bFekete))
- \(maint\) confine and variables and ensure [\#74](https://github.com/puppetlabs/device_manager/pull/74) ([tkishel](https://github.com/tkishel))
- Manage devices' config folder [\#73](https://github.com/puppetlabs/device_manager/pull/73) ([JonasVerhofste](https://github.com/JonasVerhofste))
- Do not require aio\_agent\_version to be present [\#66](https://github.com/puppetlabs/device_manager/pull/66) ([fizmat](https://github.com/fizmat))
- \(MODULES-9628, PUP-8736\) don't purge device certificates on new puppet versions \(3.0.1 hotfix\) [\#58](https://github.com/puppetlabs/device_manager/pull/58) ([DavidS](https://github.com/DavidS))

## [v3.0.1](https://github.com/puppetlabs/device_manager/tree/v3.0.1) (2019-08-14)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/v3.0.0...v3.0.1)

### Added

- \(MODULES-9191\) implement configurable run\_user per device [\#64](https://github.com/puppetlabs/device_manager/pull/64) ([tkishel](https://github.com/tkishel))

## [v3.0.0](https://github.com/puppetlabs/device_manager/tree/v3.0.0) (2019-06-11)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/v2.7.1...v3.0.0)

### Fixed

- \(maint\) Relax version requirement for concat [\#49](https://github.com/puppetlabs/device_manager/pull/49) ([DavidS](https://github.com/DavidS))
- \(FM-8238, FM-8137\) Dependency fixes [\#48](https://github.com/puppetlabs/device_manager/pull/48) ([DavidS](https://github.com/DavidS))

## [v2.7.1](https://github.com/puppetlabs/device_manager/tree/v2.7.1) (2019-04-10)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/2.7.0...v2.7.1)

### Fixed

- \(maint\) removing the aio\_agent\_version fact check [\#41](https://github.com/puppetlabs/device_manager/pull/41) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- Tighter version bounding on puppetlabs/hocon [\#40](https://github.com/puppetlabs/device_manager/pull/40) ([rnelson0](https://github.com/rnelson0))
- Fix build issues on Jenkins [\#39](https://github.com/puppetlabs/device_manager/pull/39) ([da-ar](https://github.com/da-ar))

## [2.7.0](https://github.com/puppetlabs/device_manager/tree/2.7.0) (2018-10-02)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/2.6.0...2.7.0)

### Added

- \(FM-7230\) Specify defaults for multiple devices when using Hiera or Classifier [\#24](https://github.com/puppetlabs/device_manager/pull/24) ([tkishel](https://github.com/tkishel))
- \(FM-7148\) logdest scheduled runs to system log [\#16](https://github.com/puppetlabs/device_manager/pull/16) ([tkishel](https://github.com/tkishel))
- \(FM 7115\) return device certificates with task results [\#15](https://github.com/puppetlabs/device_manager/pull/15) ([tkishel](https://github.com/tkishel))

### Fixed

- CVE-2018-11748 \(FM-7258\) Update device config file permissions [\#32](https://github.com/puppetlabs/device_manager/pull/32) ([willmeek](https://github.com/willmeek))
- \(FM-7383\) allow device manager to work with Puppet 6 [\#27](https://github.com/puppetlabs/device_manager/pull/27) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- Pass through credentials from device\_manager::devices [\#21](https://github.com/puppetlabs/device_manager/pull/21) ([DavidS](https://github.com/DavidS))
- \(FM-7114\) purge conf devices directory [\#18](https://github.com/puppetlabs/device_manager/pull/18) ([tkishel](https://github.com/tkishel))

## [2.6.0](https://github.com/puppetlabs/device_manager/tree/2.6.0) (2018-05-31)

[Full Changelog](https://github.com/puppetlabs/device_manager/compare/2.5.0...2.6.0)

### Added

- \(MODULES-7100\) Update Readme documentation [\#9](https://github.com/puppetlabs/device_manager/pull/9) ([willmeek](https://github.com/willmeek))
- \(MODULES-7101\) rename scheduled task [\#8](https://github.com/puppetlabs/device_manager/pull/8) ([tkishel](https://github.com/tkishel))
- \(MODULES-7101\) adding the first acceptance tests [\#5](https://github.com/puppetlabs/device_manager/pull/5) ([tphoney](https://github.com/tphoney))

### Fixed

- \(MODULES-7051\) use to\_json instead of hocon\_setting [\#10](https://github.com/puppetlabs/device_manager/pull/10) ([tkishel](https://github.com/tkishel))
- \(MODULES-7051\) remove default node from credentials configuration [\#7](https://github.com/puppetlabs/device_manager/pull/7) ([tkishel](https://github.com/tkishel))

## 2.5.0

- Add include_module parameter and functionality.
- Prepare for adoption.

## 2.4.7

- Clarify documentation.

## 2.4.6

- Allow specifying devices via a classifier and/or Hiera.
- Support the Puppet Resource API and its credential files.

## 2.4.5

- PDK 1.5

## 2.4.4

- Add classification guard.

## 2.4.3

- Add LICENSE to accommodate users who need it in a top-level file.
- Update Puppet documentation URLs.

## 2.4.2

- Minor changes.

## 2.4.1

- Namespace custom facts.
- Prefer os.family fact over legacy osfamily fact.

## 2.4.0

- Specify '--verbose' by default.
- Deprecate 'run_via_exec' parameter

## 2.3.7

- Use ensure_resource to prevent duplicate resource for facter/facts.s path (credit: Kris Amundson).

## 2.3.6

- Replace reference to run_via_cron with run_interval (credit: Kris Amundson).

## 2.3.5

- Minor changes.

## 2.3.4

- Sanitize

## 2.3.3

- Rewrite task using methods
- Update run_interval function

## 2.3.1

- Typo in README.
- Tune run_interval.

## 2.3.0

- Restore run_interval parameter for cron and scheduled_task.

## 2.2.0

- Abstract cron and scheduled_task.
- Correct fact location on Windows.

## 2.1.2

- Added documentation.
- Tuneup cron, and prepare a scheduled_task.

## 2.1.1

Minor changes.

- Cleanup parameter handling.

## 2.1.0

Parameter changes.

- Rename the autorun parameter to run_via_exec.
- Implement a beta run_via_cron parameter.

## 2.0.1

- Fix anchor in README.
- Simplify run.

### Summary

Minor changes.

## 2.0.0

- Add support for tasks.
- Rename the run parameter to autorun.
- Change structured fact format from array to hash.
- Fully qualify the path to the test command.
- Normalize the waitforcert and user parameters of the puppet device command.

### Summary

This release adds support for tasks, and uses Puppet Development Kit (PDK).

## 1.1.1

### Summary

Minor changes.

#### Changed

- Test version to choose between hiera_hash and lookup.
- Use show_diff=false in concat to not log changes to device.conf.

## 1.1.0

### Summary

Minor changes.

#### Changed

- Use hiera_hash to improve compatibility.
- Use iteration instead of create_resource to improve readability.

## 1.0.9

### Summary

This release allows users to declare devices as a hash of hashes in Hiera.

#### Features/Improvements

- Implement a CHANGELOG.
- Adds support for declaring devices in Hiera.


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
