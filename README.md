# RFP Display 1.75 Release Bins

This repository holds public OTA-safe firmware artifacts for `RFP Display 1.75`.

Published content in this repo is intended for already provisioned displays that are already running the RFP OTA firmware family.

This repo should contain only:

- signed app-only OTA `.bin` files
- `latest.json` metadata for the companion app

This repo must not contain:

- bootloader binaries
- partition table binaries
- merged flash images
- provisioning bundles
- signing keys
