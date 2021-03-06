# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.0.0"></a>
# [2.0.0](https://github.com/stellarguard/multisig-utils/compare/v1.1.0...v2.0.0) (2020-11-23)


### Features

* upgrade to stellar-sdk 7.0.0 ([95a2583](https://github.com/stellarguard/multisig-utils/commit/95a2583))


### BREAKING CHANGES

* Requires a peerDependency of stellar-sdk ^7.0.0



<a name="1.1.0"></a>
# [1.1.0](https://github.com/stellarguard/multisig-utils/compare/v1.0.0...v1.1.0) (2020-02-10)


### Features

* 🎸 Update to stellar sdk 4.0.0 ([3a4bb45](https://github.com/stellarguard/multisig-utils/commit/3a4bb45))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/stellarguard/multisig-utils/compare/v0.4.1...v1.0.0) (2019-05-16)


### Chores

* **dependencies:** Ugrade to stellar-sdk 1.0 ([474c373](https://github.com/stellarguard/multisig-utils/commit/474c373))


### BREAKING CHANGES

* **dependencies:** Removes @types/stellar-sdk as a dependency. You must use the types directly from stellar-sdk



<a name="0.4.1"></a>
## [0.4.1](https://github.com/stellarguard/multisig-utils/compare/v0.4.0...v0.4.1) (2018-11-08)


### Bug Fixes

* Drop HAL for multisig server response and use "statusHref" instead ([926e6b8](https://github.com/stellarguard/multisig-utils/commit/926e6b8))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/stellarguard/multisig-utils/compare/v0.3.2...v0.4.0) (2018-11-02)


### Bug Fixes

* submitToMultisigServer uses JSON body ([2ce15b0](https://github.com/stellarguard/multisig-utils/commit/2ce15b0))


### Features

* Add getSigners method ([0e97566](https://github.com/stellarguard/multisig-utils/commit/0e97566))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/stellarguard/multisig-utils/compare/v0.3.1...v0.3.2) (2018-10-31)


### Bug Fixes

* Use multisig.domain instead of multisig_domain to align with namespaces proposal ([72146bb](https://github.com/stellarguard/multisig-utils/commit/72146bb))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/stellarguard/multisig-utils/compare/v0.3.0...v0.3.1) (2018-10-29)



<a name="0.3.0"></a>
# [0.3.0](https://github.com/stellarguard/multisig-utils/compare/v0.2.6...v0.3.0) (2018-10-29)


### Bug Fixes

* Rename data.multisig_server to multisig_domain ([88e600d](https://github.com/stellarguard/multisig-utils/commit/88e600d))


### Features

* Use SEP-0007 stellar uris when submitting to multisig endpoints ([760d604](https://github.com/stellarguard/multisig-utils/commit/760d604))


### Performance Improvements

* Check signature hints before doing full verify. ([da16510](https://github.com/stellarguard/multisig-utils/commit/da16510))



<a name="0.2.6"></a>
## [0.2.6](https://github.com/stellarguard/multisig-utils/compare/v0.2.5...v0.2.6) (2018-10-19)



<a name="0.2.5"></a>
## [0.2.5](https://github.com/stellarguard/multisig-utils/compare/v0.2.4...v0.2.5) (2018-10-19)



<a name="0.2.4"></a>
## [0.2.4](https://github.com/stellarguard/multisig-utils/compare/v0.2.3...v0.2.4) (2018-10-19)


### Bug Fixes

* MultisigServerResponse type should be looser. ([7929fe3](https://github.com/stellarguard/multisig-utils/commit/7929fe3))



<a name="0.2.3"></a>
## [0.2.3](https://github.com/stellarguard/multisig-utils/compare/v0.2.2...v0.2.3) (2018-10-18)


### Bug Fixes

* Submit transaction as application/x-www-form-urlencoded ([c7fcb2f](https://github.com/stellarguard/multisig-utils/commit/c7fcb2f))



<a name="0.2.2"></a>
## [0.2.2](https://github.com/stellarguard/multisig-utils/compare/v0.2.1...v0.2.2) (2018-10-18)


### Bug Fixes

* Use `tx` instead of `xdr` when submitting to multisig endpoint. ([79a97eb](https://github.com/stellarguard/multisig-utils/commit/79a97eb))



<a name="0.2.1"></a>
## [0.2.1](https://github.com/stellarguard/multisig-utils/compare/v0.2.0...v0.2.1) (2018-10-16)


### Bug Fixes

* isStellarGuard is actually just "stellarGuard" in the response ([2906b39](https://github.com/stellarguard/multisig-utils/commit/2906b39))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/stellarguard/multisig-utils/compare/v0.1.0...v0.2.0) (2018-10-16)


### Features

* needsMoreSignatures lets you pass in a list of cached accounts to use ([e278ff7](https://github.com/stellarguard/multisig-utils/commit/e278ff7))



<a name="0.1.0"></a>
# 0.1.0 (2018-10-16)


### Features

* Add more tests and prepare for initial release. ([a67e5d3](https://github.com/stellarguard/multisig-utils/commit/a67e5d3))
