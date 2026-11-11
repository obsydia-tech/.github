# Obsydia Technologies

**Core0** is a self-hosted vault for personal data. Your application stores a token; the value lives in Core0, on machines you own, encrypted per record, with the keys on separate nodes and the master key split into shares that only you hold. There is no telemetry, no remote licence check and no vendor endpoint in the request path.

> Data that doesn't exist can't be stolen.

## What is published here

The parts of Core0 that let you check our claims without taking them on trust:

| Repository | What it is | Status |
| --- | --- | --- |
| verify-audit | Verifier for Core0's hash-chained audit log, the encrypted copy and the anchor mails | coming |
| licence verification | How Core0 checks its licence: an ECDSA P-256 signature against a public key, with no network call | coming |
| installers and network rules | The install scripts and the firewall rules they apply | coming |

The core services stay closed for now. Their source is available to auditors on request.

## Read first

- [Documentation](https://obsydia.tech/docs) — security reference, API, audit log, restart and unseal, measured failure behaviour, backup and restore, updates
- [Architecture and trust model](https://obsydia.tech/core0/architecture) — what each part of the system can see, and what the design does not defend against
- [Technical whitepaper](https://obsydia.tech/whitepaper)
- [Community Edition](https://obsydia.tech/core0/community) — free, single node, for testing

## Security

To report a vulnerability, see [SECURITY.md](https://github.com/obsydia-tech/.github/blob/main/SECURITY.md).

[obsydia.tech](https://obsydia.tech) · hello@obsydia.tech
