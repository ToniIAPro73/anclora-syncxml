<!-- markdownlint-disable MD001 MD013 MD033 MD041 MD060 -->

<div align="center">

<img src="./public/brand/anclora-syncxml.png" alt="Anclora SyncXML" width="132" />

# Anclora SyncXML

### Secure conversion from Excel bookings to per-reservation XML

Pre-MVP premium product that transforms hospitality booking spreadsheets into normalized, per-reservation XML files ready for required reporting systems.

[Español](./README.md) · **English** · [Deutsch](./README.de.md)

<br />

![Anclora](https://img.shields.io/badge/Anclora-ecosystem-111827)
![Category](https://img.shields.io/badge/category-Premium-C07860)
![Languages](https://img.shields.io/badge/languages-ES%20%7C%20EN%20%7C%20DE-047857)

</div>

---

> [!IMPORTANT]
> Internal Anclora ecosystem repository. Product in **pre-MVP** stage. Do not publish operational details, credentials, or sensitive logic outside authorized channels.

## What it is

Anclora SyncXML converts hospitality booking Excel sheets into individual per-reservation XML files, with data validation and a controlled download flow. It is designed to simplify accommodation reporting compliance from common industry data sources.

## Category in the ecosystem

| Field | Value |
|---|---|
| Category | Premium |
| Status | Pre-MVP |
| Brand accent | `#BFA46A` |
| Typography | DM Sans |
| Canonical repository | `anclora-syncxml` |

## Key features

- Excel booking import and parsing (ExcelJS)
- Per-reservation XML generation (fast-xml-parser)
- ZIP-packaged download (JSZip)
- Persistence with Prisma
- File storage on Vercel Blob
- Email notifications (Resend)

## Technology stack

| Area | Technology |
|---|---|
| Framework | Next.js, React |
| Database | Prisma |
| Data processing | ExcelJS, fast-xml-parser, JSZip |
| Storage | Vercel Blob |
| Email | Resend |
| Testing | Testing Library, Jest DOM |

## Local setup

```bash
npm install
npm run dev
```

## Supported languages

- Español (default)
- English
- Deutsch

## Documentation and governance

- Brand and governance contracts: [`docs/standards/`](./docs/standards/)
- Anclora Vault (source of truth): `contracts/` and `docs/governance/`

---

<div align="center">

### Anclora Group

Internal use.

</div>
