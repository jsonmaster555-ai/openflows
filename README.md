# Open Flow

Open Flow is a free, community-powered library of real interface screens and user flows.

The project exists to make useful UI references easier to access, study, and maintain without placing the core library behind a subscription. The repository is the source of truth for the community dataset, documentation, schemas, and future tools.

## What belongs here

Open Flow focuses on two things:

- **Screens**: individual screenshots of an interface state
- **Flows**: ordered groups of screens showing how a task is completed

Examples include onboarding, authentication, search, checkout, settings, messaging, account management, dashboards, educational tools, and other useful product experiences.

## Privacy first

Every submission must be sanitized **before it is uploaded**.

- Blur every recognizable real person and face.
- Blur personal profile pictures and avatars showing real people.
- Blur names, usernames, handles, email addresses, phone numbers, locations, schools, workplaces, private messages, payment details, account identifiers, and other identifying information.
- Remove secrets such as passwords, one-time codes, API keys, session tokens, QR codes, and private links.
- Use test accounts and fake data whenever possible.

Read [SUBMISSION_GUIDELINES.md](SUBMISSION_GUIDELINES.md) before contributing media. If something might identify a person, blur it.

## Submit screens and flows

Want to contribute a screen or complete flow? Use the private submission form below. Submissions are reviewed manually before anything is added to the repository.

<table>
  <tr>
    <td>
      <strong>Contribute to Open Flow</strong><br />
      Upload sanitized screenshots and interface flows for review.
    </td>
    <td align="right">
      <a href="https://forms.gle/ojEQb2b76MGAzRDx7"><strong>Open submission form →</strong></a>
    </td>
  </tr>
</table>

The form collects screenshots privately for moderation. Read [SUBMISSION_GUIDELINES.md](SUBMISSION_GUIDELINES.md) before uploading.

## Repository layout

```text
open-flow/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── CODEOWNERS
│   └── PULL_REQUEST_TEMPLATE.md
├── apps/
├── docs/
├── examples/
├── flows/
├── schemas/
├── screens/
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTENT_POLICY.md
├── CONTRIBUTING.md
├── DMCA.md
├── GOVERNANCE.md
├── LICENSE
├── PRIVACY.md
├── ROADMAP.md
├── SECURITY.md
├── SUBMISSION_GUIDELINES.md
└── SUPPORT.md
```

## Planned features

- Browse screens and complete flows
- Filter by product, platform, category, region, and date
- Search structured metadata
- Track interface versions and updates
- Community submissions and moderation
- Duplicate detection and reporting
- Public API
- MCP server for design and coding tools
- A dedicated Open Flow website

See [ROADMAP.md](ROADMAP.md) for the current direction.

## Contributing

1. Read [CONTRIBUTING.md](CONTRIBUTING.md).
2. Read [SUBMISSION_GUIDELINES.md](SUBMISSION_GUIDELINES.md) and [CONTENT_POLICY.md](CONTENT_POLICY.md).
3. Create a branch for your contribution.
4. Add or update the content and metadata.
5. Run the checks described in the contribution guide.
6. Open a pull request using the repository template.

By contributing, you confirm that you are allowed to provide the contribution and that it follows the project policies.

## Copyright and trademarks

Open Flow does not claim ownership of third-party products, trademarks, logos, interface designs, or screenshots. Those materials remain subject to the rights of their owners. Their presence does not imply endorsement or affiliation.

The project is intended for interface reference, research, commentary, documentation, and education. Those purposes do not automatically make every use lawful in every country or situation. Rights holders can use the process in [DMCA.md](DMCA.md) to request review or removal.

## License

Open Flow source code is licensed under the [GNU Affero General Public License v3.0](LICENSE).

Third-party screenshots, logos, product names, trademarks, and other submitted media are not automatically licensed under the AGPL. See [CONTENT_POLICY.md](CONTENT_POLICY.md).

## Status

Open Flow is in its foundation stage. The file structure and schemas may change before the first stable release.
