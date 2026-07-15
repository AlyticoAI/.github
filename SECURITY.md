# Security Policy

This is a private AlyticoAI repository. Please do not open a public GitHub
issue for a suspected vulnerability or credential leak.

## Reporting

Email [security contact to be filled in] with:
- A description of the issue and its potential impact
- Steps to reproduce, if applicable
- Any relevant logs or affected commits/files

We will acknowledge within 2 business days.

## Scope

This applies to this repository and any AlyticoAI-owned repository under the
[AlyticoAI GitHub organization](https://github.com/AlyticoAI).

## Handling leaked credentials

If you discover a committed secret (API key, password, token) in git
history:
1. Do not open a public issue describing it.
2. Notify a Code Owner directly.
3. The credential must be rotated at the source (AWS/GCP/etc.), not just
   removed from the current file — git history retains it until purged.
