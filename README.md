# RFP 200 Release Bins

This repository holds public OTA-safe firmware artifacts for `RFP 200`.

Published content in this repo is intended for already provisioned displays that are already running the RFP OTA firmware family.

Compatibility note: the OTA project identifier and this repository path remain on
the legacy `rfp_display_1_75` / `RFP-1.75-release-bins` naming so deployed
clients continue to resolve the same manifest and pass OTA validation.

This repo should contain only:

- signed app-only OTA `.bin` files
- `latest.json` metadata for the companion app

This repo must not contain:

- bootloader binaries
- partition table binaries
- merged flash images
- provisioning bundles
- signing keys
