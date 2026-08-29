# LyraStage Updates

Official public **update-only** channel for already-installed LyraStage clients.

## Initial installation

The first-install Windows Setup is distributed separately through the owner's protected download portal at `https://dl.irodoli.com/`. Standalone initial installers are not published from this repository.

## Installed-client updates

Installed clients read the Ed25519-signed `latest.json`, verify the exact update package URL, expected byte size, and SHA-256, then apply the existing-install update package through LyraStage's maintenance backend.

GitHub is therefore the post-install update backend, not the advertised first-install download route.

Public contents are limited to signed update metadata, release notes, update-only release assets, and the issue tracker. The application source, signing private key, credentials, user data, logs, and standalone initial installers are not published here.
