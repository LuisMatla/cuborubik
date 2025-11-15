# Cubo de Rubik - OpenGL

Implementación de un cubo de Rubik 3D interactivo usando OpenGL y GLUT en C.

**Proyecto creado para la materia de Graficación por Computadora, en la Universidad Veracruzana.**

## Características

- Cubo de Rubik 3x3x3 completamente funcional
- Rotación de caras con animación fluida
- Control de cámara con mouse
- Zoom con scroll del mouse
- Interfaz gráfica 3D

## Requisitos

- Compilador GCC
- OpenGL
- GLUT (freeglut)
- Mesa (Mesa-libGL)

## Instalación

### Fedora/RHEL

```bash
sudo dnf5 install gcc gcc-c++ make cmake pkg-config -y
sudo dnf5 install freeglut-devel mesa-libGL-devel mesa-libGLU-devel -y
```

### Ubuntu/Debian

```bash
sudo apt-get update
sudo apt-get install build-essential freeglut3-dev libgl1-mesa-dev libglu1-mesa-dev -y
```

## Compilación

```bash
gcc -o Cubo_Rubik Cubo_Rubik.c -lGL -lGLU -lglut -lm
```

## Ejecución

```bash
./Cubo_Rubik
```

## Controles

### Teclado (Rotación de caras)

- **A / Q**: Cara superior (normal / inversa)
- **S / W**: Cara derecha (normal / inversa)
- **D / E**: Cara frontal (normal / inversa)
- **F / R**: Cara izquierda (normal / inversa)
- **G / T**: Cara trasera (normal / inversa)
- **H / Y**: Cara inferior (normal / inversa)

### Mouse

- **Clic derecho + arrastrar**: Rotar la vista del cubo
- **Scroll del mouse**: Zoom in/out

## Estructura del código

- `Cubo_Rubik.c`: Código fuente principal con toda la lógica del cubo de Rubik

## Autor

Luis Matla

## Información del Proyecto

Este proyecto fue desarrollado como parte de la materia de **Graficación por Computadora** en la **Universidad Veracruzana**.

## Licencia

Este proyecto es de código abierto.

