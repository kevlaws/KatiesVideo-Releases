# Katie's Video — Windows releases

This public repository is the verified Windows update channel for **Katie's Video**, the venue-video player used by Katie O'Brien's Irish Taverns.

## What is published here

- Signed-off GitHub release notes.
- The Windows x64 installer.
- A SHA-256 checksum for every installer.

Pre-release versions are clearly marked and should be tested on a non-critical venue PC before live use.

## What is not published here

The Katie's Video application source remains private. This repository contains no venue data, media, schedules, server addresses, usernames, passwords, access tokens, API keys, debug symbols or application configuration.

## Verification

Katie's Video accepts updates only from this exact GitHub repository over HTTPS. Before an installer is opened, the application verifies its filename, download origin, published SHA-256 checksum, and final on-disk hash.

For support, contact Kev Laws at `k.laws@katieobriensirishtaverns.com`.
