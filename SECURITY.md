# Security Policy

This is the public contact point for security issues in anything published by
**BumuStudios** — this site and both Android applications:

- **ImageToPdf** — `com.bumustudios.imgtopdf`
- **PdfPages** — `com.bumustudios.pdfpages`

The application source repositories are private, so this is the only place a
report can reach us.

## Reporting a vulnerability

Please use whichever suits you:

1. **GitHub private vulnerability reporting** on this repository —
   *Security → Report a vulnerability*. Preferred, because the discussion stays
   private and attached to a record.
2. **Email** <bumustudios@gmail.com> with `SECURITY` in the subject line.

Useful things to include: which app and version, the device and Android version,
what an attacker gains, and the steps to reproduce it. A proof of concept helps
but is not required — a clear description of the flaw is enough to start.

**Please do not open a public issue** for a vulnerability, and please do not
publish details before a fix has shipped to Google Play.

## What to expect

- **Acknowledgement within 7 days.** If you have not heard back by then, assume
  the mail went astray and send it again.
- An assessment and a rough timeline once the report is understood.
- Credit in the release notes when a fix ships, if you would like it.

There is **no paid bug bounty**. This is a two-person studio; what we can offer
is a prompt reply, a real fix, and public credit.

## Scope

In scope: the two applications above, and the content served from
`bumustudios.github.io`.

Out of scope, because they are not ours to fix: Google Play, the Google Mobile
Ads SDK, Google Play Billing, and the Android platform itself. Report those to
Google. Findings that depend on a rooted device, a hostile app already holding
the same permissions, or physical access to an unlocked phone are also out of
scope.

## A note on how the apps work

Both applications process files entirely on the device and neither has a backend,
a user account, or any file upload. There is no server of ours to attack. The
realistic attack surface is local: how the apps handle a malformed or hostile
input file, and what they expose through Android IPC — shared intents, content
URIs and exported components. That is where we would look first, and reports
there are especially welcome.
