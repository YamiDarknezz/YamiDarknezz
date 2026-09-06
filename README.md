<div align="center">

<img src="darknezz-logo.png" alt="Darknezz" width="60" height="60" />

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

### 🛡️ [darknezz-infra](https://github.com/YamiDarknezz/darknezz-infra) — Baseline Server Hardening & GitOps
> Plataforma de aprovisionamiento e infraestructura como código (IaC) para servidores Linux en producción:
> - **Ingress Seguro:** Reverse proxy con **Traefik v3** y emisión automatizada de certificados wildcard SSL (`*.darknezz.dev`) vía Cloudflare DNS API.
> - **Orquestación PaaS:** Despliegue y administración de contenedores mediante **Dokploy** y Docker Compose.
> - **Hardening Host:** UFW estricto (solo 22 y 443), llaves SSH Ed25519 (bloqueo total de root/passwords), Fail2ban activo y observabilidad con **Prometheus & Grafana**.
>
> ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Traefik](https://img.shields.io/badge/Traefik_v3-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white) ![Dokploy](https://img.shields.io/badge/Dokploy-181717?style=flat-square&logo=docker&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_DNS-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
>
> 🔗 **[Ver Repositorio en GitHub](https://github.com/YamiDarknezz/darknezz-infra)**

---

### 📦 [inventory-api](https://github.com/YamiDarknezz/inventory-api) — API REST Empresarial en Java 21 & Spring Boot 3
> Servicio backend de gestión de inventarios y control de stock bajo estándares de ingeniería de software:
> - **Seguridad & RBAC:** Autenticación mediante **JWT** y control de accesos granular basado en roles.
> - **Arquitectura & Calidad:** Validación estricta de DTOs, persistencia relacional con Spring Data JPA sobre **PostgreSQL**, y arquitectura limpia por capas.
> - **Documentación Viva:** Especificación OpenAPI 3.0 con interfaz **Swagger UI** interactiva desplegada en producción.
>
> ![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger_OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
>
> 🔗 **[Ver Repositorio en GitHub](https://github.com/YamiDarknezz/inventory-api)** · 🌐 **[Swagger UI en Vivo](https://api-inventory.darknezz.dev/swagger-ui/index.html)**

---

### ⚡ Pauser Maestros (Extractor Maestro) — Ingesta & Replicación Multi-Proveedor
> Middleware de ingesta de alto rendimiento para desacoplar proveedores externos críticos en Pauser Distribuciones SAC:
> - **Desacoplamiento Absoluto:** Extracción incremental desde ERP corporativo (Progress OpenEdge/ODBC), combustible Primax y telemetría de flotas ProGPS.
> - **Alto Rendimiento:** Control de concurrencia con `asyncio.Semaphore` y procesamiento vectorial en memoria con DataFrames de **Polars**.
> - **Latencias <15ms:** Replicación limpia en **PostgreSQL** mediante upserts atómicos masivos, reduciendo tiempos de consulta de >8s a milisegundos para microservicios internos.
>
> ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
>
> 📖 **[Ver Caso de Estudio en darknezz.dev](https://darknezz.dev)** *(Código propietario Pauser)*

---

### 🌐 [Darknezz.dev](https://darknezz.dev) — Portafolio Web Reactivo & Hub de Arquitectura
> Single Page Application construida con los últimos estándares del ecosistema frontend:
> - **Reactividad Moderna:** 100% Standalone Components en **Angular 21** con **Signals & LinkedSignal** para estado puro.
> - **UI & Rendimiento:** Estilizado moderno con **Tailwind CSS v4**, micro-animaciones con GSAP, soporte PWA y compilación con 0 errores.
> - **Casos de Estudio Técnicos:** Documentación interactiva de AuthOps, MechGuard, Extractor Maestro y Darknezz-Infra.
>
> ![Angular 21](https://img.shields.io/badge/Angular_21-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
>
> 🌐 **[Explorar darknezz.dev](https://darknezz.dev)** · 📄 **[Descargar CV Ejecutivo](https://darknezz.dev/CV_Gerardo_Plasencia.pdf)**

---

## 💻 Stack Tecnológico

### Backend & APIs
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### Frontend Engineering
![Angular](https://img.shields.io/badge/Angular_21-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)

### Bases de Datos & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO_S3-C72C48?style=for-the-badge&logo=minio&logoColor=white)

### Infraestructura & DevOps (Sysadmin)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Dokploy](https://img.shields.io/badge/Dokploy_PaaS-181717?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik_v3-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_DNS-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux Hardening](https://img.shields.io/badge/Linux_Hardening-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Business Intelligence & Automatización
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![n8n](https://img.shields.io/badge/n8n_Workflows-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![WhatsApp API](https://img.shields.io/badge/WhatsApp_Evolution_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

### Redes & Ciberseguridad
![Cisco CCNA](https://img.shields.io/badge/Cisco_CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity_Essentials-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Hacker Etico](https://img.shields.io/badge/Hacker_Etico_Cisco-000000?style=for-the-badge&logo=cisco&logoColor=white)

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
