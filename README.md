# Hola, soy Kevin 👋

**Desarrollador Full Stack** · TypeScript, Next.js, NestJS, Go y Python
Construyo productos de punta a punta: desde la app web o móvil hasta el despliegue y el monitoreo en producción.

## Qué hago

- **Web y móvil:** aplicaciones con Next.js, React, React Native (Expo) y Kotlin.
- **Backend:** APIs con NestJS, Prisma, PostgreSQL, WebSockets (Socket.IO) y servicios en Go.
- **Pasarelas de pago:** implementación de pagos en línea con ePayco y MercadoPago.
- **Automatización e integraciones:** bots de Telegram, webhooks, scraping y herramientas para IA.
- **DevOps:** despliegues con Dokploy y Docker, alertas, seguridad y monitoreo de servidores Linux.
- **IA aplicada:** integración de Claude en productos y plugins para flujos de desarrollo.

## Experiencia

### Desarrollador de software · World Travel Assist · 4 años

Mi trabajo principal fue resolver problemas operativos internos con proyectos tecnológicos: identificar cómo se hacía un proceso, detectar dónde se perdía tiempo y construir una solución que agilizara y optimizara el flujo de trabajo.

Una tarea constante fue **migrar procesos que vivían en hojas de Excel a sistemas diseñados para cada área**. Se pasó de archivos lentos de abrir y con la información dispersa a sistemas organizados y rápidos, con mejores filtros, visualizaciones y fluidez, lo que redujo de forma notable el tiempo de trabajo en las áreas operativas.

Estos son algunos de los proyectos que desarrollé:

**Plataforma web para gestionar mensajes de WhatsApp con integración de Twilio** (Django, API de Twilio)

- **Problema:** la atención por WhatsApp estaba repartida en varias cuentas gestionadas de forma manual. Meta bloqueaba esos números con frecuencia por detectarlos como spam, y no había control sobre quién accedía a cada conversación.
- **Solución:** construí una aplicación web en Django que centraliza en un solo lugar todos los mensajes entrantes de los números de la empresa. Usé la API de Twilio para registrar los números en Meta y operarlos de forma oficial.
- **Resultado:** los números ganaron confianza ante Meta y dejaron de bloquearse con tanta frecuencia. Además, el acceso quedó gestionado por permisos y los equipos responden desde un único panel web.

**Sistema de inventario y seguimiento de activos tecnológicos**

- **Problema:** no existía un registro centralizado de los equipos ni del historial de lo que ocurría con cada uno, como mantenimientos y novedades.
- **Solución:** desarrollé un sistema con módulos para recursos físicos (computadores, celulares, impresoras, aires acondicionados, ventiladores y más) y no físicos (licencias y un calendario de tareas que se relaciona con los registros de cualquier módulo). Diseñé un módulo de comentarios reutilizable, implementado en todos los módulos, que deja la trazabilidad completa de cada equipo.
- **Integración:** expuse una API para que otros sistemas internos consulten los registros y creen comentarios, de modo que las aplicaciones de la empresa se comunican entre sí.
- **Resultado:** historial completo y consultable de cada recurso, y un punto de integración para el resto de los sistemas.

**Landing pages informativas para clientes, desarrolladas como PWA**

Sitios web con interfaces intuitivas y fáciles de navegar, construidos como aplicaciones web progresivas.

- **Beneficios de la PWA:**
  - Funcionan sin conexión gracias al caché offline.
  - Se instalan en el dispositivo como una app, sin pasar por una tienda.
  - Cargan rápido, incluso con una conexión lenta.
  - Admiten notificaciones y se adaptan a cualquier pantalla.
  - Un solo código sirve para móvil y escritorio, lo que reduce el costo de mantenimiento.

## Proyectos destacados

