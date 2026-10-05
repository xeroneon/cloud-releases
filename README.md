# Xeroneon Cloud — Android Releases (public)

Public **release-only** channel for the [Xeroneon Cloud](https://cloud.xeroneon.dev) Android app.
The app source stays private in `xeroneon/cloud`. This repo just hosts signed APK releases so
[Obtainium](https://obtainium.imranr.dev/) can install + update the app with no GitHub auth.

## Install in Obtainium

1. In Obtainium, add an app with **source: GitHub**.
2. Repo: `xeroneon/cloud-releases`
3. **What to install** (regex): `xeroneon-cloud-v[\d.]+[.]apk`
   (or simply `[.]apk` to match any release asset)
4. Version check: **By release TAG NAME** (tags are `vX.Y.Z`).

Releases here are public, so no token is needed.

## Asset naming

Each release attaches a signed APK named `xeroneon-cloud-v<version>.apk`
(e.g. `xeroneon-cloud-v0.1.0.apk`).

## Source

Source lives in [`xeroneon/cloud`](https://github.com/xeroneon/cloud) (private).
