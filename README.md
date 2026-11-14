# ProTech Quotes & Contracts v2.0.0-beta.3

![All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)
![Version](https://img.shields.io/badge/Version-2.0.0--beta.3-blue.svg)
![Platform](https://img.shields.io/badge/Windows-10%2F11%20x64-blue.svg)

ProTech Quotes & Contracts is a standalone Windows desktop application for Arabic quotation and contract templates, client/project records, pricing, inventory, payments, and PDF/DOCX/XLSX/CSV reporting.

## Installation and verified downloads
[Download Setup.exe directly](https://github.com/Abdealmalk007/ProTechQuotesContracts/releases/download/v2.0.0-beta.3/Setup.exe) from the official [v2.0.0-beta.3 GitHub Release](https://github.com/Abdealmalk007/ProTechQuotesContracts/releases/tag/v2.0.0-beta.3).
Windows 10/11 x64; Python installation is unnecessary. Verify the file against [SHA256SUMS.txt](SHA256SUMS.txt).
**This beta installer is NOT digitally signed.** Windows SmartScreen may display a warning.

## Features
- Customizable Arabic contract and quotation templates.
- Customer and project management, measurements, quotations, stock, production, and installation.
- Beta.3 Customer RC3: required customer name and address, normalized Saudi mobile, searchable customer dossier and immutable issued-document snapshots.
- Payments, commercial (non-tax) receipts and customer statements.
- Report preview, printing, PDF, Word, Excel, and CSV exports.
- Restores the last working screen; SHA256-verified ZIP backups with safe restore.
- Version 2 uses its own data path at %LOCALAPPDATA%/ProTech/QuotesContractsV2, separate from v1.1.0.

## Limitations and QA
Beta only. Official ZATCA tax invoicing is not yet available. Unverifiable costs do not generate estimated profit figures.
The verified RC3 QA record reports 212/212 Python regression tests, 14/14 frozen EXE checks, and 14/14 each for clean install and same-version upgrade, with uninstall passed. SHA256 is verified; both the installer and application remain Authenticode NotSigned and final third-party redistribution approval is pending.

## Copyright and third-party components
Copyright (c) 2026 ProTech / Abu Omar. All Rights Reserved.
The [LICENSE](LICENSE) is a proprietary notice for original ProTech-owned materials in this new release, not for third-party components. Read [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt). Existing MIT grants for earlier releases, if applicable, are not revoked.
A limited end-user installation permission is set out in [BINARY_USAGE_TERMS.md](BINARY_USAGE_TERMS.md). There is NO source-code distribution here.

## Documentation and support
- [Arabic README](README_AR.md)
- [Beta.3 release notes and QA limitations](RELEASE_NOTES_BETA3_AR_EN.md)
- [Preliminary third-party compliance status](THIRD_PARTY_COMPLIANCE_STATUS.md)
- [Historical Beta.2 notes](RELEASE_NOTES_AR.md)
- [Security policy](SECURITY.md)
- https://alghad.digital
- protech.2025.2026@gmail.com

No embedded MCP Server compatibility is claimed without verification.
