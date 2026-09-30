# CustodyFlow

Defensible DFIR and eDiscovery workflow tools. Every tool runs client-side or with the Python standard library, and each is built around integrity: SHA-256 hashing, chain-of-custody records and tamper-evident logs, so the work can be defended in court.

| Tool | What it does | Try it |
|---|---|---|
| [TraceFlow](https://github.com/ryandus/TraceFlow) | Evidence hash manifests and an ISO/IEC 27037 chain-of-custody ledger | [Live](https://ryandus.github.io/TraceFlow/) |
| [SyncFlow](https://github.com/ryandus/SyncFlow) | CCTV/DVR clock-drift calibration and timeline synchronization (LEVA/SWGDE) | [Live](https://ryandus.github.io/SyncFlow/) |
| [ProdFlow](https://github.com/ryandus/ProdFlow) | Production load-file QC, TAR elusion/recall statistics, matter estimates | [Live](https://ryandus.github.io/ProdFlow/) |

## Shared principles

- **Data stays local:** browser tools make no server uploads.
- **Integrity is verifiable:** SHA-256 hashing and tamper-evident records.
- **Output is reproducible:** the same inputs give the same result.
- **Failures are explicit:** nothing is skipped silently.

## Companion tool

[SupportTriage](https://github.com/ryandus/SupportTriage) is a ticket triage and escalation-package builder for SaaS support and IT operations teams. It is not part of the forensic suite.

## Author

Ryan C. Hanks, digital forensics and eDiscovery. MIT licensed. See [github.com/ryandus](https://github.com/ryandus).
