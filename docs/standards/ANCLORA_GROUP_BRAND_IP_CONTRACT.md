---
title: ANCLORA_GROUP_BRAND_IP_CONTRACT
type: standard
estado: activo
scope: brand-ip
tags: [branding, legal, intellectual-property, anclora, contract]
related:
  - "[[ANCLORA_BRANDING_MASTER_CONTRACT]]"
  - "[[ANCLORA_ECOSYSTEM_CONTRACT_GROUPS]]"
  - "[[LOCALIZATION_CONTRACT]]"
---

# ANCLORA_GROUP_BRAND_IP_CONTRACT

## Estado

Contrato transversal de marca, titularidad de activos intangibles e identidad legal del ecosistema Anclora Group.

Estado legal: marca matriz en proceso de registro / pendiente de validación legal final.

> [!warning] Validación legal
> Este contrato documenta criterios operativos de marca y propiedad intelectual para la Bóveda Anclora. No sustituye revisión legal profesional ni resolución registral. No debe afirmarse que la marca está registrada salvo evidencia documental explícita.

## Entidad matriz

La entidad de referencia para titularidad, operación y propiedad intelectual del ecosistema es:

**Anclora Group**

Cuando se haga referencia a titularidad de derechos, datos, marca, activos intangibles, contenidos, interfaces, productos, documentos o experiencia de usuario, debe usarse **Anclora Group** y no "Anclora" como entidad legal independiente.

## Copyright general

Fórmula canónica para footers:

```txt
© {currentYear} Anclora Group — Todos los derechos reservados.
```

Reglas:

- Usar año dinámico siempre que el framework lo permita.
- Si el componente exige string estático, usar el año de despliegue vigente y documentar la razón.
- No usar "Anclora" como titular jurídico aislado.
- No usar nombres personales como titulares de producto salvo documentación legal específica.

## Declaración de marca derivada

Fórmula canónica:

```txt
[Nombre de la Aplicación] forma parte del ecosistema tecnológico de Anclora Group.
```

> [!note] Actualización 2026-05-17
> La fórmula anterior `"operada bajo licencia exclusiva"` fue reemplazada por la fórmula prudente actual.
> Motivo: el estado registral de la marca matriz está pendiente de validación legal final;
> afirmar "licencia exclusiva" implica un acuerdo formal que no está documentado como concedido.
> La fórmula vigente es neutral y coherente con el estado real del ecosistema.

Reglas:

- El nombre de aplicación debe extraerse de `package.json`, metadatos de marca o configuración canónica del repo.
- Si el nombre público difiere del nombre técnico, usar el nombre público documentado.
- La frase debe aparecer preferentemente bajo el copyright, en tipografía secundaria/caption.
- La frase debe adaptarse por idioma cuando existan locales.
- No usar "marca registrada", "licencia exclusiva" ni "registro concedido" sin evidencia documental explícita.

## Titularidad de activos intangibles

Anclora Group debe figurar como titular y operador de:

- Nombres comerciales.
- Marcas derivadas.
- Identidad visual.
- Logos.
- Copy de producto.
- Interfaz de usuario.
- Contratos UX/UI.
- Documentación pública.
- Playbooks.
- Prompts maestros.
- Agentes de contenido del ecosistema.
- Informes generados por las apps, salvo derechos de terceros o datos aportados por usuarios.

## Marcas derivadas

Las apps del ecosistema se consideran marcas, productos o módulos derivados de Anclora Group cuando la Bóveda las clasifique dentro del perímetro Anclora Group.

Ejemplos:

- Anclora Private Estates.
- Anclora Nexus.
- Anclora Data Lab.
- Anclora Synergi.
- Anclora EnergyScan.
- Anclora Content Generator AI.
- Hermes Copy Curator / Hermes-Agent.
- Anclora Talent.
- Anclora Impulso.
- Anclora Command Center.
- Anclora Portfolio.
- Regla183 / Calculadora Fiscal 183 solo si la Bóveda la clasifica explícitamente dentro del perímetro de explotación de Anclora Group.

## Reglas de i18n

Cuando una app tenga ES/EN/DE, traducir las fórmulas legales en todos los idiomas disponibles.

ES:

```txt
© {currentYear} Anclora Group — Todos los derechos reservados.
[Nombre de la Aplicación] forma parte del ecosistema tecnológico de Anclora Group.
```

EN:

```txt
© {currentYear} Anclora Group — All rights reserved.
[Application Name] is part of the Anclora Group technology ecosystem.
```

DE:

```txt
© {currentYear} Anclora Group — Alle Rechte vorbehalten.
[Anwendungsname] ist Teil des technologischen Ökosystems von Anclora Group.
```

## Reglas de diseño

- En footer, la declaración de marca derivada debe usar estilo caption, small text o microcopy legal.
- Debe respetar tokens del Design System aplicable.
- No debe competir visualmente con CTAs ni navegación principal.
- No debe introducir ruido visual en experiencias ultra premium.
- Debe mantener contraste accesible.

## Reglas de adopción por repositorio

Cada repo consumidor debe revisar:

- Footer.
- Páginas legales.
- Metadata SEO.
- Contratos de marca locales.
- README si declara titularidad.
- Documentación pública.
- PDFs o documentos exportables si incluyen copyright.
- Locales i18n.

## Familias consumidoras

Este contrato es transversal y lo consumen:

- Entidad Matriz.
- Premium.
- Internal.
- Ultra Premium.
- Portfolio / Showcase.
- Activation cuando exista como familia o superficie operativa.
- Independientes solo si la Bóveda los clasifica explícitamente dentro del perímetro de explotación de Anclora Group.

## Criterio de cumplimiento

- `NOT_STARTED`: no auditado.
- `PARTIAL`: contrato conocido pero no aplicado en todas las superficies.
- `ADOPTED`: footers y legales principales actualizados.
- `VALIDATED`: revisión completa por repo, incluyendo i18n y documentos exportables.
- `UNKNOWN`: repo o superficie no disponible para auditoría.

## Restricciones

- No afirmar registro concedido si solo hay solicitud en curso.
- No eliminar disclaimers sectoriales de cada producto.
- No sustituir textos legales específicos por copy genérico.
- No romper i18n.
- No atribuir titularidad de marcas de terceros a Anclora Group.
- No modificar backups de Windows; solo sirven como referencia de lectura salvo instrucción explícita.

## Relacionado

- [[ANCLORA_BRANDING_MASTER_CONTRACT]]
- [[ANCLORA_ECOSYSTEM_CONTRACT_GROUPS]]
- [[LOCALIZATION_CONTRACT]]
- [[HERMES_COPY_CURATOR_CONTRACT]]
