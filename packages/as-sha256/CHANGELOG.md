# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.5.0](https://github.com/ChainSafe/ssz/compare/as-sha256-v0.5.0...as-sha256-v0.5.0) (2024-10-15)


### Bug Fixes

* add homepage/repo etc to as-sha256 package.json ([#401](https://github.com/ChainSafe/ssz/issues/401)) ([1dc50ef](https://github.com/ChainSafe/ssz/commit/1dc50ef2985a03c315bbce44165cd271a4a6e2df))

## [0.5.0](https://github.com/ChainSafe/ssz/compare/as-sha256-v0.4.2...as-sha256-v0.5.0) (2024-08-06)


### ⚠ BREAKING CHANGES

* implement hashInto() api for as-sha256 ([#382](https://github.com/ChainSafe/ssz/issues/382))

### Features

* implement hashInto() api for as-sha256 ([#382](https://github.com/ChainSafe/ssz/issues/382)) ([ccadf43](https://github.com/ChainSafe/ssz/commit/ccadf431cea6164822e72771304192b2728d7bb2))
* SIMD implementation for as-sha256 ([#367](https://github.com/ChainSafe/ssz/issues/367)) ([ec123ec](https://github.com/ChainSafe/ssz/commit/ec123ec3cfcc37ff82635da7a57ad9c74cc9accb))
* use allocUnsafe to allocate hash digests ([#391](https://github.com/ChainSafe/ssz/issues/391)) ([8ea1bb4](https://github.com/ChainSafe/ssz/commit/8ea1bb4809592691e568238520cb3c2aa9257c25))

## [0.4.2](https://github.com/ChainSafe/ssz/compare/as-sha256-v0.4.1...as-sha256-v0.4.2) (2024-05-02)


### Bug Fixes

* migrate to the latest assemblyscript ([#348](https://github.com/ChainSafe/ssz/issues/348)) ([9cf6991](https://github.com/ChainSafe/ssz/commit/9cf6991e7ece4e4002668f601ecb43bb8bd53f4e))

## [0.4.1](https://github.com/ChainSafe/ssz/compare/as-sha256-v0.4.0...as-sha256-v0.4.1) (2023-04-21)


### Bug Fixes

* Use file path imports ([#318](https://github.com/ChainSafe/ssz/issues/318)) ([f459e92](https://github.com/ChainSafe/ssz/commit/f459e92fbafc5d9388bfa630291855ec32a09566))

## [0.4.0](https://github.com/ChainSafe/ssz/compare/as-sha256-v0.3.1...as-sha256-v0.4.0) (2023-04-05)


### Features

* add swappable hasher, default to noble-hashes ([#314](https://github.com/ChainSafe/ssz/issues/314)) ([4b44614](https://github.com/ChainSafe/ssz/commit/4b44614003619b2c5477363a3c85287e2f2987bd))

## [0.3.1](https://github.com/chainsafe/as-sha256/compare/@chainsafe/as-sha256@0.3.0...@chainsafe/as-sha256@0.3.1) (2022-04-14)

* Add and use a new helper to digest64 two 32 bytes (#255)
* Remove unused files (#248)
* Bump minimist from 0.0.8 to 0.0.10 (#192)

# [0.3.0](https://github.com/chainsafe/as-sha256/compare/@chainsafe/as-sha256@0.2.4...@chainsafe/as-sha256@0.3.0) (2022-03-24)


* Convert as-sha256 to typescript (#244) ([2d4e3fe](https://github.com/chainsafe/as-sha256/commit/2d4e3febec89ca8ca7c89a19c6949c3213c2c45c)), closes [#244](https://github.com/chainsafe/as-sha256/issues/244)


### BREAKING CHANGES

* export digest* functions as named exports

## 0.2.4 (2021-08-18)

- normal digest mem opt for < 512 bytes ([30f7ec](https://github.com/ChainSafe/as-sha256/commit/30f7ec))

## 0.2.3 (2021-08-10)

- Add digestObjects method ([da5d82](https://github.com/ChainSafe/as-sha256/commit/da5d82))
- Optimised w+k for digest64 ([359555](https://github.com/ChainSafe/as-sha256/commit/359555))

## 0.2.2 (2021-05-06)

### Bug Fixes

- Fix static digest method ([a42f89](https://github.com/ChainSafe/as-sha256/commit/a42f89))

## 0.2.1 (2021-05-04)

### Chores

- Add performance tests ([9621ea](https://github.com/ChainSafe/as-sha256/commit/9621ea))

### Features

- Add optimized digest64 method for 64 byte input ([4acbea](https://github.com/ChainSafe/as-sha256/commit/4acbea))

<a name="0.2.0"></a>
## 0.2.0 (2020-02-19)

### BREAKING CHANGES

* new TS and AS exported interface

<a name="0.1.4"></a>
## 0.1.4 (2020-01-30)

### Bug Fixes

* fix data corruption on hash return ([9dd43f](https://github.com/ChainSafe/as-sha256/commit/9dd43f))

### Chores

* update license to Apache-2.0 ([585b2c6](https://github.com/ChainSafe/as-sha256/commit/585b2c6))

### Code Refactoring

* browser compatible as-sha256 ([e44f1d0](https://github.com/ChainSafe/as-sha256/commit/e44f1d0))
* update README & minor refactorings ([122e2a8](https://github.com/ChainSafe/as-sha256/commit/122e2a8))
* add `toHexString` to public wasm api ([eb3534a](https://github.com/ChainSafe/as-sha256/commit/eb3534a))
