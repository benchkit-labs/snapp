# SNapp

**A context-aware browser extension for ServiceNow.** Right-click any record form to copy richly formatted links or inject standard change templates, and let SNapp surface URLs and email contacts from form fields automatically in the Related Links panel.

**Supports:** Chrome, Edge, Firefox (Manifest V3) · MIT-licensed

> ⚠️ **Status: in revival.** This public repo currently holds the basics —
> license, manifests, store assets, and the landing page. The extension source
> is being brought back into shape and will land here when it's working again.
> Until then there's nothing to install. Watch the repo to know when it ships.

## What it does

- **Extracted Links** — scans form fields and lists discovered URLs in the Related Links panel, with friendly labels (GitHub, Jira, Confluence, Microsoft, ServiceNow `.do` records, or the bare hostname).
- **Email Contacts** — turns discovered email addresses into labeled `mailto:` links.
- **Right-click menu** — copy a canonical `nav_to.do` record link, optionally with the record's short description; emit change-request metadata; or inject a standard change template.

All of it runs locally in the browser on `*.service-now.com` pages. No accounts, no analytics, no servers.

## Install

Once it ships, SNapp will be available from the browser stores:

- Chrome Web Store — _coming soon_
- Firefox Add-ons — _coming soon_
- Edge Add-ons — _coming soon_

## Landing page

[snapp.benchkit-labs.dev](https://snapp.benchkit-labs.dev/)

## License

MIT — see [LICENSE](LICENSE). Free to use, modify, and distribute.

---

Part of [Benchkit Labs](https://benchkit-labs.dev) · [github.com/benchkit-labs](https://github.com/benchkit-labs)
