# ProtoConsent Demo

<p align="center">
  <img src="https://github.com/ProtoConsent/ProtoConsent/blob/main/design/assets/logo/protoconsent_logo.png" alt="ProtoConsent logo" width="160">
</p>

<p align="center"><strong>Consent you can express, enforce and observe</strong></p>

<p align="center"><em>User‑side, purpose‑based consent for the web</em></p>

Demo site for the [ProtoConsent](https://github.com/ProtoConsent/ProtoConsent) browser extension, hosted at [demo.protoconsent.org](https://demo.protoconsent.org).

## What this site does

- Publishes a complete [`.well-known/protoconsent.json`](.well-known/protoconsent.json) declaration with all protocol fields: purposes, legal bases, providers, sharing scopes, data handling, and rights URL.
- Provides a live SDK test that queries the extension for your current preferences.
- Checks whether the [GPC signal](https://globalprivacycontrol.org/) (`navigator.globalPrivacyControl`) is active on this page.

All data is fictional (Acme Corp). The site is meant for testing the extension.

## Hosting

Static site served via GitHub Pages — no build step, no dependencies. The `.nojekyll` file ensures the `.well-known` directory is served correctly.

## Links

- **Main repository**: [github.com/ProtoConsent/ProtoConsent](https://github.com/ProtoConsent/ProtoConsent)
- **Project website**: [protoconsent.org](https://protoconsent.org)
- **Chrome Web Store**: [Install ProtoConsent](https://chromewebstore.google.com/detail/protoconsent/dkcdkdcclhofocmkecccmikkfmfgfdlb)
- **`.well-known` spec**: [protoconsent-well-known.md](https://github.com/ProtoConsent/ProtoConsent/blob/main/design/spec/protoconsent-well-known.md)
