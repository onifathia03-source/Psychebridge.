# PsycheBridge

A responsive, installable website starter for psychosocial developmental assessment.

## Files
- `index.html`: application
- `manifest.webmanifest`: installable web app metadata
- `service-worker.js`: offline app-shell caching
- `icons/`: app icons

## Run locally
For a quick preview, open `index.html` in a browser. Client-side records are saved in that browser's local storage.

## Install as an app
To enable the install prompt / Add to Home Screen, publish the folder to an HTTPS static host (for example, a private deployment on a hosting provider). Then:
- iPhone/iPad: open the HTTPS site in Safari → Share → Add to Home Screen.
- Android: open in Chrome → menu → Install app / Add to Home screen.
- Laptop: use the browser's Install icon or menu where supported.

## Important privacy and professional limitations
This starter app stores data locally in browser local storage. It does not provide encryption at rest, user accounts, role-based access, secure cloud backup, audit logs, or server-side data protection. Do not store identifiable or sensitive real-client information until a qualified developer has implemented appropriate security, consent, retention, backup, and applicable data-protection requirements. Use pseudonymous client codes for testing.

The Erikson prompts are original reflective interview prompts inspired by the eight psychosocial themes. They are not a validated psychometric instrument, do not produce clinical scores, and must not be used to diagnose or label a client or determine that a developmental stage was failed. Use professional judgement, supervision, and appropriate validated tools where needed.
