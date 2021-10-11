# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.8.0]
### Added
- Allow ledger-bridge iframe to connect Ledger wia WebHID, when it is supported by the current browser ([#107](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/107))

### Changed
- Reject with an Error object if unlocking is not successful  ([#104](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/104))
- Ensure that logs of errors only have a single `Error:` string in the message ([#105](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/105))

## [0.7.0]
### Changed
- Remove unused `events` and `ethereumjs-tx` dependencies ([#101](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/101), [#102](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/102))
- Update eth-ledger-bridge-keyring to support EIP-1559 transactions ([#98](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/98), [#97](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/97), [#96](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/96))

## [0.6.0]
### Added
- Support new versions of ethereumjs/tx ([#68](https://github.com/MetaMask/eth-ledger-bridge-keyring/pull/68))