# Security Policy

## Supported versions

This project is a static single-page application deployed from the `main` branch. Only the latest published version on [GitHub Pages](https://crymarch.github.io/un-scorm/) is supported for security fixes.

## Reporting a vulnerability

**Please do not open a public issue** for undisclosed security problems.

1. **Preferred:** Use [GitHub private vulnerability reporting](https://github.com/crymarch/un-scorm/security/advisories/new) for this repository (available if enabled in repo settings).
2. **Alternative:** Open a security-related discussion with the maintainer via GitHub (profile / appropriate private channel), or contact the repository owner through GitHub with enough detail to reproduce the issue.

Include:

- Description of the issue and potential impact
- Steps to reproduce (e.g. sample SCORM package or minimal HTML/JS if relevant)
- Whether you believe the issue affects only local browser processing or also the hosted site

## Scope notes

- Processing is **client-side** in the user’s browser; there is no server-side storage of uploads in this project’s design.
- Third-party scripts (e.g. JSZip, PDF.js) are loaded from a CDN as referenced in `index.html`; reports about those libraries may be forwarded upstream.

## Response

Maintainers will acknowledge receipt when possible and coordinate a fix and disclosure timeline. This is a small open-source project; please allow reasonable time for triage.
