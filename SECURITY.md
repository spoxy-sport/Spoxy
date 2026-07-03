# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this repository (e.g. an XSS vector in the landing page, a dependency issue, or a misconfigured deploy), please **do not open a public issue**.

Instead:

1. Email the maintainers directly, or use GitHub's [private vulnerability reporting](../../security/advisories/new) if enabled on this repo.
2. Include a clear description of the issue, steps to reproduce, and potential impact.
3. Allow a reasonable amount of time for a fix before any public disclosure.

## Supported Scope

This repository contains a static marketing site only (`index.html`). It does not process payments, private keys, or user funds directly — wallet interactions happen client-side through the user's own wallet extension (e.g. Phantom). Report any issue that could put site visitors at risk (malicious script injection, spoofed wallet-connect prompts, etc.).

## Response

We aim to acknowledge reports within 5 business days and to keep reporters updated as a fix is developed.
