<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1392952814866665572/1392972933114232953/MOON_STUDIO_1.jpg?ex=68717aa3&is=68702923&hm=1cebb27d5f5e5569e8b42036bfbb3a93376547495ac112ab8cbef479b9885d38&" alt="Banner del servidor" style="border-radius: 12px;"/>
  <h1>🌆 Moon Studio</h1>
  <h4>Tu historia, tu identidad, tu ciudad.</h4>
  <p>Servidor de Roleplay en GTA V con visión moderna, comunidad selecta y experiencias memorables.</p>

  <img src="https://img.shields.io/badge/Whitelist-Activa-green?style=for-the-badge&logo=trustpilot" />
  <img src="https://img.shields.io/badge/RP-Inmersivo-blueviolet?style=for-the-badge&logo=themoviedatabase" />
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-FFB800?style=for-the-badge&logo=gear" />
</div>

---

## 🚀 Visión del Proyecto

> **Moon Studio** no es solo otro servidor de RP.  
> Es un espacio narrativo donde cada jugador puede desarrollarse, conectarse y evolucionar en un entorno urbano diseñado al detalle. Realismo, comunidad y libertad creativa se mezclan en una ciudad que nunca duerme.

---

## 🔍 Lo que nos hace diferentes

✨ **Enfoque serio e inmersivo**  
🎯 **Whitelist con filtro humano y entrevistas**  
🧠 **Desarrollo de personajes real y coherente**  
📈 **Economía viva y lógica**  
🛰️ **Ciudad ambientada en España + scripts premium**  
🤝 **Staff activo, cercano y transparente**

---

## 🔗 Enlaces de interés

- 💬 **Discord:** [Únete Aquí](https://discord.gg/jTrRAuGfwm)
- 🌐 **Sitio web oficial:** *(Próximamente)*
- 📺 **Tráiler oficial:** *(Próximamente)*
- 📚 **Guía de inicio RP:** [Ver guía](https://tuweb.com/guia)
- 📖 **Normativa del servidor:** [Consulta aquí](https://tuweb.com/normas)
- 🛠️ **Estado del servidor:** [Ver estado](https://tuweb.com/estado)

## 🗂️ Estructura del Proyecto

```bash
📁 /server              # Scripts, assets y configuraciones del RP
📁 /database            # Dump y estructuras SQL
📁 /web                 # PÁGINA WEB
  📁 public/
├── index.html               # Portada principal
├── formulario.html          # Formulario de whitelist
├── login.html               # Login de staff
├── admin.html               # Panel de administración
├── comunidad.html           # Página de comunidad (noticias/eventos/foro)
├── normativa.html           # Normativa del servidor
│
├── 📁 assets/
│   ├── 📁 css/
│   │   ├── style.css        # Estilos generales
│   │   ├── login.css        # Estilos del login
│   │   ├── admin.css        # Estilos del panel staff
│   │   ├── comunidad.css    # Estilos comunidad
│   │   ├── normativa.css    # Normativa super detallada
│   │
│   └── 📁 js/
│       ├── script.js        # Scripts generales
│       ├── formulario.js    # Lógica del formulario de whitelist
│       ├── login.js         # Login staff
│       ├── admin.js         # Aceptar/Rechazar desde el panel
│       ├── normativa.js     # Scroll animado o buscador de normativa

📁 db/
└── solicitudes.json         # Base de datos local de whitelist

📁 utils/
└── email.js (opcional)      # Sistema de recuperación por email

📄 .env                       # Variables de entorno (webhook, ID canales, token)
📄 index.js                   # Servidor Express + API + Bot Discord
📄 package.json               # Dependencias y scripts
📄 server.cfg           # Config principal
🚀 start.sh             # Script de arranque
📄 README.md          
