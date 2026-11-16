<h1 align="center">David Peralta</h1>

<p align="center">
  <b>Desarrollador Backend (Python) · Integración de IA</b><br>
  Bogotá, Colombia · Disponible para roles presenciales o híbridos
</p>

<p align="center">
  <a href="https://github.com/David-Peralta-Rd/MinimalistDots_Rs">Portafolio</a> ·
  <a href="https://linkedin.com/in/david-peralta-380652366">LinkedIn</a> ·
  <a href="mailto:crdavidperalta@gmail.com">Correo</a>
</p>

---

Diseño servicios backend desacoplados con **Python, Django y PostgreSQL**, los empaqueto con **Docker** y los opero sobre **Linux**, mi sistema principal desde marzo de 2025 (instalación directa, sin máquinas virtuales). Mi diferenciador es la IA aplicada: construyo agentes que resuelven trabajo real de ingeniería y ejecuto modelos de lenguaje de 30B en mi propio equipo.

Tecnólogo en Análisis y Desarrollo de Software (SENA, 2026).

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat&logo=ollama&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Proyectos

### [MinimalistDots_Rs](https://github.com/David-Peralta-Rd/MinimalistDots_Rs) — entorno Linux con IA local
Dotfiles para Hyprland sobre CachyOS/Arch, con una capa de desarrollo asistido por IA que corre en mi propia CPU (Ryzen 5 5600G, 32 GB de RAM). Migrado a Rust para máxima velocidad y un solo binario.

#### Características
- **Entorno de escritorio**: Hyprland + Slint (Rust) para menús, notificaciones, reloj y OSD. Waybar/Quickshell sustituidos por `md` (un único binario).
- **IA local**: `md ai` levanta modelos con llama.cpp (`llama-server`) y los expone con una API compatible con OpenAI + tool calling. Mide rendimiento real con `llama-bench` y conecta OpenCode al modelo local.
- **Plantillas**: `AGENTS.md`, `SPEC.md` y `tasks.md` que separan lo que escribo yo de lo que delego al agente, con revisión humana de cada cambio.
- **Instalador modular** en Python (uv) con pasos ordenados, menús fuzzy y 7 idiomas (es, en, fr, pt, de, it, zh). Catálogos TOML en `lang/`.
- **Servicios en Lua** para Hyprland (reloj, notificaciones, bienvenida, etc.) y windowrules con `hyprland.lib.rules`.
- **Herramientas incluidas**: grabador de pantalla (gpu-screen-recorder), capturas con grimblast, OCR/QR, portapapeles, pomodoro, gestión de procesos, cambio de idioma en vivo.

### [B2C_MercyVentas_DavidPeralta](https://github.com/David-Peralta-Rd/cr-B2C_MercyVentas) — inventario y ventas *(en desarrollo)*
Backend Django + Django Ninja + PostgreSQL 18 y frontend Streamlit desacoplados, orquestados con Docker Compose en entornos de producción y desarrollo.

- Builds **multi-stage con `uv`**, usuario no root y healthchecks por servicio.
- Modelo de datos documentado y 8 criterios de aceptación; recepción de compras con transacciones atómicas y bloqueo de filas.
- Estado actual: infraestructura y diseño listos; la lógica de negocio está en construcción.

## Experiencia destacada

**SoftwareOne · Pasante SENA, Analista de Datos / Junior Data Engineer (IA)** · Sep 2025 – Mar 2026

- Diseñé dos **Copilot Agents** que automatizaron la documentación técnica: completaba en una jornada documentos que el equipo estimaba en 16 a 24 horas.
- Automaticé el análisis de consultas SQL legadas de MicroStrategy: de entre 10 minutos y 2 horas (con riesgo de reproceso) a 5 minutos estables.
- Participé en la migración a Microsoft Fabric y en una migración de 10 TB en SharePoint con más del 60 % de reducción de almacenamiento.
- Gané el **AI Prompt Challenge** de SoftwareOne, región Bogotá (2025).

## Contacto

Si estás construyendo backend con IA y buscas a alguien que aprende rápido y documenta lo que hace, escríbeme a **crdavidperalta@gmail.com**.
