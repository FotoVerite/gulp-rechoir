# Changelog

## 1.0.0 (2026-10-06)


### ⚠ BREAKING CHANGES

* Normalize repository, dropping node <10.13 support ([#40](https://github.com/FotoVerite/gulp-rechoir/issues/40))

### Bug Fixes

* Bail gracefully on unknown extensions when nothrow is specified ([529d9c0](https://github.com/FotoVerite/gulp-rechoir/commit/529d9c0a2f7d5b9a41f10b209054965dc5b16a2b))
* Correct "is array" expectation ([4b67fcf](https://github.com/FotoVerite/gulp-rechoir/commit/4b67fcf0b0aaf1ff3e3d8b992d87df97fc9fb657))
* Ensure folder names containing dots don't cause a failure (fixes [#11](https://github.com/FotoVerite/gulp-rechoir/issues/11)) ([da4fd86](https://github.com/FotoVerite/gulp-rechoir/commit/da4fd86dd8a8e34d2f6893b6ffeb272194ab7467))
* Ensure load() resolves the filepath before requiring (fixes [#7](https://github.com/FotoVerite/gulp-rechoir/issues/7)) ([af80b79](https://github.com/FotoVerite/gulp-rechoir/commit/af80b7987b7e2c81b96570ee1308af360aa44f0c))
* Properly handle extensions like .coffee.md (fixes [#4](https://github.com/FotoVerite/gulp-rechoir/issues/4)) ([7726db9](https://github.com/FotoVerite/gulp-rechoir/commit/7726db9bf4519da02bd236a6fde34f0128384949))
* Support single character extensions (Fixes [#38](https://github.com/FotoVerite/gulp-rechoir/issues/38)) ([#39](https://github.com/FotoVerite/gulp-rechoir/issues/39)) ([1258548](https://github.com/FotoVerite/gulp-rechoir/commit/12585486c15f844f94ee92343420348931f16fe8))
* Update require-xml output & skip some tests on old node ([8611843](https://github.com/FotoVerite/gulp-rechoir/commit/86118439d9eb217e38a84819c61f342b68442f2d))


### Miscellaneous Chores

* Normalize repository, dropping node &lt;10.13 support ([#40](https://github.com/FotoVerite/gulp-rechoir/issues/40)) ([00f5968](https://github.com/FotoVerite/gulp-rechoir/commit/00f59689d0eb9668d939a85e06428a0906587a6f))

## [0.8.0](https://www.github.com/gulpjs/rechoir/compare/v0.7.1...v0.8.0) (2021-07-24)


### ⚠ BREAKING CHANGES

* Normalize repository, dropping node <10.13 support (#40)

### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#40](https://www.github.com/gulpjs/rechoir/issues/40)) ([00f5968](https://www.github.com/gulpjs/rechoir/commit/00f59689d0eb9668d939a85e06428a0906587a6f))
