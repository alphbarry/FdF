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

⚙️ Compilación
Asegúrate de tener la MiniLibX instalada. Luego, simplemente ejecuta:

make

Para limpiar archivos objeto:

make clean

🚀 Uso
Una vez compilado, puedes ejecutar el programa así:

./fdf maps/42.fdf
🔺 Nota: Asegúrate de pasarle un archivo con extensión .fdf. El programa validará esto antes de intentar abrirlo.

🗂️ Formato del archivo .fdf
Cada línea representa una fila, y cada número representa una altura z. Por ejemplo:

0 0 0 0
0 1 1 0
0 0 0 0
Este mapa tiene 3 filas y 4 columnas.

🖱️ Controles
W, A, S, D – Mover el mapa

+, - – Zoom

ESC – Salir

🧪 Ejemplos de mapas
Puedes encontrar ejemplos de mapas en la carpeta maps/ o generar los tuyos propios.

🧑‍💻 Autor
Este proyecto fue desarrollado como parte del programa de 42.

💼 [Alpha Omar Barry]

📫 [alphaomar9@gmail.com]

