# Open Flow

Open Flow is a free, community-powered library of real interface screens and user flows.

The goal is simple: make high-quality UI references accessible to everyone without locking everything behind a subscription.

Instead of one company maintaining the entire library, Open Flow is built and maintained by the community.

## What is Open Flow?

Open Flow is an open-source project for collecting and organizing UI references from apps, websites, dashboards, platforms, and digital products.

Users can contribute:

* App screens
* Website screens
* Complete user flows
* Onboarding experiences
* Authentication flows
* Checkout flows
* Settings pages
* Search experiences
* Educational platforms
* Dashboards
* Mobile interfaces
* Desktop interfaces
* Other useful product design references

The repository is the starting point for the project.

A dedicated Open Flow website and additional tools may be built later.

## Why Open Flow?

Design reference libraries are extremely useful, but many of them place large parts of their collections behind paid plans.

Open Flow takes a different approach.

The library is intended to remain:

* Free to browse
* Community maintained
* Easy to contribute to
* Easy to search
* Open source
* Useful for designers and developers
* Large enough to include both popular and niche products

The community should be able to document interfaces that traditional design libraries may never cover.

That could include anything from major social apps to school portals, educational websites, local services, experimental software, or extremely niche products.

## Project Goals

Open Flow aims to eventually provide:

1. A large searchable interface library
2. Individual screens grouped by product and platform
3. Complete user flows
4. Community submissions
5. Community moderation
6. Tags and categories
7. Search and filtering
8. Version history for interfaces
9. Metadata for devices and platforms
10. An API
11. An MCP server for AI tools and coding agents
12. A dedicated Open Flow website

The long-term goal is to create an open interface reference database that humans and software tools can both use.

## Repository Structure

The exact structure may change as the project grows.

A possible structure is:

```text
open-flow/
├── apps/
├── screens/
├── flows/
├── metadata/
├── contributors/
├── docs/
├── tools/
├── api/
├── mcp/
├── CONTRIBUTING.md
├── CONTENT_POLICY.md
├── LICENSE
└── README.md
```

Each product can eventually contain structured metadata alongside its screenshots.

Example:

```text
apps/
└── example-app/
    ├── metadata.json
    ├── screens/
    │   ├── home/
    │   ├── search/
    │   └── settings/
    └── flows/
        ├── onboarding/
        └── account-creation/
```

## Contributing

Open Flow depends on community contributions.

Contributions may include:

* New screenshots
* Updated screenshots
* New flows
* Better metadata
* Categorization
* Documentation
* Bug fixes
* Website improvements
* Search improvements
* API development
* MCP development
* Moderation tools

Before contributing, please read `CONTRIBUTING.md` and `CONTENT_POLICY.md`.

When submitting screenshots, contributors should provide accurate information whenever possible.

Useful metadata may include:

```text
Product:
Platform:
Operating System:
Device:
Screen:
Flow:
Version:
Date Captured:
Region:
Contributor:
```

Do not submit private information, personal accounts, passwords, private messages, payment information, API keys, authentication tokens, or other sensitive data.

## Content Guidelines

Open Flow is intended for documenting and studying interface design.

Community submissions should focus on the interface itself.

Do not upload content containing:

* Passwords
* Authentication tokens
* Private messages
* Personal email addresses
* Phone numbers
* Payment information
* Private user information
* Confidential company information
* Content obtained through unauthorized access

Screenshots should be sanitized before submission when necessary.

## Copyright and Trademarks

Open Flow does not claim ownership of third-party applications, screenshots, trademarks, logos, product names, or interface designs.

All trademarks and copyrighted material belong to their respective owners.

Screenshots contributed to Open Flow are intended for purposes such as design reference, research, commentary, documentation, and education.

The Open Flow software itself is licensed separately from third-party content contained within the library.

If you are a rights holder and believe material should be removed, please open an issue or contact the project maintainers.

## License

The Open Flow source code is licensed under the GNU Affero General Public License v3.0.

See `LICENSE` for the complete license.

Third-party screenshots, logos, trademarks, and other submitted media are not automatically licensed under the AGPL and may remain subject to the rights of their respective owners.

## MCP

One of Open Flow's planned features is an MCP server.

This could allow AI coding and design tools to search the Open Flow library directly.

For example, an agent could request:

```text
Find examples of mobile checkout flows.
```

or:

```text
Show dashboard navigation patterns from productivity apps.
```

or:

```text
Find onboarding screens for educational apps.
```

The MCP could return relevant screens, flows, metadata, and references from the Open Flow database.

This would make Open Flow useful not only as a website, but as infrastructure for design agents and development tools.

## API

A public API may eventually provide programmatic access to Open Flow data.

Possible endpoints could include:

```text
/apps
/apps/:id
/screens
/screens/:id
/flows
/flows/:id
/search
/categories
/platforms
```

The API design has not been finalized.

## Roadmap

Open Flow is currently at an early stage.

Planned development includes:

* Repository structure
* Contribution format
* Screenshot metadata standard
* Community submission process
* Moderation system
* Search
* Filters
* Product pages
* Flow viewer
* Website
* API
* MCP server
* Automated duplicate detection
* Version tracking
* Community accounts
* Reporting tools

The roadmap may change as the project develops.

## Community

Open Flow should be shaped by the people who use it.

Ideas, discussions, bug reports, feature requests, interface submissions, and code contributions are welcome.

If you have an idea, open an issue or start a discussion.

## Status

Open Flow is under active development.

Expect breaking changes while the repository structure, contribution system, metadata format, and future website are being designed.

## Open Flow

Free UI references.

Built by the community.

Open for everyone.
