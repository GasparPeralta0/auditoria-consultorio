# Auditoría de Seguridad ISO 27001 — Consultorio Médico

Herramienta de auditoría de seguridad de la información para consultorios médicos pequeños, desarrollada como
proyecto de práctica dentro de mi formación como **ISO 27001 Lead Auditor (PECB)**.

Combina un checklist interactivo de 33 controles (basados en el Anexo A de ISO/IEC 27001:2022) con la
normativa argentina aplicable al sector salud, y genera un informe ejecutivo profesional con matriz de riesgo
y radar de madurez.

## Qué incluye este repositorio

- **`herramienta/`** — El checklist interactivo (HTML/JS, sin dependencias), organizado en 7 categorías:
  datos de pacientes, accesos y usuarios, copias de seguridad, equipos y red, seguridad física, gestión de
  incidentes y cumplimiento legal. Cada control incluye referencia a ISO 27001, normativa argentina, escala
  de madurez (0-3) y campo de observación.
- **`plantillas/`** — Modelo en blanco del acuerdo de confidencialidad y alcance de servicios (NDA) que se
  firma con el consultorio antes de iniciar cualquier relevamiento.
- **`ejemplo/`** — Una guía de campo y un informe ejecutivo completos, generados con datos ficticios, para
  mostrar el formato y el nivel de detalle del entregable final sin exponer información de ningún caso real.

## Metodología

- **ISO/IEC 27001:2022** — Anexo A como marco de controles.
- **Ley 25.326** — Protección de Datos Personales (Argentina).
- **Ley 26.529** — Derechos del Paciente en su Relación con los Profesionales e Instituciones de Salud.

Cada hallazgo del informe cruza dos ejes — **impacto** (según la naturaleza del control) y **probabilidad**
(derivada de la madurez relevada en el relevamiento) — para priorizar el plan de acción de forma objetiva.

## Nota de confidencialidad

Todo relevamiento real se realiza bajo el acuerdo de confidencialidad incluido en `plantillas/`, firmado por
ambas partes antes de comenzar. Los informes reales generados con esta herramienta son de uso exclusivo del
cliente y no se publican ni comparten — el ejemplo en `ejemplo/` usa datos ficticios de principio a fin.

## Autor

**Gaspar Peralta** — Auditor en formación ISO 27001 Lead Auditor (PECB)
Punta Alta, Argentina · gaspar.peralta.sec@gmail.com
