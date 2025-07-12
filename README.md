# 🌆 Moon Studio RP
<div align="center">

<img src="https://cdn.discordapp.com/attachments/1392952814866665572/1392972933114232953/MOON_STUDIO_1.jpg" alt="Moon Studio Banner" width="100%" style="border-radius: 12px;" />

</div>

<h1 align="center">🌆 Moon Studio RP</h1>
<h4 align="center">Tu historia. Tu identidad. Tu ciudad.</h4>

<p align="center">
Un servidor de <strong>GTA V Roleplay</strong> con enfoque realista, sistema profesional de whitelist, desarrollo de personajes libre, y una comunidad moderada para garantizar una experiencia de rol inmersiva y cuidada al detalle.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Whitelist-Activa-4caf50?style=for-the-badge&logo=trustpilot" />
  <img src="https://img.shields.io/badge/RP-Inmersivo-6a1b9a?style=for-the-badge&logo=themoviedatabase" />
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-ff9800?style=for-the-badge&logo=gear" />
</p>

> **Tu historia. Tu identidad. Tu ciudad.**  
> Un servidor serio de GTA V Roleplay con un enfoque moderno, inmersivo y totalmente profesional. Creamos experiencias, no solo partidas.

---

## 🧭 Visión General

Moon Studio RP nace como una propuesta alternativa al rol genérico y poco moderado. Nuestro objetivo es ofrecer una ciudad **viva**, **realista** y **comunitaria**, donde cada jugador tenga un espacio para desarrollarse y crear historias significativas.

- Rol serio y coherente
- Comunidad filtrada con whitelist
- Soporte humano, cercano y eficaz
- Estética web profesional, diseño premium
- Automatización sin perder el toque manual

---

## 🚀 Características Principales

- ✅ **Sistema de whitelist avanzado** con panel web
- 🧠 **Preguntas personalizadas** sobre normativa y rol
- 🔐 **Formulario con validaciones** y verificación antispam
- 🤖 **Bot de Discord** que integra el backend con canales de revisión
- 🛠️ **Dashboard para Staff** con botón de Aceptar/Rechazar
- ✉️ **Notificaciones automáticas** vía Discord
- 📦 **Base de datos JSON local** (sin necesidad de SQL)
- 💻 **Frontend profesional** con diseño oscuro tipo dashboard moderno

---

## 📁 Estructura del Proyecto

```bash
MoonStudio/
│
├── public/                     # Frontend de la web
│   ├── index.html             # Página principal
│   ├── formulario.html        # Formulario de whitelist
│   ├── login.html             # Login staff
│   ├── admin.html             # Panel de administración
│   ├── comunidad.html         # Comunidad: eventos, noticias, foro
│   ├── normativa.html         # Normativa oficial
│   ├── recuperar.html         # Recuperar contraseña (próximamente)
│   │
│   └── assets/
│       ├── css/
│       │   ├── style.css
│       │   ├── login.css
│       │   ├── admin.css
│       │   ├── comunidad.css
│       │   ├── normativa.css
│       │   └── recuperar.css
│       └── js/
│           ├── script.js
│           ├── formulario.js
│           ├── login.js
│           ├── admin.js
│           ├── normativa.js
│           └── recuperar.js
│
├── db/
│   └── solicitudes.json       # Base de datos local de whitelists
│
├── utils/
│   └── email.js               # Envío de correos (recuperación)
│
├── .env                       # Variables privadas
├── index.js                   # Servidor Express + API + Discord Bot
├── package.json               # Dependencias y scripts
└── README.md                  # Este archivo
