# EPIC

An Android keyboard designed to transform ordinary words into
luxurious style, elevated, and epic language using AI.

## Builds

- [EPIC 0.1.0](EPIC-0.1.0.apk?raw=true) — Initial version
- [EPIC 0.2.0](EPIC-0.2.0.apk?raw=true) — Updated version

## Installation

Download an APK from the **Builds** links above and install it on your Android
device. The APK files are stored directly in this repository.

To check that a downloaded file matches this checkout, download `SHA256SUMS`
into the same folder and run:

```bash
sha256sum --check --ignore-missing SHA256SUMS
```

The checksums detect changed or incomplete downloads; they do not verify the
publisher's identity or replace Android's APK signature checks.

## Repository scope

This repository contains prebuilt APKs and documentation. Android source code,
build configuration, and signing material are not included, so the app cannot be
rebuilt or upgraded from this checkout alone.

## API

EPIC uses the Groq API. Configure your own API key in the app.
Never commit API keys or other secrets.
