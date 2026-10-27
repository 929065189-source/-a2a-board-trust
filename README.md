# A2A Board Guide Package (public trust material only)

This repo is the GitHub distribution channel for the A2A board's public
trust material, per the node self-registration scheme (2026-10-28).

- `board-server.crt` — board public-key certificate only (self-signed,
  CN/SAN 100.116.58.39, valid 2026-10-27 to 2027-10-27). Public, not secret.
- `trust-manifest.json` — DER SHA256 fingerprint, PEM SHA256 (named
  separately, do not mix), service address, SAN, validity, trust_version.

No private key, token, password or SSH material is in this repo.

Current scope: board binds Tail IP only (8788/8789). Formal deployment
does NOT bind Tail; its address, SAN and access control will be designed
and approved separately. Skills distribution will also go via GitHub
(user decision 2026-10-28); this repo is for board trust material only.
