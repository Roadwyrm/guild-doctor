# Guild Doctor Public Release Checklist

## Complete

- [x] Read-only Discord scan boundary
- [x] Token non-disclosure and redacted failure reports
- [x] Structural snapshot completeness checks
- [x] Role, channel, category, and synchronization analysis
- [x] Plain-language permission explanations
- [x] `server-report` command surface
- [x] Versioned server-map artifact
- [x] Versioned report bundle with additive server map
- [x] 575 Stage 8 tests passing
- [x] Pass 5 integration tests passing

## Final live verification

- [x] Run one bounded read-only structural scan
- [x] Confirm structural and thread completeness
- [x] Confirm no registration, permission, or server-object writes
- [x] Save the live receipt and snapshot reference
- [x] Reconcile command catalog against the current 13-command manifest

## Public safety requirements

- [x] No token appears in output, logs, reports, or screenshots
- [x] No automatic role, channel, category, permission, or command mutation
- [x] Incomplete evidence is labeled clearly
- [x] Reports distinguish facts from recommendations
- [x] Server IDs and member identities remain protected in public artifacts
- [x] Users receive a clear explanation before any future mutation feature is considered

## Public handoff contents

- Scanner package
- Installation instructions
- Read-only command reference
- Visual server-map explanation
- Privacy and safety statement
- Troubleshooting guide
- Known limitations
- Live validation receipt

## Release status

Current state: **LIVE READ-ONLY VALIDATION AND RELEASE-CANDIDATE PACKAGING PASSED**.

The application is cleared for public read-only publication, provided internal live evidence remains private and the final package includes the approved documentation.
