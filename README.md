<div align="center">

```
███╗   ███╗██╗   ██╗███████╗██╗ ██████╗██████╗ ██╗   ██╗
████╗ ████║██║   ██║██╔════╝██║██╔════╝██╔══██╗╚██╗ ██╔╝
██╔████╔██║██║   ██║███████╗██║██║     ██████╔╝ ╚████╔╝ 
██║╚██╔╝██║██║   ██║╚════██║██║██║     ██╔═══╝   ╚██╔╝  
██║ ╚═╝ ██║╚██████╔╝███████║██║╚██████╗██║        ██║   
╚═╝     ╚═╝ ╚═════╝ ╚══════╝╚═╝ ╚═════╝╚═╝        ╚═╝  
```

# 🎵 Musicpy Downloader

**El descargador de música más completo. Sin límites. Sin compromisos.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Platforms](https://img.shields.io/badge/Plataformas-5-success?style=for-the-badge)](#plataformas-soportadas)
[![Formats](https://img.shields.io/badge/Formatos-7-blueviolet?style=for-the-badge)](#formatos-de-descarga)
[![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)](LICENSE)

</div>

---
[English](README.md) | [Español](README.es.md) | [CHINO](README.zn.md) | [RUSO](README.ru.md)
## ✨ ¿Qué es Musicpy Downloader?

**Musicpy Downloader** es una herramienta con interfaz construida en **Python** que te permite descargar música desde las plataformas más populares del mundo — con soporte de letras incrustadas, múltiples formatos y total personalización visual.

> 🎯 Una sola herramienta. Cinco plataformas. Cero límites de descarga. Sin registro. 

---

## 🚀 Características principales

| Característica | Descripción |
|---|---|
| 🎨 **Colores personalizables** | Cambia los colores de la interfaz a tu gusto |
| 📁 **7 formatos de descarga** | MP3 (320k Y 128k), M4A(AAC), FLAC, WAV, OGG, OPUS, AAC |
| 🌐 **7 fuentes de descarga** | Múltiples backends para máxima disponibilidad |
| 🎤 **Letras LRC incrustadas** | Sincronizadas y embebidas directamente en el archivo |
| 🔗 **Descarga solo con link** | Pega el link y listo, sin configuraciones extra |
| 📋 **Soporte de playlists** | Descarga listas completas de una sola vez |
| 🎵 **5 plataformas** | YouTube, Spotify, SoundCloud, Deezer y Tidal |
| 📁 **Cambiar carpeta de descarga |

---

## 🎧 Plataformas soportadas

<div align="center">

| | Plataforma | Canciones | Playlists | Álbumes |
|:---:|:---:|:---:|:---:|:---:|
| 🔴 | **YT y YTMUSIC** | ✅ | ✅ | ✅ |
| 🟢 | **Spotify** | ✅ | ✅ | ✅ |
| 🟠 | **SoundCloud** | ✅ | ✅ | ✅ |
| 🩵 | **Deezer** | ✅ | ✅ | ✅ |
| 🔵 | **Tidal** | ✅ | ✅ | ✅ |

</div>

---

## 📦 Formatos de descarga

```
┌─────────────────────────────────────────────────┐
│  🎵 MP3   — Compatible con todo                 │
│  🎵 FLAC  — Calidad sin pérdida                 │
│  🎵 WAV   — Audio sin compresión                │
│  🎵 M4A   — AAC optimizado para Apple           │
│  🎵 OGG   — Open source y liviano               │
│  🎵 OPUS  — El mejor para streaming             │
│  🎵 AAC   — Alta calidad, menor tamaño          │
└─────────────────────────────────────────────────┘
```

---

## 🎤 Letras LRC

Musicpy Downloader soporta **tres modos de letra**:

- ✅ **Incrustada en el archivo** — La letra viaja junto con la canción, sincronizada al milisegundo
- ✅ **Solo el link** — Descarga sin letra si no la necesitas
- ✅ **Archivo `.lrc` separado** — Guarda la letra como archivo externo

```
[00:12.00] 🎵 La letra aparece sincronizada...
[00:15.30] 🎵 mientras escuchas la canción.
[00:18.60] 🎵 Sin apps externas. Sin configuración.
```

---

## ⚙️ Instalación
1- Descarga en release el .zip
2- Ejecuta install.py
3- Despues de pasar los 6 requirimientos 
4- Ejecuta run.bat 

IMPORTANTE se incluira ffmpeg.exe y ffprobe.exe IMPORTANTES para descargar por caso de error en el install.py EL CMD que se abre no debe borrarse se quitara automaticamente una vez se cierre el programa
---

## 🎨 Personalización de colores

Musicpy Downloader te permite modificar los **colores de la interfaz** directamente desde el menú de configuración. Elige entre paletas predefinidas o define tus propios colores ANSI para una experiencia completamente tuya.

```
  ┌────────────────────────────┐
  │  🎨 Tema: Morado Noche     │
  │  🎨 Tema: Verde Matrix     │
  │  🎨 Tema: Rojo Fuego       │
  │  🎨 Tema: automatico       │
  │  🎨 Personalizado...       │
  └────────────────────────────┘
```

---

## 🖥️ Uso básico

```
este descargador tiene interfaz por lo que no nesesitas saber mucho de python solo copiar el LINK y cambiar fuente, formato, letra y presionar DESCARGAR facil y rapido 
```

---

## 📂 Estructura del proyecto

```
musicpy-downloader/
│
├── 📄 main.py              # Punto de entrada
├── 📄 downloader.py        # Lógica de descarga
├── 📄 lyrics.py            # Módulo de letras LRC
├── 📄 platforms/           # Conectores por plataforma
│   ├── youtube.py
│   ├── spotify.py
│   ├── soundcloud.py
│   ├── deezer.py
│   └── tidal.py
├── 📄 themes.py            # Sistema de colores
├── 📄 requirements.txt     # Dependencias
└── 📄 README.md
```

---

## 📋 Requisitos

- Python **3.8 o superior**
- `ffmpeg` instalado en el sistema
- Conexión a internet

---

## 🤝 Contribuir

¿Tienes ideas? ¿Encontraste un bug? Las contribuciones son bienvenidas.

1. Haz un **Fork** del proyecto
2. abre un issue para errores o ideas en un futuro se te agradecera y mencionara en el programa 

---

## 📄 Licencia

Distribuido bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.

---

<div align="center">

Hecho con 🎶 y mucho Python 

**[⬆ Volver arriba](#-musicpy-downloader)**

</div>
