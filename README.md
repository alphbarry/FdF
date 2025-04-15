# FdF - Wireframe Viewer 🗺️

Este proyecto es parte del plan de estudios de la escuela 42 y tiene como objetivo representar mapas en 3D mediante proyecciones isométricas o paralelas, a partir de un archivo `.fdf`.

## 🧠 Descripción

FdF (Fil de Fer) es un visualizador gráfico que lee un archivo de texto con valores de altura y lo transforma en una representación 3D de un terreno en forma de wireframe, utilizando la biblioteca MiniLibX para el renderizado gráfico.

### Funcionalidades

- Lectura y parseo de mapas `.fdf`.
- Visualización 3D en proyección isométrica.
- Interacción con el usuario (zoom, movimiento, etc).
- Control de errores y validaciones (extensión de archivo, contenido válido...).

## 📁 Estructura del Proyecto

```bash
.
├── includes/
│   └── fdf.h
├── srcs/
│   ├── main.c
│   ├── parse.c
│   ├── draw.c
│   ├── controls.c
│   └── utils.c
├── maps/
│   └── 42.fdf
├── libft/
├── Makefile
└── README.md
