# Vanda RiskGuard Releases

Official channel for signed Vanda RiskGuard binary releases and customer documentation. Product source code remains private.

**Current stable release: [Vanda RiskGuard 1.1.1](https://github.com/RezaAskari4755/Vanda-RiskGuard-Releases/releases/tag/v1.1.1).** Both signed component feeds are available from Latest.

Downloads: [EA package](https://github.com/RezaAskari4755/Vanda-RiskGuard-Releases/releases/download/v1.1.1/riskguard-1.1.1.zip), [Windows companion](https://github.com/RezaAskari4755/Vanda-RiskGuard-Releases/releases/download/v1.1.1/VandaUpdater.exe), [Persian customer guide](https://github.com/RezaAskari4755/Vanda-RiskGuard-Releases/releases/download/v1.1.1/Vanda-RiskGuard-Customer-Guide-FA.pdf).

The Windows companion verifies signed manifests and package hashes before installation. Updates require user consent, and EA installation is gated by terminal safety. Companion self-update support starts at version 1.1.1; users of 1.0.0 need a one-time manual companion upgrade.

## Release assets

- `riskguard-update.json` and `riskguard-VERSION.zip`: signed EA component; archive contains exactly `VN_STRM.ex5`.
- `riskguard-updater-update.json` and `riskguard-updater-VERSION.zip`: separately typed signed companion component; archive contains exactly `VandaUpdater.exe`.
- `VandaUpdater.exe`: initial Windows companion setup.
- `Vanda-RiskGuard-Customer-Guide-FA.pdf`: Persian illustrated customer guide.

Every published Latest release must retain both valid component feeds. Draft assets are not a working public update feed. A handoff archive is not an update package.

## Public verification key

`public-update-key.xml` is public-only RSA verification material for key ID `rg-update-2026-10-24`.

SHA-256 of this public XML file:

`ca7f49e1c84f43c791b70d92e482cf46e0a06e788f5202d9c6cd83e74939ef18`

The independent private update-signing key is not stored in this repository or customer downloads. This package signature is separate from Windows Authenticode signing; do not bypass Windows security warnings.
