# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [4.0.0-pre.3](https://github.com/feathersjs/feathers/compare/v4.0.0-pre.2...v4.0.0-pre.3) (2019-06-01)


### Bug Fixes

* Update dependencies and fix tests ([#1373](https://github.com/feathersjs/feathers/issues/1373)) ([d743a7f](https://github.com/feathersjs/feathers/commit/d743a7f))





# [4.0.0-pre.2](https://github.com/feathersjs/feathers/compare/v4.0.0-pre.1...v4.0.0-pre.2) (2019-05-15)

**Note:** Version bump only for package @feathersjs/adapter-commons





# [4.0.0-pre.1](https://github.com/feathersjs/feathers/compare/v4.0.0-pre.0...v4.0.0-pre.1) (2019-05-08)

**Note:** Version bump only for package @feathersjs/adapter-commons





# [4.0.0-pre.0](https://github.com/feathersjs/feathers/compare/v3.2.0-pre.1...v4.0.0-pre.0) (2019-04-21)


### Bug Fixes

* Update all dependencies to latest ([#1206](https://github.com/feathersjs/feathers/issues/1206)) ([e51e0f6](https://github.com/feathersjs/feathers/commit/e51e0f6))
* **adapter-commons:** Keep Symbols when filtering a query ([#1141](https://github.com/feathersjs/feathers/issues/1141)) ([c9f55d8](https://github.com/feathersjs/feathers/commit/c9f55d8))
* **chore:** Add .npmignore to adapter-commons ([8e129d8](https://github.com/feathersjs/feathers/commit/8e129d8))
* Add whitelist and filter support to common adapter service ([#1132](https://github.com/feathersjs/feathers/issues/1132)) ([df1daaa](https://github.com/feathersjs/feathers/commit/df1daaa))
* Fix AdapterService multi option when set to true ([#1134](https://github.com/feathersjs/feathers/issues/1134)) ([40402fc](https://github.com/feathersjs/feathers/commit/40402fc))
* Throw error in `filterQuery` when query parameter is unknown ([#1131](https://github.com/feathersjs/feathers/issues/1131)) ([cd1a183](https://github.com/feathersjs/feathers/commit/cd1a183))
* Update adapter common tests ([#1135](https://github.com/feathersjs/feathers/issues/1135)) ([8166dda](https://github.com/feathersjs/feathers/commit/8166dda))
* Update adapter common tests to check for falsy ([#1140](https://github.com/feathersjs/feathers/issues/1140)) ([2856722](https://github.com/feathersjs/feathers/commit/2856722))


### chore

* **package:** Move adapter tests into their own module ([#1164](https://github.com/feathersjs/feathers/issues/1164)) ([dcc1e6b](https://github.com/feathersjs/feathers/commit/dcc1e6b))


### Features

* Add TypeScript definitions ([#1275](https://github.com/feathersjs/feathers/issues/1275)) ([9dd6713](https://github.com/feathersjs/feathers/commit/9dd6713))
* Authentication v3 core server implementation ([#1205](https://github.com/feathersjs/feathers/issues/1205)) ([1bd7591](https://github.com/feathersjs/feathers/commit/1bd7591))
* Common database adapter utilities and test suite ([#1130](https://github.com/feathersjs/feathers/issues/1130)) ([17b3dc8](https://github.com/feathersjs/feathers/commit/17b3dc8))


### BREAKING CHANGES

* **package:** Removes adapter tests from @feathersjs/adapter-commons
* Move database adapter utilities from @feathersjs/commons into its own module





# [2.0.0](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.7...@feathersjs/adapter-commons@2.0.0) (2019-01-10)


### chore

* **package:** Move adapter tests into their own module ([#1164](https://github.com/feathersjs/feathers/issues/1164)) ([dcc1e6b](https://github.com/feathersjs/feathers/commit/dcc1e6b))


### BREAKING CHANGES

* **package:** Removes adapter tests from @feathersjs/adapter-commons





## [1.0.7](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.6...@feathersjs/adapter-commons@1.0.7) (2019-01-02)


### Bug Fixes

* **chore:** Add .npmignore to adapter-commons ([8e129d8](https://github.com/feathersjs/feathers/commit/8e129d8))





## [1.0.6](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.5...@feathersjs/adapter-commons@1.0.6) (2018-12-21)


### Bug Fixes

* **adapter-commons:** Keep Symbols when filtering a query ([#1141](https://github.com/feathersjs/feathers/issues/1141)) ([c9f55d8](https://github.com/feathersjs/feathers/commit/c9f55d8))





## [1.0.5](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.4...@feathersjs/adapter-commons@1.0.5) (2018-12-20)


### Bug Fixes

* Update adapter common tests to check for falsy ([#1140](https://github.com/feathersjs/feathers/issues/1140)) ([2856722](https://github.com/feathersjs/feathers/commit/2856722))





## [1.0.4](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.3...@feathersjs/adapter-commons@1.0.4) (2018-12-17)


### Bug Fixes

* Update adapter common tests ([#1135](https://github.com/feathersjs/feathers/issues/1135)) ([8166dda](https://github.com/feathersjs/feathers/commit/8166dda))





<a name="1.0.3"></a>
## [1.0.3](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.2...@feathersjs/adapter-commons@1.0.3) (2018-12-17)


### Bug Fixes

* Fix AdapterService multi option when set to true ([#1134](https://github.com/feathersjs/feathers/issues/1134)) ([40402fc](https://github.com/feathersjs/feathers/commit/40402fc))





<a name="1.0.2"></a>
## [1.0.2](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.1...@feathersjs/adapter-commons@1.0.2) (2018-12-17)


### Bug Fixes

* Add whitelist and filter support to common adapter service ([#1132](https://github.com/feathersjs/feathers/issues/1132)) ([df1daaa](https://github.com/feathersjs/feathers/commit/df1daaa))





<a name="1.0.1"></a>
## [1.0.1](https://github.com/feathersjs/feathers/compare/@feathersjs/adapter-commons@1.0.0...@feathersjs/adapter-commons@1.0.1) (2018-12-17)


### Bug Fixes

* Throw error in `filterQuery` when query parameter is unknown ([#1131](https://github.com/feathersjs/feathers/issues/1131)) ([cd1a183](https://github.com/feathersjs/feathers/commit/cd1a183))





<a name="1.0.0"></a>
# 1.0.0 (2018-12-16)


### Features

* Common database adapter utilities and test suite ([#1130](https://github.com/feathersjs/feathers/issues/1130)) ([17b3dc8](https://github.com/feathersjs/feathers/commit/17b3dc8))


### BREAKING CHANGES

* Move database adapter utilities from @feathersjs/commons into its own module
