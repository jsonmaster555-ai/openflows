# Contributing to Open Flow

Thanks for helping build Open Flow. Contributions can include screens, flows, metadata fixes, documentation, moderation tools, schemas, API work, MCP work, or website code.

## Before you contribute

Read these files first:

- [SUBMISSION_GUIDELINES.md](SUBMISSION_GUIDELINES.md)
- [CONTENT_POLICY.md](CONTENT_POLICY.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md) for security reports

## Ways to contribute

- Add a new product
- Add individual screens
- Add a complete flow
- Update an outdated interface
- Correct metadata
- Report a duplicate or policy problem
- Improve documentation or schemas
- Build project tooling

## Git workflow

1. Fork the repository.
2. Create a focused branch such as `screens/example-app-checkout` or `docs/privacy-fix`.
3. Make one logical change per pull request.
4. Use clear commit messages.
5. Open a pull request and complete every relevant checklist item.

## Adding a product

Create a product directory in `apps/<product-slug>/` containing `metadata.json`.

Use lowercase kebab-case slugs. For example, `example-learning-app` is valid and `Example Learning App` is not.

Validate metadata against `schemas/app.schema.json`.

## Adding a screen

1. Sanitize the image before it enters Git history.
2. Store the image under `screens/<product-slug>/<platform>/`.
3. Add a matching JSON metadata file beside it.
4. Use the same base filename for the image and JSON file.
5. Validate the metadata against `schemas/screen.schema.json`.

Example:

```text
screens/example-app/ios/
├── checkout-payment.png
└── checkout-payment.json
```

## Adding a flow

Create `flows/<product-slug>/<flow-slug>/flow.json` and reference existing screen IDs in order. Validate it against `schemas/flow.schema.json`.

Do not duplicate image files inside a flow directory. A flow should point to screens already stored in the screen library.

## Image requirements

- PNG, JPEG, or WebP only
- Original interface aspect ratio
- Clear and readable at normal zoom
- No contributor watermarks
- No unnecessary borders or decorative mockups
- No upscaling that invents interface details
- No personal or identifying information
- No visible secrets or private data

Privacy blurring is required and is not considered unwanted image editing.

## Metadata requirements

Provide accurate information when known:

- Product name and slug
- Platform
- Screen or flow name
- Capture month in `YYYY-MM` format
- Region when it changes the interface
- App or site version when known
- Tags
- Contributor GitHub username
- Whether test data was used

Never place personal account information in metadata.

## Commit messages

Use short messages that explain the change:

```text
add ios checkout flow for example app
update web settings screens
fix capture dates in example app metadata
```

## Pull request review

Maintainers may request:

- Stronger privacy redaction
- Better image quality
- Metadata corrections
- File renaming
- Removal of duplicates
- Proof that the contributor had authorized access to capture the interface

A submission can be rejected even if it passes automated checks.

## Contributor responsibility

By opening a pull request, you confirm that:

- You created the contribution or are authorized to submit it.
- You captured content through lawful, authorized access.
- You did not bypass access controls or obtain leaked material.
- You sanitized all personal, private, and secret information.
- You understand that repository history can preserve uploaded files.
- Your code contribution is provided under AGPL-3.0.

