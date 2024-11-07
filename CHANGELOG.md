## [3.0.1](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/compare/v3.0.0...v3.0.1) (2024-11-07)


### Bug Fixes

* **mariadb:** Fix rootPassword template issue ([a745bf5](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/a745bf53d84f460bb87be89736277c435e42a851))

# [3.0.0](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/compare/v2.3.1...v3.0.0) (2024-11-06)


### Bug Fixes

* Added missing part to template keys ([ed8e26a](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/ed8e26a440491fa8edf8c35bd5eeb185a1c2112b))


### Features

* **opendesk-mariadb:** Added support for secrets ([501ffb1](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/501ffb192e03b5368eef0ef60dbde0184180ce7d))


### BREAKING CHANGES

* **opendesk-mariadb:** Environment variable MARIADB_ROOT_PASSWORD is now propagated with the
help of a Kubernetes secret instead of a plain value

## [2.3.1](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/compare/v2.3.0...v2.3.1) (2024-08-19)


### Bug Fixes

* User specific connection support. ([2b49809](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/2b49809b5697cfdd52b79f08ff2af6239eab89fc))

# [2.3.0](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/compare/v2.2.1...v2.3.0) (2024-08-15)


### Features

* **init:** Support for user based connection limits and password update. ([febcdd3](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/febcdd3e0dce8bf12254d15bab124d885bfe027f))

## [2.2.1](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/compare/v2.2.0...v2.2.1) (2023-12-21)


### Bug Fixes

* Update Signing and add GPG key ([b3c0529](https://gitlab.opencode.de/bmi/opendesk/components/platform-development/charts/opendesk-mariadb/commit/b3c0529618db12f9211d9a76ed476546e2e6bd6a))

# [2.2.0](https://gitlab.opencode.de/bmi/opendesk/components/charts/opendesk-mariadb/compare/v2.1.1...v2.2.0) (2023-12-06)


### Features

* **mariadb:** [[#1](https://gitlab.opencode.de/bmi/opendesk/components/charts/opendesk-mariadb/issues/1)] Add cleanup flag to configure job deletion on success ([af5263d](https://gitlab.opencode.de/bmi/opendesk/components/charts/opendesk-mariadb/commit/af5263d4d61a67eb0b53973bf5921843c05e8505))

## [2.1.1](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/compare/v2.1.0...v2.1.1) (2023-10-16)


### Bug Fixes

* **mariadb:** Don't quote targetPort ([39e0954](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/39e0954574c9dd341e68d2f1ac8a704ecbf41df1))
* **mariadb:** Use "| quote" wherever possible ([9e769b0](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/9e769b0d38aa66d5ac163ead3531197027df82df))

# [2.1.0](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/compare/v2.0.2...v2.1.0) (2023-09-12)


### Features

* **mariadb:** Use updated binary pathes to support 11.1.x ([2fbc7b3](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/2fbc7b3e781d05b0f2608eb679ef00b7b888eae7))

## [2.0.2](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/compare/v2.0.1...v2.0.2) (2023-08-23)


### Bug Fixes

* **mariadb:** Update default security profile settings ([1f775a3](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/1f775a351066e3adf05b53aa7e815884b24ca793))

## [2.0.1](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/compare/v2.0.0...v2.0.1) (2023-08-03)


### Bug Fixes

* **mariadb:** Terminate bootstrap job when timeout is reached ([b37c855](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/b37c855564c643aa04778f34489599ef0e5cc8d5))

# [2.0.0](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/compare/v1.0.1...v2.0.0) (2023-07-26)


### Features

* **mariadb:** Add common configuration options ([30eb89a](https://gitlab.souvap-univention.de/souvap/tooling/charts/mariadb/commit/30eb89ababb0d8149e61b7fee599aaea4f4b6aa8))


### BREAKING CHANGES

* **mariadb:** Restructure configuration to mariadb.configuration
