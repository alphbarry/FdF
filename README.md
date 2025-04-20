# FdF - Wireframe Viewer 🗺️

## 🧠 Descripción

**FdF (Fil de Fer)** es un visualizador gráfico 3D desarrollado como parte del plan de estudios de la escuela 42. Su objetivo es representar mapas en forma de wireframes (rejillas) utilizando proyecciones isométricas o paralelas, a partir de un archivo de texto `.fdf` con valores de altura.

Este proyecto fue diseñado para afianzar conceptos como lectura de archivos, estructuras de datos, gráficos en 2D/3D, transformaciones espaciales y control de eventos, utilizando C y la biblioteca gráfica MiniLibX.

---

## ⚙️ Instalación

### Requisitos

- Sistema operativo basado en UNIX (Linux, macOS).
- Compilador C (`gcc` o `clang`).
- Biblioteca gráfica **MiniLibX** instalada.
- Make.

### Pasos de instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/fdf.git

    Accede al directorio del proyecto:

cd fdf

Compila el proyecto:

make

(Opcional) Limpia archivos objeto:

    make clean

💻 Tecnologías Utilizadas

    Lenguaje C

    Biblioteca MiniLibX (renderizado gráfico)

    Libft (funciones de utilidad)

    Sistema de ventanas X11 (Linux) o macOS Frameworks

    Control de eventos de teclado y renderizado 2D/3D

🚀 Instrucciones de Uso

Una vez compilado, puedes ejecutar el programa con un archivo .fdf:

./fdf maps/42.fdf

🔺 Nota: El archivo debe tener extensión .fdf. El programa validará su contenido antes de procesarlo.
🗂️ Formato del archivo .fdf

Cada archivo .fdf es una matriz de números enteros que representan las elevaciones (z) del terreno. Cada línea del archivo representa una fila del mapa.

Ejemplo:

0 0 0 0
0 1 1 0
0 0 0 0

Este mapa tiene 3 filas y 4 columnas, y genera una elevación central en forma de “meseta”.
🖱️ Controles

    W, A, S, D – Mover el mapa

    +, - – Zoom in/out

    ESC – Salir del programa

📁 Estructura del Proyecto

.
├── includes/
│   └── fdf.h             # Header principal
├── srcs/
│   ├── main.c            # Punto de entrada
│   ├── parse.c           # Lectura y parseo de archivos .fdf
│   ├── draw.c            # Renderizado de líneas
│   ├── controls.c        # Manejo de teclas y eventos
│   └── utils.c           # Funciones auxiliares
├── maps/                 # Mapas de ejemplo
│   └── 42.fdf
├── libft/                # Librería personalizada
├── Makefile
└── README.md

🧪 Ejemplos de Mapas

Puedes utilizar los archivos en la carpeta maps/ o crear tus propios mapas .fdf. Asegúrate de que sigan el formato correcto para una visualización adecuada.
👨‍💻 Autor

Este proyecto fue desarrollado como parte del programa de formación de la École 42.
