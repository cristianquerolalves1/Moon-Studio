<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1392952814866665572/1392972933114232953/MOON_STUDIO_1.jpg" alt="Moon Studio Banner" width="100%" style="border-radius: 12px;" />
</div>

<h1 align="center">🌆 Moon Studio RP</h1>
<h4 align="center"><em>Tu historia, tu identidad, tu ciudad.</em></h4>
<p align="center">Servidor de GTA V Roleplay con identidad única, narrativa profunda y una comunidad selecta. Donde cada decisión importa.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Whitelist-Activa-4caf50?style=for-the-badge&logo=trustpilot" />
  <img src="https://img.shields.io/badge/RP-Inmersivo-6a1b9a?style=for-the-badge&logo=themoviedatabase" />
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-ff9800?style=for-the-badge&logo=gear" />
</p>

---

## 🚀 Visión del proyecto

> **Moon Studio RP** no es solo un servidor más.  
> Es un espacio de rol donde convergen la narrativa, el realismo y la estética.  
> Un ecosistema serio, profesional y selectivo, diseñado para quienes buscan **rol con propósito**.

---

## 🎯 Características clave

- 🔐 **Sistema de whitelist profesional** con revisión manual y formulario inteligente
- 🧠 **Narrativa libre pero estructurada**, sin facciones forzadas
- 💰 **Economía coherente** y autosostenible
- 🏙️ **Ambientación moderna y scripts optimizados**
- 🧾 **Normativa extensa y clara**, tipo GitBook (más de 1000 líneas)
- 📦 **Panel de staff con gestión desde web y bot de Discord**
- 🤖 **Bot integrado** para logs y aceptación/rechazo desde web
- 📫 **Sistema de recuperación por email** (próximamente)
- 💬 **Comunidad seleccionada por afinidad, no por cantidad**

---

## 🌐 Enlaces de interés

| Categoría          | Enlace                                 |
|--------------------|----------------------------------------|
| 💬 Discord          | [Unirse al servidor](https://discord.gg/jTrRAuGfwm) |
| 📚 Normativa        | [Consultar normativa](https://moonstudio.com/normativa) |
| 📝 Whitelist        | [Solicitar acceso](https://moonstudio.com/formulario.html) |
| 📖 Guía RP          | [Guía de rol](https://moonstudio.com/guia) |
| 🛠️ Estado del Servidor | [Ver estado](https://moonstudio.com/estado) |

---

## 🧩 Estructura del proyecto

```bash
📁 /server              # Scripts, assets y configuraciones del RP
📁 /database            # Estructura SQL y backups
📁 /web                 # Frontend del panel y sitio oficial
├── 📁 public/
│   ├── index.html            # Portada
│   ├── formulario.html       # Whitelist
│   ├── login.html            # Login de staff
│   ├── admin.html            # Dashboard
│   ├── comunidad.html        # Comunidad (noticias/eventos/foro)
│   ├── normativa.html        # Normativa visual profesional
│
│   └── 📁 assets/
│       ├── 📁 css/
│       │   ├── style.css
│       │   ├── login.css
│       │   ├── admin.css
│       │   ├── comunidad.css
│       │   └── normativa.css
│       ├── 📁 js/
│       │   ├── script.js
│       │   ├── formulario.js
│       │   ├── login.js
│       │   ├── admin.js
│       │   └── normativa.js

📁 /db/
└── solicitudes.json         # Base de datos local

📁 /utils/
└── email.js                 # Sistema de recuperación por correo (en progreso)

📄 .env                       # Variables del entorno
📄 index.js                   # Servidor Express + Bot Discord
📄 package.json               # Dependencias y scripts
📄 server.cfg                 # Config del servidor RP
🚀 start.sh                   # Script de arranque
