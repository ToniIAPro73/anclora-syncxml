<!-- markdownlint-disable MD001 MD013 MD033 MD041 MD060 -->

<div align="center">

<img src="./public/brand/anclora-syncxml.png" alt="Anclora SyncXML" width="132" />

# Anclora SyncXML

### Conversión segura de reservas Excel a XML por reserva de hospedaje

Producto premium en fase pre-MVP que transforma hojas de cálculo de reservas de alojamiento en ficheros XML normalizados, por reserva, listos para los sistemas de reporte requeridos.

**Español** · [English](./README.en.md) · [Deutsch](./README.de.md)

<br />

![Anclora](https://img.shields.io/badge/Anclora-ecosystem-111827)
![Categoría](https://img.shields.io/badge/categoría-Premium-C07860)
![Idiomas](https://img.shields.io/badge/idiomas-ES%20%7C%20EN%20%7C%20DE-047857)

</div>

---

> [!IMPORTANT]
> Repositorio interno del ecosistema Anclora. Producto en fase **pre-MVP**. No publicar detalles operativos, credenciales ni lógica sensible fuera de canales autorizados.

## Qué es

Anclora SyncXML convierte hojas Excel de reservas de hospedaje en ficheros XML individuales por reserva, con validación de datos y flujo de descarga controlado. Está pensado para simplificar el cumplimiento de reporte de alojamiento a partir de fuentes de datos habituales del sector.

## Categoría en el ecosistema

| Campo | Valor |
|---|---|
| Categoría | Premium |
| Estado | Pre-MVP |
| Acento de marca | `#BFA46A` |
| Tipografía | DM Sans |
| Repositorio canónico | `anclora-syncxml` |

## Funcionalidades principales

- Importación y parseo de Excel de reservas (ExcelJS)
- Generación de XML por reserva (fast-xml-parser)
- Descarga empaquetada en ZIP (JSZip)
- Persistencia con Prisma
- Almacenamiento de ficheros en Vercel Blob
- Notificaciones por email (Resend)

## Stack tecnológico

| Área | Tecnología |
|---|---|
| Framework | Next.js, React |
| Base de datos | Prisma |
| Procesado de datos | ExcelJS, fast-xml-parser, JSZip |
| Almacenamiento | Vercel Blob |
| Email | Resend |
| Testing | Testing Library, Jest DOM |

## Arranque local

```bash
npm install
npm run dev
```

## Idiomas soportados

- Español (predeterminado)
- English
- Deutsch

## Documentación y gobernanza

- Contratos de marca y gobernanza: [`docs/standards/`](./docs/standards/)
- Bóveda Anclora (fuente de verdad): `contracts/` y `docs/governance/`

---

<div align="center">

### Anclora Group

Uso interno.

</div>
