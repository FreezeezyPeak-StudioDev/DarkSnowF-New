<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=58A6FF&center=true&vCenter=true&width=500&lines=Games+Developer;Open+Source+Projects;Creative+Coding;Simple+Apps+Creator;Learning+New+Things" />

<br>

<!-- LOGO CENTRADO -->
<div align="center">

<img src="https://raw.githubusercontent.com/FreezeezyPeak/Info-Freezeezy-PeaK/main/logo_freezeezy.png" width="220">

# FreezeezyPeak

</div>

---

<div align="center">

![DarkSnowF](https://img.shields.io/badge/DarkSnowF-v3.2-blue?style=for-the-badge&logo=firefox)

## DarkSnowF

**Tu Página de Inicio Personalizada para Firefox**

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-GPL%20v3-blue)
![Firefox](https://img.shields.io/badge/Firefox-Compatible-orange)

</div>

---

**[🇪🇸 Español](#español)** | **[🇬🇧 English](#english)**

---

## Español

### DarkSnowF — Tu página de inicio personalizada

Experiencia oscura, personalizable y completa. Buscador multi-motor, accesos rápidos arrastrables, reloj en vivo, fondos dinámicos, 5 temas azules, nieve animada, frases secretas y perfiles independientes.

100% local • Sin cuentas • Código abierto (GPL-3.0)

### Características

- **Buscador Multi-Motor** — Google, Bing, DuckDuckGo, ChatGPT, Wikipedia, Perplexity
- **Accesos Rápidos** — Arrastra, organiza y categoriza con iconos automáticos
- **Perfiles** — Personal, Público, Trabajo... cada uno con enlaces independientes
- **Reloj en Vivo** — Sincronización internet/PC, formato 12/24h, zonas horarias
- **Fondos Dinámicos** — Presets, URLs o archivos locales con rotación automática
- **5 Temas Azules** — Oscuro, claro y paletas exclusivas
- **Nieve Animada** — Efectos navideños y easter eggs
- **100% Local** — Sin nube, sin rastreo, todo en tu navegador

### Estructura del Proyecto


DarkSnowF/
├── Index.html ← home (buscador, accesos, categorías, logo)
├── popup.html ← mini menú del icono (redes, perfiles, ventana)
├── manifest.json ← MV3 v3.2 (newtab, permisos, iconos)
├── read.txt ← documentación
├── .vscode/settings.json ← config del editor
│
├── pages/
│ ├── config.html ← ajustes (tema, fondo, reloj, zoom, perfiles…)
│ ├── credit.html ← créditos (logo + redes)
│ └── License.html ← licencia GPL-3.0
│
├── assets/
│ ├── Fx/Click2.mp3 ← sonido de clic
│ ├── Texturas/Logos/ ← DarkSnowF.ico/.png, logo_freezeezy.png
│ └── Texturas/UI/ ← 16 PNG + 21 SVG (iconos)
│ └── icons/ ← gatos (5) + iconGd/Mc/Nav/Normal/Ny/Win
│
├── src/css/
│ ├── cursor.css
│ ├── dialogs.css
│ ├── index-styles.css
│ ├── main.css
│ ├── menu.css
│ ├── modals.css
│ └── themes.css
│
├── src/js/
│ ├── background.js
│ ├── clock.js
│ ├── config-loader.js
│ ├── config-page.js
│ ├── festive.js
│ ├── i18n.js
│ ├── i18n-pages.js
│ ├── index-app.js
│ ├── menu.js
│ ├── modals.js
│ ├── popup.js
│ ├── rotate.js
│ └── snow.js
│
├── utils/
│ ├── animations.js
│ ├── dialogs.js
│ └── storage.js
│
├── themes/
│ ├── abyss.css
│ ├── frost.css
│ ├── neon.css
│ ├── ocean.css
│ └── dark.css (por defecto)
│
└── versions/
├── V1.0beta.xpi
├── V2.0beta.xpi
└── V3.2beta.xpi


### Cómo Usar

**Home Principal:**
1. Click en el icono de DarkSnowF
2. Personaliza buscador, accesos rápidos y perfiles
3. Elige tema, fondo y efectos

**Ajustes:**
- Tema (Abyss, Frost, Neon, Ocean, Dark)
- Fondo (predefinido, URL o archivo local)
- Reloj (12/24h, zona horaria, sincronización)
- Zoom (50%-150%)
- Perfiles independientes

**Perfiles:**
- Crea múltiples perfiles
- Cada uno con sus propios enlaces
- Cambia rápidamente

### Instalación

1. Descarga desde Firefox Add-ons: [DarkSnowF](link)
2. Click "Agregar a Firefox"
3. Tu nueva pestaña está lista

### Licencia

GNU General Public License v3.0 — Ver archivo LICENSE

Desarrollado por **Freezeezy Peak**
GitHub: [github.com/FreezeezyPeak-StudioDev/DarkSnowF](link)

---

## English

### DarkSnowF — Personalized Home Page

Dark, customizable, complete experience. Multi-engine search, draggable shortcuts, live clock, dynamic backgrounds, 5 blue themes, animated snow, secret phrases and independent profiles.

100% local • No accounts • Open source (GPL-3.0)

### Features

- **Multi-Engine Search** — Google, Bing, DuckDuckGo, ChatGPT, Wikipedia, Perplexity
- **Draggable Shortcuts** — Drag, organize and categorize with automatic icons
- **Profiles** — Personal, Public, Work... each with independent links
- **Live Clock** — Internet/PC sync, 12/24h format, timezone support
- **Dynamic Backgrounds** — Presets, URLs, or local files with auto-rotation
- **5 Blue Themes** — Dark, light and exclusive palettes
- **Animated Snow** — Holiday effects and easter eggs
- **100% Local** — No cloud, no tracking, everything in your browser

### Project Structure

DarkSnowF/
├── Index.html ← home (search, shortcuts, categories, logo)
├── popup.html ← mini menu of icon (networks, profiles, window)
├── manifest.json ← MV3 v3.2 (newtab, permissions, icons)
├── read.txt ← documentation
├── .vscode/settings.json ← editor config
│
├── pages/
│ ├── config.html ← settings (theme, background, clock, zoom, profiles…)
│ ├── credit.html ← credits (logo + networks)
│ └── License.html ← GPL-3.0 license
│
├── assets/
│ ├── Fx/Click2.mp3 ← click sound
│ ├── Texturas/Logos/ ← DarkSnowF.ico/.png, logo_freezeezy.png
│ └── Texturas/UI/ ← 16 PNG + 21 SVG (interface icons)
│ └── icons/ ← cats (5) + iconGd/Mc/Nav/Normal/Ny/Win
│
├── src/css/
│ ├── cursor.css
│ ├── dialogs.css
│ ├── index-styles.css
│ ├── main.css
│ ├── menu.css
│ ├── modals.css
│ └── themes.css
│
├── src/js/
│ ├── background.js
│ ├── clock.js
│ ├── config-loader.js
│ ├── config-page.js
│ ├── festive.js
│ ├── i18n.js
│ ├── i18n-pages.js
│ ├── index-app.js
│ ├── menu.js
│ ├── modals.js
│ ├── popup.js
│ ├── rotate.js
│ └── snow.js
│
├── utils/
│ ├── animations.js
│ ├── dialogs.js
│ └── storage.js
│
├── themes/
│ ├── abyss.css
│ ├── frost.css
│ ├── neon.css
│ ├── ocean.css
│ └── dark.css (default)
│
└── versions/
├── V1.0beta.xpi
├── V2.0beta.xpi
└── V3.2beta.xpi


### How to Use

**Main Home:**
1. Click DarkSnowF icon
2. Customize search, shortcuts and profiles
3. Choose theme, background and effects

**Settings:**
- Theme (Abyss, Frost, Neon, Ocean, Dark)
- Background (preset, URL or local file)
- Clock (12/24h, timezone, sync)
- Zoom (50%-150%)
- Independent profiles

**Profiles:**
- Create multiple profiles
- Each with its own links
- Switch quickly

### Installation

1. Download from Firefox Add-ons: [DarkSnowF](link)
2. Click "Add to Firefox"
3. Your new tab is ready

### License

GNU General Public License v3.0 — See LICENSE file

Developed by **Freezeezy Peak**
GitHub: [github.com/FreezeezyPeak-StudioDev/DarkSnowF](link)

---

<p align="center">
<strong>Made by Freezeezy Peak</strong><br>
<a href="https://www.youtube.com/@FreezeezyPeak">YouTube</a> |
<a href="https://addons.mozilla.org/es-ES/firefox/">Firefox Profile</a> |
<a href="https://github.com/FreezeezyPeak-StudioDev">GitHub</a>
</p>
