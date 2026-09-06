<div align="center">

<img src="darknezz-logo.png" alt="Darknezz" width="56" height="56" />

# Gerardo Erick Plasencia Torres
### Analista de Desarrollo & Sysadmin | Full Stack Developer

[![Portafolio](https://img.shields.io/badge/Portafolio-darknezz.dev-ff4d4d?style=for-the-badge&logo=googlechrome&logoColor=white)](https://darknezz.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gerardo_Plasencia-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gerardo-plasencia)
[![Email](https://img.shields.io/badge/Email-gerardo@darknezz.dev-101313?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:gerardo@darknezz.dev)
[![GitHub](https://img.shields.io/badge/GitHub-YamiDarknezz-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YamiDarknezz)

</div>

---

## 🚀 Perfil Profesional

Ingeniero de software y Sysadmin enfocado en la **construcción de sistemas en producción, infraestructura segura sobre Linux y pipelines de datos de alto rendimiento**. 

Actualmente en **Pauser Distribuciones SAC** (Área de Mejora Continua), donde asumí la gobernanza integral del servidor de producción (Ubuntu 24.04 LTS con 30+ contenedores bajo Docker, Dokploy y Traefik) y diseñé el ecosistema de microservicios corporativos: autenticación centralizada (**AuthOps**), telemetría de flotas vehiculares (**MechGuard**), portal web unificado (**Frontend-Central**) y motor de ingesta de datos (**Pauser Maestros**), además de pipelines ETL hacia **Power BI** y automatizaciones operativas con **n8n**, **Power Automate** y bots de mensajería.

- 🎓 **Formación:** Estudiante de último ciclo de Ingeniería de Sistemas Computacionales (egreso Dic 2026) en la Universidad Privada del Norte.
- 📜 **Certificaciones Oficiales Cisco:** Hacker Ético, CCNA 2 (SRWE), CCNA 1 (ITN) y Cybersecurity Essentials.
- 📍 **Disponibilidad:** Remoto / Híbrido / Presencial (Trujillo / Lima, Perú).

---

## 🏆 Proyectos Destacados

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [darknezz-infra](https://github.com/YamiDarknezz/darknezz-infra)
**Infraestructura como Código (IaC) & Server Hardening**

Línea base de aprovisionamiento y endurecimiento para servidores Linux en producción:
- Reverse proxy perimetral con **Traefik v3** y SSL wildcard automático (`*.darknezz.dev`) vía Cloudflare DNS API.
- Orquestación de contenedores mediante **Dokploy** y Docker Compose.
- Hardening en capas: UFW estricto, llaves SSH Ed25519 exclusivas (sin root/passwords), Fail2ban activo y observabilidad con **Prometheus** y **Grafana**.

```bash
Stack: Docker · Traefik v3 · Dokploy · Linux Ubuntu · Cloudflare DNS · Prometheus · Grafana
```
🔗 **[Ver Repositorio](https://github.com/YamiDarknezz/darknezz-infra)**

</td>
<td width="50%" valign="top">

### 📦 [inventory-api](https://github.com/YamiDarknezz/inventory-api)
**API REST Empresarial con Spring Boot 3 & Java 21**

Servicio backend de gestión de inventarios y control de stock bajo estándares de ingeniería de software:
- Autenticación segura mediante **JWT** con control de acceso basado en roles (**RBAC**).
- Validación estricta de DTOs, manejo global de excepciones y persistencia relacional en **PostgreSQL**.
- Documentación viva e interactiva desplegada en producción con **Swagger / OpenAPI**.

```bash
Stack: Java 21 · Spring Boot 3 · PostgreSQL · Spring Security · JWT · Swagger UI · Docker
```
🔗 **[Ver Repositorio](https://github.com/YamiDarknezz/inventory-api)** · 🌐 **[Swagger en Vivo](https://api-inventory.darknezz.dev/swagger-ui/index.html)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ Pauser Maestros (Extractor Maestro)
**Motor ETL Multi-Proveedor & Replicación de Datos**

Middleware de ingesta de alto rendimiento para desacoplar proveedores externos críticos:
- Ingesta incremental desde el ERP corporativo (Progress OpenEdge/ODBC), combustible Primax y telemetría de flotas ProGPS.
- Aislamiento de licencias mediante `asyncio.Semaphore` y procesamiento vectorial en memoria con DataFrames de **Polars**.
- Upserts atómicos en **PostgreSQL**, reduciendo tiempos de consulta de >8s a **<15ms** para todos los microservicios satélite.

```bash
Stack: Python · FastAPI · Polars · PostgreSQL · asyncio · Progress OpenEdge · Docker
```
📖 **[Ver Caso de Estudio en darknezz.dev](https://darknezz.dev)** *(Código propietario Pauser)*

</td>
<td width="50%" valign="top">

### 🌐 [Darknezz.dev](https://darknezz.dev)
**Portafolio Web Reactivo & Hub de Arquitectura**

Single Page Application construida con los últimos estándares del ecosistema frontend:
- Arquitectura pura en **Angular 21** con Standalone Components, **Signals & LinkedSignal**.
- Diseño modular con **Tailwind CSS v4**, micro-interacciones suaves con GSAP y soporte PWA.
- Fichas técnicas interactivas y casos de estudio detallados de arquitectura y resiliencia.

```bash
Stack: Angular 21 · TypeScript · Signals · Tailwind CSS v4 · GSAP · PWA
```
🌐 **[Explorar Sitio Web](https://darknezz.dev)** · 📄 **[Descargar CV](https://darknezz.dev/CV_Gerardo_Plasencia.pdf)**

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológico

| Capa | Tecnologías |
| :--- | :--- |
| **Backend & APIs** | Python, FastAPI, Java 21, Spring Boot 3, Flask, RESTful APIs, JWT, RBAC Jerárquico, SQLAlchemy, Alembic, Node.js |
| **Frontend** | Angular 21+, TypeScript, Angular Signals & LinkedSignal, Standalone Components, RxJS, Tailwind CSS v4, SCSS, PWA |
| **Datos & Storage** | PostgreSQL, SQL Server, Redis (Caché & Colas), Polars (Vectorial en Memoria), Supabase, MinIO (S3 Object Storage) |
| **DevOps & Sysadmin** | Linux Server (Ubuntu 24.04 LTS), Docker, Dokploy PaaS, Traefik v3, UFW Firewall, Fail2ban, Cloudflare DNS, GitHub Actions (CI/CD) |
| **BI & Automatización** | Power BI (Modelado & DAX), Power Automate, n8n Workflows, Evolution API (WhatsApp Business), Telegram Bots |
| **Redes & Seguridad** | Cisco CCNA (Routing & Switching), Cisco Cybersecurity Essentials, Hacker Ético, VLANs, SSH Hardening |

---

## 💼 Experiencia Laboral

```text
Pauser Distribuciones S.A.C. | Trujillo, Perú (12 sedes operativas)
├── Analista de Desarrollo de Software & Sysadmin ────────────── [Jul 2026 — Actualidad]
│   • Gobernanza del servidor VPS (Ubuntu 24.04 LTS) con 30+ contenedores bajo Dokploy y Traefik.
│   • Arquitectura de microservicios: AuthOps (IAM Centralizado), MechGuard (Flota), Pauser Maestros (ETL).
│   • Pipelines de ingesta desde ERP, Excel y SharePoint hacia PostgreSQL; dashboards ejecutivos en Power BI.
│   • Automatización de alertamiento temprano y reportes operativos vía Power Automate, n8n y WhatsApp bots.
│
└── Trainee de Desarrollo de Software (Part-Time) ────────────── [Ene 2026 — Jun 2026]
    • Migración planificada de servidor Linux desde versiones legadas a Ubuntu 24.04 LTS sin caídas de servicio.
    • Despliegue de plataforma PaaS con Dokploy y Traefik; desarrollo inicial de AuthOps y MechGuard.

Clínica Ocupacional MedCorp S.A.C. | Lima, Perú
└── Pasante en Desarrollo de Software ────────────────────────── [Ago 2025 — Nov 2025]
    • Digitalización de historias clínicas (Flask + SQL Server + Angular), reduciendo tiempos en un 80%.
    • Desarrollo integral de 6 módulos médicos (EMO, atenciones, vigilancia ocupacional, signos vitales).
    • Implementación sobre Windows Server con IIS y transacciones ACID en SQL Server.
```

---

## 🎓 Educación & Certificaciones

- **Ingeniería de Sistemas Computacionales** — Universidad Privada del Norte (UPN) | *Mar 2022 – Dic 2026 (Último ciclo)*
- **Hacker Ético** — Cisco Networking Academy
- **CCNA: Switching, Routing, and Wireless Essentials (CCNA 2)** — Cisco Networking Academy
- **CCNA: Introduction to Networks (CCNA 1)** — Cisco Networking Academy
- **Cisco Cybersecurity Essentials** — Cisco Networking Academy

---

<div align="center">

**¿Hablamos de un proyecto o una oportunidad?**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gerardo-plasencia)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Escribir-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/51947013696)
[![Email](https://img.shields.io/badge/Email-Enviar_Correo-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gerardo@darknezz.dev)

</div>
