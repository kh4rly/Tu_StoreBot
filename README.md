[deepseek_markdown_20260927_e0f08a.md](https://github.com/user-attachments/files/32706581/deepseek_markdown_20260927_e0f08a.md)
<div align="center">

# 🤖 Directorio de Bots Telegram

**El directorio definitivo para promocionar y descubrir bots de Telegram**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://core.telegram.org/bots/api)
[![SQLite](https://img.shields.io/badge/SQLite-3-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[🚀 Demo en vivo](#) · [📸 Capturas](#-capturas) · [⚡ Instalación rápida](#-instalación-rápida) · [💬 Soporte](#-soporte)

</div>

---

## 🌟 ¿Qué es esto?

**Directorio de Bots** es un bot de Telegram **todo en uno** que convierte tu canal o grupo en un **directorio profesional de bots**, con sistema de publicación, gestión de usuarios, panel de administración y monedización vía pagos manuales.

Si tienes una comunidad en Telegram y quieres:

- 💰 **Monetizar** con publicaciones destacadas
- 📈 **Organizar** bots por categorías
- 👥 **Fidelizar** a creadores de bots
- 🎯 **Ofrecer soporte** profesional

...este bot es para ti.

---

## ✨ Características estrella

<table>
<tr>
<td width="50%">

### 🎨 Para tus usuarios
- 📂 **Explorar** un directorio visual con fotos, títulos y descripciones
- ➕ **Publicar** su bot en menos de 30 segundos
- ✏️ **Editar** sus publicaciones cuando quieran
- 🖼️ **Añadir foto** o banner a cada bot
- ⭐ **Subir al Top** con un sistema de pago integrado
- 💬 **Contactar** contigo por chat de soporte interno

</td>
<td width="50%">

### 👑 Para ti (admin)
- 📊 **Panel completo** desde el propio bot
- 👥 **Gestión de usuarios** con búsqueda avanzada
- 🚫 **Baneo/desbaneo** con un clic
- 📌 **Fijar bots** en las categorías
- 💳 **Editor de precios** sin tocar código
- 🖼️ **Historial multimedia** de cada chat de soporte

</td>
</tr>
</table>

---

## 🎬 Así funciona

### 👤 Vista del usuario

```
/start
   ↓
📂 Ver Directorio  ·  ➕ Añadir mi Bot
⚙️ Mis Publicaciones  ·  💬 Chat con Soporte
   ↓
Explora por categorías → Card del bot con foto
   ↓
🚀 Abrir Bot  ·  ⚙️ Gestionar
```

### 📝 Publicar tu bot en 5 pasos

```
1/5  📌 Envía el @username del bot
2/5  ✍️ Título atractivo
3/5  📝 Descripción completa
4/5  🖼️ Foto de portada (opcional)
5/5  📂 Elige categoría
        ↓
     ✅ ¡Bot publicado!
```

### 👑 Vista del administrador

```
👑 Panel de Administración
   ├─ 💬 Chats de Soporte Activos
   ├─ 👥 Ver Usuarios / Banear
   └─ 💳 Configurar Texto de Pago
```

---

## 📸 Capturas

> 💡 Añade aquí tus propias capturas de pantalla del bot en acción

| Menú principal | Directorio | Card de bot |
|:-:|:-:|:-:|
| ![Menu](#) | ![Directorio](#) | ![Card](#) |

| Panel admin | Chat soporte | Gestión usuarios |
|:-:|:-:|:-:|
| ![Panel](#) | ![Chat](#) | ![Usuarios](#) |

---

## 💎 ¿Por qué elegir este bot?

|  | Característica | Otros bots | **Este bot** |
|:-:|:--|:-:|:-:|
| 🎨 | Interfaz moderna con fotos | ❌ | ✅ |
| 💰 | Monetización integrada | ❌ | ✅ |
| 📂 | Categorías personalizables | ⚠️ | ✅ |
| 💬 | Chat de soporte con historial | ❌ | ✅ |
| 🖼️ | Multimedia en soporte | ❌ | ✅ |
| 📅 | Historial por fecha | ❌ | ✅ |
| 👥 | Búsqueda de usuarios avanzada | ❌ | ✅ |
| 🚫 | Sistema de baneo | ⚠️ | ✅ |
| 📌 | Destacar/fijar publicaciones | ❌ | ✅ |
| 🛡️ | Rate limiting y seguridad | ❌ | ✅ |
| 📦 | Zero-config database | ❌ | ✅ |
| 🔓 | Open source | ⚠️ | ✅ |

---

## 🚀 Instalación rápida

### En 3 comandos

```bash
# 1. Clona el repo
git clone https://github.com/tu-usuario/directorio-bots.git && cd directorio-bots

# 2. Instala la dependencia
pip install pyTelegramBotAPI

# 3. Configura y ejecuta
export BOT_TOKEN="tu_token_aqui" && export ADMIN_ID="tu_id_aqui" && python bot.py
```

**¿Listo en menos de 1 minuto!** 🎉

### Requisitos

- ✅ **Python 3.8+**
- ✅ Un **token de bot** (consíguelo gratis en [@BotFather](https://t.me/BotFather))
- ✅ Tu **ID de Telegram** (consíguelo gratis en [@userinfobot](https://t.me/userinfobot))

---

## ⚙️ Personalización

Edita estas constantes al principio del archivo:

```python
# Tus datos
ADMIN_ID = 156826027              # Tu ID de Telegram
USERNAME_BOT_REF = "Tu_Storebot"  # Para el botón "Reenviar"

# Comportamiento
MAX_TITULO_LEN = 80          # Longitud máx. del título
MAX_DESCRIPCION_LEN = 500    # Longitud máx. de la descripción
RATE_LIMIT_PER_MIN = 25      # Acciones por minuto por usuario

# Categorías (¡personalízalas a tu gusto!)
CATEGORIAS = [
    "📚 Libros y Lectura",
    "🛍️ Tiendas y Ventas",
    "🤖 Cripto y AI (Bots)",
    # Añade las tuyas...
]
```

---

## 🎯 Casos de uso

<details>
<summary><b>🎮 Comunidad de gaming</b></summary>

Crea un directorio de bots para clanes, servidores de MTA/FiveM, juegos de Telegram...
</details>

<details>
<summary><b>📚 Venta de cursos y ebooks</b></summary>

Publica tus cursos, libros y guías digitales y cobra por destacarlos.
</details>

<details>
<summary><b>🤖 Directorio de bots cripto</b></summary>

Categoría especializada en bots de trading, señales, DeFi...
</details>

<details>
<summary><b>🎬 Películas y series</b></summary>

Organiza canales y bots de contenido audiovisual.
</details>

<details>
<summary><b>💼 Agencia de desarrollo</b></summary>

Muestra el portafolio de bots que has construido para clientes.
</details>

---

## 🛠️ Stack técnico

<div align="center">

| Componente | Tecnología |
|:--|:--|
| **Lenguaje** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| **Framework** | ![pyTelegramBotAPI](https://img.shields.io/badge/-pyTelegramBotAPI-26A5E4?logo=telegram&logoColor=white) |
| **Base de datos** | ![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white) |
| **Estilos** | HTML nativo de Telegram |
| **Arquitectura** | Monolito con estados en memoria |

</div>

---

## 🛡️ Seguridad de serie

- 🔒 **Rate limiting** integrado (25 acciones/min por usuario)
- ✅ **Escape HTML** de todo input del usuario
- 🛡️ **Validación regex** de usernames
- 🔐 **SQL parametrizado** (sin inyecciones)
- 🧵 **Thread-safe** con locks en memoria
- ⏱️ **Timeout SQLite** para evitar bloqueos
- 👮 **Verificación de permisos** en cada acción

---

## 📊 Estructura del proyecto

```
directorio-bots/
├── 🤖 bot.py              # Todo el código (single file)
├── 🗄️ bots_directory.db   # Base de datos (auto-generada)
├── 📄 README.md           # Este archivo
├── 📄 LICENSE             # MIT
└── 📄 .gitignore          # Ignora .db y .env
```

**Filosofía**: zero-config, single-file, fácil de entender, fácil de modificar.

---

## 🗺️ Roadmap

```
✅ v1.0  Directorio funcional con fotos y categorías
✅ v1.1  Chat de soporte bidireccional
✅ v1.2  Historial multimedia + filtro por fecha
✅ v1.3  Panel admin con paginación y búsqueda
✅ v1.4  Rate limiting y seguridad reforzada
🔄 v2.0  Soporte multi-admin
🔄 v2.1  Estados persistentes en SQLite
🔄 v2.2  Estadísticas por categoría
📋 v2.3  Búsqueda de bots por texto
📋 v2.4  Notificaciones push
📋 v2.5  API REST para integraciones
```

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si tienes una idea:

1. 🍴 Haz un **fork** del proyecto
2. 🌿 Crea tu rama: `git checkout -b feature/nueva-funcion`
3. 💾 Commit: `git commit -m "Añade nueva función"`
4. 📤 Push: `git push origin feature/nueva-funcion`
5. 🎉 Abre un **Pull Request**

También puedes contribuir:
- ⭐ Dando una **estrella** al repo
- 🐛 Reportando **bugs** en Issues
- 💡 Sugiriendo **nuevas ideas**
- 📣 **Compartiendo** el proyecto en tus redes

---

## 💖 Apoya el proyecto

Si este bot te ha sido útil y quieres que siga mejorando:

- ⭐ **Dale una estrella** en GitHub
- 🐦 **Compártelo** en Twitter/X o tu comunidad de Telegram
- ☕ **Invítame a un café** (añade tu link de PayPal/BuyMeACoffee)
- 🐛 **Reporta bugs** o sugiere mejoras

---

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**. Puedes:

- ✅ Usarlo comercialmente
- ✅ Modificarlo
- ✅ Distribuirlo
- ✅ Usarlo en proyectos privados

Solo tienes que incluir la licencia original y el aviso de copyright.

---

## 📞 Soporte

<div align="center">

| Canal | Contacto |
|:--|:--|
| 🐛 **Issues** | [Abrir un issue](https://github.com/tu-usuario/directorio-bots/issues) |
| 💬 **Telegram** | [@Tu_Usuario](https://t.me/Tu_Usuario) |
| 📧 **Email** | tu-correo@ejemplo.com |

</div>

---

<div align="center">

### 🌟 Si te gusta el proyecto, dale una estrella 🌟

**Hecho con ❤️ para la comunidad de bots de Telegram**

[⬆️ Volver arriba](#-directorio-de-bots-telegram)

</div>
