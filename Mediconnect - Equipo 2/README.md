# MediConnect — Sistema de Gestión de Clínica Médica

> Proyecto académico | Análisis y Diseño de Sistemas  
> Universidad Abierta Para Adultos — Escuela de Ingeniería y Tecnología  
> Autor: **Natanael Mateo** — 100089414  
> Facilitador/a: Joah ML Gregorio Pérez

---

## Descripción

**MediConnect** es una plataforma integral de gestión de clínica médica que digitaliza y automatiza los procesos de agendamiento de citas, historial clínico, facturación y reportes estadísticos para clínicas privadas.

---

## Estructura del Repositorio

```
MediConnect-EquipoX/
├── docs/
│   ├── hito1/          ← Visión del proyecto, stakeholders, requerimientos
│   ├── hito2/          ← Diagramas UML, MER, diccionario de datos, informe de avance
│   ├── hito3/          ← Diagramas de estructura, prototipo, análisis de costos
│   └── hito4/          ← Documento final (PDF), presentación (PPTX), enlaces
│
├── diagramas/
│   ├── casos-de-uso/   ← CU-GestionCitas.drawio, CU-HistorialFact.drawio
│   ├── actividades/    ← ACT-AgendamientoCita.drawio, ACT-ConsultaFact.drawio
│   ├── secuencia/      ← SEQ-SolicitudCita.drawio, SEQ-RegistroConsulta.drawio
│   ├── clases/         ← DC-MediConnect.drawio
│   └── mer/            ← MER-MediConnect.drawio
│
├── prototipo/
│   ├── figma-enlace.txt
│   └── capturas/
│
├── README.md
└── .gitignore
```

---

## Cómo abrir los diagramas

Todos los archivos `.drawio` pueden abrirse con:

- **[draw.io (app online)](https://app.diagrams.net/)** — gratis, sin instalación
- **[draw.io Desktop](https://github.com/jgraph/drawio-desktop/releases)** — app de escritorio

---

## Hitos del Proyecto

| Hito | Descripción | Fecha |
|------|-------------|-------|
| Hito 1 | Análisis Inicial y Requerimientos | 11 feb 2026 |
| Hito 2 | Modelado de Procesos y Datos | 04 mar 2026 |
| Hito 3 | Diseño Técnico y Prototipo | 25 mar 2026 |
| Hito 4 | Entrega Final y Presentación | 08 abr 2026 |

---

## Stack Tecnológico Propuesto

| Capa | Tecnología |
|------|-----------|
| Frontend | React 18 + Tailwind CSS |
| Backend | Node.js + Express |
| Base de Datos | PostgreSQL 15 |
| Caché / Sesiones | Redis 7 |
| Autenticación | JWT + Refresh Token |
| Notificaciones | SendGrid (email) + Twilio (SMS) |
| PDF | Puppeteer / PDFKit |
| Contenedores | Docker + Docker Compose |

---

## Módulos del Sistema

- **Gestión de Citas** — agendamiento, confirmación, cancelación y reagendamiento
- **Historial Clínico** — consultas, diagnósticos (CIE-10), recetas y resultados
- **Módulo de Pacientes** — registro y gestión de datos personales
- **Facturación** — generación automática, pagos y PDFs
- **Reportes Estadísticos** — por especialidad, ingresos mensuales, pacientes frecuentes

---

*Documento preparado para la asignatura Análisis y Diseño de Sistemas — UAPA 2026*
