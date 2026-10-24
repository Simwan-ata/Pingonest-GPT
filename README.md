# PINGONEST GPT

Independent development workspace for the PingoNest organizational platform.

## Purpose

This repository is the GPT-assisted working copy for architecture review, controlled refactoring, and validation. The original [`PINGOnest`](https://github.com/Simwan-ata/PINGOnest) repository remains unchanged.

## Baseline

- Preserve existing product capabilities while refactoring.
- Treat the platform as organization-centered, not HR-only.
- Keep `Person`, `Position`, `OrganizationUnit`, and `Assignment` as distinct concepts.
- Model organizational relationships explicitly; do not rely on a single `parentId` tree as the canonical model.
- Treat identity/access control, governance, audit, versioning, and change history as cross-cutting concerns.
- Do not claim server-side security unless authentication and authorization are enforced on the server.

## Working protocol

1. Inspect the baseline and document findings.
2. Make small, reviewable changes.
3. Preserve a clean separation from the source repository.
4. Run available validation/build checks and report what was and was not tested.

## Source

Baseline repository: https://github.com/Simwan-ata/PINGOnest
