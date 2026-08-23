# LyraStage Updates

This repository is the public update channel for already-installed LyraStage clients.

It intentionally does **not** distribute the first-install `LyraStage-Setup.exe`. The initial installer is provided directly by the LyraStage owner.

Installed clients read the Ed25519-signed `latest.json`, verify the exact update package URL, size, and SHA-256, then apply the existing-install update package through LyraStage's maintenance backend.

Public contents are limited to the signed update manifest, release notes, update-only release assets, and the issue tracker. The application source, signing private key, credentials, user data, logs, and standalone initial installers are not published here.
