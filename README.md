# Hola, soy Martín Malgor

> Estudiante de Ingeniería en Sistemas. Aprendo haciendo, comparto lo que me hubiese gustado saber. Código, sistemas, automatización y café.

<p align="left">
  <a href="https://x.com/techconmartin"><img alt="X / Twitter" src="https://img.shields.io/badge/@techconmartin-111111?logo=x&logoColor=white&labelColor=111111"></a>
  <a href="https://www.linkedin.com/in/martin-malgor-6b3824186/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-8B5E34?logo=linkedin&logoColor=white&labelColor=8B5E34"></a>
</p>

<!--
PALETA
- Fondo: #FAFAFA
- Texto: #111111
- Acento marrón: #8B5E34
- Pastel secundario: #E6D5C3
-->

---

## Proyectos destacados

> Mantengo esta sección simple por ahora. Más adelante la haremos “viva” con métricas y highlights automáticos.

### 1) dsw-2025 — Plataforma logística (UTN FRRe)

**Stack:** Next.js (frontend) · NestJS (backend, microservicios)

* **Repo:** [https://github.com/martinmalgor04/dsw-2025](https://github.com/martinmalgor04/dsw-2025)
* **Demo (frontend):** [http://logistica.mmalgor.com.ar](http://logistica.mmalgor.com.ar)

**Qué aporta:** app académica con arquitectura moderna (Next + Nest), base para productizar módulos.

---

### 2) tcmanagementweb — Sitio para agencia de management TC (Corrientes, AR)

**Stack:** Next.js · Sanity (CMS) · Formspree (forms)

* **Repo:** [https://github.com/martinmalgor04/tcmanagementweb](https://github.com/martinmalgor04/tcmanagementweb)

**Qué aporta:** marketing site editable por CMS, formularios funcionales y despliegue rápido.

---

### 3) n8n: Study Sessions (WIP)

**Idea:** automatización para crear sesiones de estudio (planificación + tracking).

* **Repo (WIP):** subiremos pronto el flujo exportado de **n8n** con README de uso.
* **Roadmap corto:** export del workflow, variables de entorno, receta de despliegue, y ejemplo con Notion/Google Calendar.

---

## Cómo trabajo / Intereses

<p>
  <img alt="Aprendo haciendo" src="https://img.shields.io/badge/Aprendo%20haciendo-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Documentación clara" src="https://img.shields.io/badge/Documentación%20clara-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Automatización" src="https://img.shields.io/badge/Automatización-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="IA aplicada" src="https://img.shields.io/badge/IA%20aplicada-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Colaboración" src="https://img.shields.io/badge/Colaboración-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Aprendizaje continuo" src="https://img.shields.io/badge/Aprendizaje%20continuo-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Construyo en público" src="https://img.shields.io/badge/Construyo%20en%20público-E6D5C3?style=flat&labelColor=E6D5C3&color=E6D5C3">
  <img alt="Café" src="https://img.shields.io/badge/Café%20☕-8B5E34?style=flat&labelColor=8B5E34&color=8B5E34&logo=coffeescript&logoColor=white">
</p>

---

## Coffee counter (placeholder)

> Este contador es estático por ahora. Lo dejé con **marcadores** para que un workflow (n8n/GitHub Action) lo actualice automáticamente.

**Cafés hoy:** <!-- COFFEE_COUNTER_START -->0<!-- COFFEE_COUNTER_END --> ☕

![Cafés badge](https://img.shields.io/badge/cafés%20hoy-0-8B5E34?style=flat\&labelColor=8B5E34)

**Hook técnico (comentado):**

```html
<!--
Buscar entre marcadores COFFEE_COUNTER_START y COFFEE_COUNTER_END y reemplazar solo el número.
Ejemplo pseudo:

1) n8n obtiene el total (por ejemplo, de un Google Sheet o Notion).
2) n8n lee README.md, hace regex para /(<!-- COFFEE_COUNTER_START -->)(\d+)(<!-- COFFEE_COUNTER_END -->)/ y reemplaza con el nuevo número.
3) Commit push al repo si cambia.
-->
```

---

## Actualmente aprendiendo

Next.js · NestJS · TypeScript · n8n · (abierto a colaboraciones y feedback)

---

## Siguientes pasos (para la versión “cool”)

* Banners `<picture>` con variantes para **modo claro/oscuro**.
* Tarjetas dinámicas: últimos posts/threads y highlights (Twitter/LinkedIn).
* Métricas vivas: WakaTime, contribuciones, repos activos.
* Sección “Builds IA & automations” con casos pequeños y GIFs.

---

### Nota para automatización (n8n)

* Programar job diario para refrescar `Coffee counter` y “Currently learning”.
* Exportar flujo `Study Sessions` y documentar variables (`.env` / credenciales).
* (Opcional) GitHub Action que ejecute un script de formateo antes del commit.

---

<p align="center">
  <sub>Hecho con ☕ y ganas de aprender. ¿Ideas o feedback? Abrí un issue en este repo.</sub>
</p>
