# Storlane (frontend)

![License MIT](https://img.shields.io/badge/license-MIT-green)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/jinzhenyi/Storlane-Frontend)](./package.json)
[![NPM Version](https://img.shields.io/npm/v/%40storlane-frontend%2Fstorlane-frontend)](https://www.npmjs.com/package/@storlane-frontend/storlane-frontend)
[![NPM Downloads](https://img.shields.io/npm/dw/%40storlane-frontend%2Fstorlane-frontend)](https://www.npmjs.com/package/@storlane-frontend/storlane-frontend)
[![NPM Last Update](https://img.shields.io/npm/last-update/%40storlane-frontend%2Fstorlane-frontend)](https://www.npmjs.com/package/@storlane-frontend/storlane-frontend)

## BUILD

You can use [the build script](./build.sh).

```plaintext
Usage: ./build.sh [--dev|--release] [--compress|--no-compress] [--enforce-tag] [--skip-i18n] [--lite]

Options (will overwrite environment setting):
  --dev         Build development version
  --release     Build release version (will check if git tag match package.json version)
  --compress    Create compressed archive
  --no-compress Skip compression
  --enforce-tag Force git tag requirement for both dev and release builds
  --skip-i18n   Skip i18n build step
  --lite        Build lite version

Environment variables:
  STORLANE_FRONTEND_BUILD_MODE=dev|release (default: dev)
  STORLANE_FRONTEND_BUILD_COMPRESS=true|false (default: false)
  STORLANE_FRONTEND_BUILD_ENFORCE_TAG=true|false (default: false)
  STORLANE_FRONTEND_BUILD_SKIP_I18N=true|false (default: false)
```

## LICENSE

MIT

## CREDITS

[Storlane](https://github.com/jinzhenyi/Storlane) is a resilient, community-driven fork of [AList](https://github.com/AlistGo/alist) — built to defend open source against trust-based attacks.

This frontend is based on [OpenList-Frontend](https://github.com/OpenListTeam/OpenList-Frontend) (MIT License), customized and rebranded for Storlane.
