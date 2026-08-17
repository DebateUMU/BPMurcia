# 🏛️ BP Murcia — Plataforma Oficial del Torneo

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-success?style=flat-square&logo=github)](https://debateumu.github.io/BPMurcia/)
[![Edición 2027](https://img.shields.io/badge/Edición-2027%20(Próxima)-D9291C?style=flat-square)](https://debateumu.github.io/BPMurcia/2027/)
[![Edición 2026](https://img.shields.io/badge/Edición-2026-0f0f0f?style=flat-square)](https://debateumu.github.io/BPMurcia/2026/)
[![Organiza](https://img.shields.io/badge/Organiza-Club%20de%20Debate%20UMU-black?style=flat-square)](https://github.com/DebateUMU)

Repositorio web oficial del **Torneo de Debate BP Ciudad de Murcia**, organizado por la Asociación de Debate de la Universidad de Murcia (**Debate UMU**).

---

## 🔗 Enlaces Rápidos

| Edición | Web Oficial | Cronómetro Oficial |
| :--- | :--- | :--- |
| **Portal Principal** | [debateumu.github.io/BPMurcia](https://debateumu.github.io/BPMurcia/) | — |
| **BP Murcia 2027** | [debateumu.github.io/BPMurcia/2027](https://debateumu.github.io/BPMurcia/2027/) | [Timer 2027](https://debateumu.github.io/BPMurcia/2027/crono) |
| **BP Murcia 2026** | [debateumu.github.io/BPMurcia/2026](https://debateumu.github.io/BPMurcia/2026/) | [Timer 2026](https://debateumu.github.io/BPMurcia/2026/crono) |

---

## 📂 Estructura del Repositorio

El proyecto utiliza una arquitectura estática versionada por años para preservar el histórico de ediciones:

```text
BPMurcia/
├── index.html        # Portal principal (Selector de ediciones)
├── .gitignore        # Reglas de exclusión de Git
├── README.md         # Documentación técnica
│
├── 2027/             # Edición XII (2027) — Próxima
│   ├── index.html    # Landing page 2027 (Equipo académico en ?)
│   ├── crono.html    # Temporizador de debate parlamentario británico
│   ├── queTab.html   # Easter egg / Página de estado
│   ├── audio/        # Campanadas (1', 6') y alarma final (7')
│   └── img/          # Grafismos e imágenes
│
└── 2026/             # Edición XI (2026)
    ├── index.html    # Landing page 2026
    ├── crono.html    # Temporizador 2026
    ├── queTab.html   # Easter egg 2026
    ├── audio/        # Campanadas y alarmas
    └── img/          # Equipo de adjudicación 2026 y logos
```

---

## ⏱️ Funcionalidades del Cronómetro (`crono.html`)

- **Gestión de Tiempos BP**: Cuenta estándar regresiva y progresiva (7 min) con avisos sonoros y 15 segundos de tiempo de cortesía visual.
- **Atajos y Controles**:
  - `Espacio`: Iniciar / Pausar.
  - `Reset`: Reinicia manteniendo la configuración elegida.
  - Modo Oscuro / Claro / Silencio configurable.
- **Diseño Neo-Brutalista**: Máxima legibilidad y contraste para proyectores en sala.

---

## 🛠️ Cómo crear una nueva edición (ej. `2028`)

1. Duplica la carpeta de la última edición:
   ```bash
   cp -r 2027 2028
   ```
2. Modifica los textos y formularios en `2028/index.html`.
3. Añade la tarjeta de la nueva edición en el portal raíz `index.html`.

---

## 👥 Mantenimiento

Proyecto desarrollado y mantenido por el **Club de Debate de la Universidad de Murcia**.
