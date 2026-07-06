# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v1.0.0...v1.0.1) (2026-06-04)


### 🐛 Fixes

* use correct namespace list for validation, exclude integration policy permissions from resource collection policy ([#43](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/43)) ([d822416](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/d82241657e67607c2bb0f51b209e51ec4048f44f))

## [1.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.9.1...v1.0.0) (2026-06-03)


### 🚀 Features

* breaking: updated for deprecated datadog_integration_aws_* res… ([#41](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/41)) ([700b11d](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/700b11da3a112d967d8368b610138b5a11f1861e))

## [0.9.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.9.0...v0.9.1) (2026-04-22)


### 🐛 Fixes

* use variables for iam role name and collection policy ([#42](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/42)) ([9294c67](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/9294c67446c2b5bb14cc2941acf94e79253bb46b))
* use variables for iam role name and collection policy ([#42](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/42)) ([9294c67](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/9294c67446c2b5bb14cc2941acf94e79253bb46b))

## [0.9.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.5...v0.9.0) (2025-03-19)


### 🚀 Features

* option to create Datadog API key ([#38](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/38)) ([7652f24](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/7652f24e78ed346d59fc43f2014d17313abad99e))

## [0.8.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.4...v0.8.5) (2024-10-02)


### 🐛 Fixes

* Bump minimum required DD provider as extended resource collection field was added in 3.39.0 ([#36](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/36)) ([5011425](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/5011425935367b882d13508e5111ba063fea86a2))

## [0.8.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.3...v0.8.4) (2024-09-25)


### 🐛 Fixes

* bug: resource_collection logic fix ([#35](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/35)) ([0f4986d](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/0f4986de78361214cac5dd8b0d75482be29e5299))

## [0.8.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.2...v0.8.3) (2024-09-17)


### 🐛 Fixes

* policy should still be created without enabling cloud security ([#34](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/34)) ([5cfd80e](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/5cfd80ef7fdb0e8353d13ecbf5a4b74d2f42e4e3))

## [0.8.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.1...v0.8.2) (2024-08-21)


### 🐛 Fixes

* bug: cannot be empty for policies ([#33](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/33)) ([b1623ac](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/b1623ac8b5e67dc4adebf554266d6f4cedb08b07))

## [0.8.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.8.0...v0.8.1) (2024-08-21)


### 🐛 Fixes

* bug: correct arn of policy! ([#32](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/32)) ([dc91164](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/dc911642c71e4039d42f721398f4311a95ee3155))

## [0.8.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.7.1...v0.8.0) (2024-08-20)


### 🚀 Features

* additional AWS resource collection IAM policy ([#31](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/31)) ([16e72bc](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/16e72bc2dbdeb48bbe781acd7ffb288ffe52e813))

## [0.7.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.7.0...v0.7.1) (2024-08-15)


### 🐛 Fixes

* Dependency fixes. ([#30](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/30)) ([abde21d](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/abde21dda9b1ccd33d7ea198313a3669b41f697b))

## [0.7.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.6.0...v0.7.0) (2024-07-08)


### 🚀 Features

* Add metrics tag filter ([#29](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/29)) ([bfd2cfa](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/bfd2cfab688ca04fe56139149aaf1c0a5a7e04d8))
* Add metrics tag filter ([#29](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/29)) ([bfd2cfa](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/bfd2cfab688ca04fe56139149aaf1c0a5a7e04d8))

### 🐛 Fixes

* correct policy ARN ([#28](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/28)) ([6dbaa30](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/6dbaa300b328abf8956085c576119726634b5e30))

## [0.6.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.5.0...v0.6.0) (2024-07-05)


### 🚀 Features

* enable Datadog resource collection for cloud security ([#27](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/27)) ([a2bca50](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/a2bca5013b9b38aea65cbfcbfcb5e38c3b585b62))

## [0.5.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.4.0...v0.5.0) (2024-06-03)


### 🚀 Features

* Add configuration of the enabled namespaces ([#25](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/25)) ([d7f85ad](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/d7f85adfa6c66065a07ada6d175ed04f57fb40c4))

## [0.4.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.12...v0.4.0) (2023-12-06)


### 🐛 Fixes

* Let datadog_integration_aws_log_collection depend on the cloudformation stack to prevent deployment issues & refactoring module ([#24](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/24)) ([c4ee167](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/c4ee167167495bb42b3293c5b693d5ab0c88256f))
* Let datadog_integration_aws_log_collection depend on the cloudformation stack to prevent deployment issues & refactoring module ([#24](https://github.com/schubergphilis/terraform-aws-mcaf-datadog/pull/24)) ([c4ee167](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/commit/c4ee167167495bb42b3293c5b693d5ab0c88256f))

## [0.3.12](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.10...v0.3.12) (2023-12-05)

## [0.3.10](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.11...v0.3.10) (2023-01-10)

## [0.3.11](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.9...v0.3.11) (2023-01-10)

## [0.3.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.8...v0.3.9) (2022-09-29)

## [0.3.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.7...v0.3.8) (2022-01-17)

## [0.3.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.6...v0.3.7) (2021-09-09)

## [0.3.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.5...v0.3.6) (2021-09-01)

## [0.3.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.4...v0.3.5) (2021-08-17)

## [0.3.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.3...v0.3.4) (2021-04-08)

## [0.3.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.1...v0.3.3) (2020-12-09)

## [0.3.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.2...v0.3.1) (2020-10-19)

## [0.3.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.3.0...v0.3.2) (2020-10-19)

## [0.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.2.2...v0.3.0) (2020-09-22)

## [0.2.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.2.1...v0.2.2) (2020-09-14)

## [0.2.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.2.0...v0.2.1) (2020-09-11)

## [0.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.1.3...v0.2.0) (2020-08-13)

## [0.1.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.1.2...v0.1.3) (2020-07-06)

## [0.1.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.1.1...v0.1.2) (2020-03-17)

## [0.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-datadog/compare/v0.1.0...v0.1.1) (2019-11-26)

## 0.1.0 (2019-09-20)