Incluye productos que construyo en [Wordev](https://github.com/wWordDevw), la empresa que fundé con amigos; algunos tienen código privado.

| Proyecto | Qué es | Tecnologías |
|---|---|---|
| [**Realm**](https://realm.lat/) | Espacio de escritura con IA para novelistas y guionistas: biblia de la historia, navegador de capítulos, editor Tiptap y asistente creativo en streaming | Next.js, NestJS, Tiptap, IA |
| [**Eventia**](https://eventia.events/) | Marketplace para encontrar, comparar y contratar profesionales de eventos en Colombia, con propuestas y panel para cada profesional | Next.js 15, NestJS 11, PostgreSQL, Redis |
| [**Nuestro Circo**](https://nuestrocirco.com) | SaaS multi-tenant que conecta a artistas de circo y circos o agencias en Latinoamérica: perfiles públicos, ofertas de trabajo, postulaciones, roster, shows y finanzas | Next.js 16, Prisma 7, PostgreSQL, Better Auth, Tailwind 4, MercadoPago |
| **ERP Vowtech (IntelligentERP)** | Plantilla base para ERPs web multiempresa con RBAC por perfiles, módulos activables (Comercial, Compras, Facturación, Cobranza, Tesorería, Inventario, Reportes) y generadores de código | PHP 8.3, Laravel 12, Livewire 4, Tailwind 4, MariaDB |
| **Emi Call** | Videollamadas médicas en 1080p con degradación automática de calidad, grabación, chat multimedia e historial | Go (Pion WebRTC), Angular 17, PostgreSQL |
| **Documa** | SaaS que convierte notas en crudo (escritas o dictadas) en documentos Word formales con IA y editor ONLYOFFICE embebido | NestJS, React, BullMQ, Claude, MinIO |
| **Terap-IA** | Gestión de clínicas de terapia: seguimiento de pacientes y objetivos, notas diarias generadas automáticamente | TypeScript, PostgreSQL, Docker |
| [**Insumos Pereira**](https://insumos.vowtech.lat) | PWA con mapa y GPS para inventariar insumos de ayuda en puntos de acopio, con API pública documentada con OpenAPI | Node, SQLite, PWA |
| [**Sembra**](https://github.com/AloreBB/sembra) | Editor visual de documentos educativos tipo Canva, con exportación a PDF y búsqueda difusa | Next.js 16, Prisma 7, Better Auth, fabric.js, Tailwind 4 |
| [**Muse plugin para Claude Code**](https://github.com/AloreBB/muse-plugin-cc) | Plugin para revisar código y delegar tareas desde Claude Code | JavaScript |
| [**Hornet**](https://github.com/AloreBB/hornet) | Monitor ligero de seguridad para servidores Linux con alertas push vía ntfy | Shell |
| [**Despliegues Telegram**](https://github.com/AloreBB/despliegues-telegram) | Servicio que recibe webhooks de Dokploy y los envía a Telegram con formato | Go, Docker |
| [**DoIt**](https://github.com/AloreBB/doit-app) | App móvil de recordatorios con notificaciones locales, modo offline y pruebas automatizadas | Expo, React Native, Jest |
| [**Roxy Power Bot**](https://github.com/AloreBB/roxy-power-bot) | Bot de Telegram para encender (Wake-on-LAN) y apagar un PC por SSH, sin dependencias | Python |
| [**Silkdash**](https://github.com/AloreBB/silkdash-pwnagotchi) | Plugin de dashboard con temática Hollow Knight para Pwnagotchi | Python |

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## Cómo trabajo

- Código tipado, simple y mantenible (DRY y KISS).
- Pruebas automatizadas en la lógica crítica.
- Entrego en producción: despliegue, notificaciones y monitoreo incluidos.
- Documento lo que construyo para que otros puedan continuarlo.

## Estoy buscando

Un rol **Full Stack / Frontend / Backend** donde pueda aportar desde el primer día y seguir creciendo en un equipo de producto.

## Contacto

- 📫 Escríbeme por [GitHub](https://github.com/AloreBB) o por [LinkedIn](https://www.linkedin.com/in/kevin-jovy)
- 📧 kev.castrillon.contacto@gmail.com
- 🏢 Para proyectos con [Wordev / Vowtech](https://github.com/wWordDevw): info-comercial@vowtech.co
