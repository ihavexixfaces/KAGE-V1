# KAGE V1 — Free Animations Edition

KAGE V1 has been re-released as the free animations-only edition of KAGE.

## Included
- Roblox animation scanning/reupload workflow
- Existing KAGE V1 interface and Studio Command Bar workflow
- User/group destination controls that were already part of V1
- Existing account/verification flow from this V1 codebase

## V1 Free limitation
Only **Animations** are supported by this release. The three additional asset-type slots are intentionally disabled/blank, and non-animation asset-type handling has been removed from the free V1 source.

For the expanded interface, additional supported asset categories, account manager, Recent History, improved progress UI, built-in updater, and other newer features, use KAGE V2.

## Development
```bash
npm start
```

## Windows package
```bash
npm run build:win
```

This repository keeps the existing Electron product/config identity so the V1 re-release does not unexpectedly move existing app-data paths.
