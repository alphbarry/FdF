# FdF - Wireframe Viewer 🗺️

## 🧠 Description

**FdF (Fil de Fer)** is a 3D graphics viewer developed as part of the School 42 curriculum. Its objective is to represent maps in the form of wireframes (grids) using isometric or parallel projections, from a .fdf text file with height values.

This project was designed to reinforce concepts such as file reading, data structures, 2D/3D graphics, spatial transformations, and event handling, using C and the MiniLibX graphics library.

---

## ⚙️ Facility

### Requisites

- UNIX-based operating system (Linux, macOS).
- C compiler (`gcc` or `clang`).
- **MiniLibX** graphics library installed.
- Make.

### Pasos de instalación

1. Clone the repository
   ```bash
   git clone https://github.com/alphbarry/FdF.git

2. Access the project directory:
   ```bash
   cd fdf

3. Compile the project:
   ```bash
   make

(Optional) Clean up object files:

    make clean

💻 Technologies Used

    C Language

    MiniLibX Library (graphical rendering)

    Libft (utility functions)

    X11 Window System (Linux) or macOS Frameworks

    Keyboard event handling and 2D/3D rendering

🚀 Instructions for Use

Once compiled, you can run the program with a .fdf file:

./fdf maps/42.fdf

🔺 Note: The file must have a .fdf extension. The program will validate its contents before processing it.
🗂️ .fdf file format

Each .fdf file is a matrix of integers representing the elevations (z) of the terrain. Each line in the file represents a row of the map.

Example:

0 0 0 0
0 1 1 0
0 0 0 0

This map has 3 rows and 4 columns, and creates a central elevation in the shape of a "plateau."

🖱️ Controls

    W, A, S, D – Move the map

    +, - – Zoom in/out

    ESC – Exit the program

📁 Project Structure

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

🧪 Map Examples

You can use the files in the maps/ folder or create your own .fdf maps. Make sure they follow the correct format for proper viewing.

👨‍💻 Author
alphbarry
This project was developed as part of the École 42 training program.
