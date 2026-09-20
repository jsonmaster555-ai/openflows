# Open Flow Submission Guidelines

Open Flow documents interface design, not the people using an interface. Every contributor must remove personal, private, identifying, and secret information before uploading anything.

## The main rule

If it identifies, shows, describes, contacts, tracks, or belongs to a real person, blur or remove it.

This rule applies even when the information is publicly visible elsewhere.

## Always blur or remove

- Faces and recognizable people
- Profile pictures or avatars showing real people
- Full names, partial names when identifying, display names, usernames, and handles
- Email addresses and phone numbers
- Home, school, workplace, and live-location information connected to a person
- Biographies or text containing identifying details
- Private messages, contact lists, follower lists, and notifications
- License plates and personal documents
- Account, order, tracking, membership, and support numbers
- Payment, banking, insurance, and medical information
- Search history, recently viewed content, and personalized recommendations when identifying
- QR codes, barcodes, invite links, and private URLs
- Passwords, passkeys, recovery codes, one-time codes, API keys, cookies, and session tokens
- Anything else that could reasonably identify or expose a person

## People and profile photos

Every recognizable real person must be anonymized. Blur the entire face strongly enough that it cannot be reconstructed or recognized. Crop the person out only when doing so does not misrepresent the interface.

Profile pictures showing people must always be blurred. Company logos, product icons, and clearly fictional artwork may remain unless they contain a recognizable real person.

## Dating and social apps

Dating, social, messaging, community, marketplace, school, and workplace apps need extra care.

For dating profiles, blur or replace every face, photo of a person, name, age linked to a profile, biography, distance, location, workplace, school, social handle, and other identifying detail. Prefer a test or demo account with fake profiles. Do not submit private conversations.

## Messages and user content

Names alone are not enough. Message text, images, timestamps, channel names, attachments, reactions, and surrounding context can identify someone.

Use empty states, public demo content, or intentionally created sample conversations whenever possible. Do not upload private conversations from real accounts.

## Use test data

The safest captures use an account created only for UI documentation. Prefer:

- Fake names and placeholder avatars
- Example addresses such as `person@example.com`
- Demo messages and empty histories
- Test payment data supplied by the product
- Developer, sandbox, or demo environments

Do not use another person's account. Avoid capturing a primary personal account.

## Blur before uploading

Sanitize every file before it is uploaded to GitHub, attached to an issue, placed in a pull request, or sent to a maintainer. Do not upload an original and ask someone else to blur it later. Git history and notification systems can preserve the original.

Use an opaque blur or solid redaction strong enough that the hidden content cannot be read. Do not use weak transparency, pixelation that leaves details recognizable, or removable editing layers.

## Inspect the whole frame

Zoom in and check:

1. Main content
2. Headers and sidebars
3. Navigation and status bars
4. Notifications and popovers
5. Search and browsing history
6. Suggested contacts and personalized recommendations
7. Background images and reflections
8. Tiny text, QR codes, and links
9. Every screen in a submitted flow
10. Image metadata when it may contain identifying information

## Capture rules

- Capture only interfaces you are authorized to access.
- Do not bypass subscriptions, authentication, rate limits, access controls, or technical protections.
- Do not submit leaked, stolen, confidential, or internal material.
- Do not misrepresent a modified mockup as a real product screen.
- Follow applicable law and the service's rules.

## Quality rules

- Keep the original aspect ratio.
- Preserve the full useful interface when possible.
- Avoid unnecessary cropping and compression.
- Do not add contributor watermarks.
- Do not add device frames or decorative backgrounds.
- Label intentional recreations or mockups clearly; do not mix them with verified captures.

## Required checklist

Before submitting, confirm:

- [ ] Every face and recognizable person is blurred or removed.
- [ ] Every personal profile photo is blurred or removed.
- [ ] Names, usernames, handles, emails, and phone numbers are removed.
- [ ] Locations, schools, workplaces, and personal biographies are removed.
- [ ] Private messages and identifying user content are absent.
- [ ] Payment, medical, account, and document information is absent.
- [ ] Passwords, codes, keys, tokens, QR codes, and private links are absent.
- [ ] The interface was captured through authorized access.
- [ ] The image is useful, accurate, and correctly labeled.
- [ ] Every screen in the flow was checked at full size.

When in doubt, blur it or leave it out.

