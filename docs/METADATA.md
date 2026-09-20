# Metadata Reference

Open Flow stores product, screen, and flow information as JSON. The schemas in `schemas/` are authoritative.

## Shared conventions

- `schemaVersion` is currently `1.0`.
- IDs and slugs use lowercase kebab-case.
- Capture dates use `YYYY-MM` when the exact day is unnecessary.
- Platforms use the controlled values listed in the schemas.
- Tags describe interface patterns, not people.
- `privacyReviewed` must be `true` for accepted screens and flows.
- `submittedBy` uses a GitHub username beginning with `@`.

## Product metadata

One `metadata.json` file describes a product and its supported platforms and categories.

## Screen metadata

A screen JSON file lives beside its image and uses the same base filename. Its `id` must be unique across the repository.

## Flow metadata

A flow is an ordered list of existing screen IDs. Keep steps in the exact order a user experiences them.

## Unknown values

Omit optional values when they are unknown. Do not guess a version, capture date, region, device, or locale.

