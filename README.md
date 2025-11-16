# 🎲 Cubo de Rubik - OpenGL

Implementación de un cubo de Rubik 3D interactivo usando OpenGL y GLUT en C.

**📚 Proyecto creado para la materia de Graficación por Computadora, en la Universidad Veracruzana.**

## 📸 Vista Previa

<img width="497" height="532" alt="Captura desde 2025-11-14 22-38-25" src="https://github.com/user-attachments/assets/57af1d69-753d-499b-873a-5fce1ddd0c00" />


*Vista del cubo de Rubik en ejecución*

## 🚀 Características

- ✅ Cubo de Rubik 3x3x3 completamente funcional
- 🔄 Rotación de caras con animación fluida
- 🖱️ Control de cámara con mouse
- 🔍 Zoom con scroll del mouse
- 🎨 Interfaz gráfica 3D

## 🛠️ Tecnologías Utilizadas

---

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![GLUT](https://img.shields.io/badge/GLUT-FF6B6B?style=for-the-badge&logo=opengl&logoColor=white)
![Mesa](https://img.shields.io/badge/Mesa-00A8FF?style=for-the-badge&logo=mesa&logoColor=white)

## 📋 Requisitos

- 🔧 Compilador GCC
- 🎮 OpenGL
- 🖼️ GLUT (freeglut)
- 📦 Mesa (Mesa-libGL)

## 💻 Instalación

### 🐧 Fedora/RHEL

```bash
sudo dnf5 install gcc gcc-c++ make cmake pkg-config -y
sudo dnf5 install freeglut-devel mesa-libGL-devel mesa-libGLU-devel -y
```

### 🐧 Ubuntu/Debian

```bash
sudo apt-get update
sudo apt-get install build-essential freeglut3-dev libgl1-mesa-dev libglu1-mesa-dev -y
```

## 🔨 Compilación

```bash
gcc -o Cubo_Rubik Cubo_Rubik.c -lGL -lGLU -lglut -lm
```

## ▶️ Ejecución

```bash
./Cubo_Rubik
```

## 🎮 Controles

### ⌨️ Teclado (Rotación de caras)

- **A / Q**: 🔝 Cara superior (normal / inversa)
- **S / W**: ➡️ Cara derecha (normal / inversa)
- **D / E**: 🔲 Cara frontal (normal / inversa)
- **F / R**: ⬅️ Cara izquierda (normal / inversa)
- **G / T**: 🔙 Cara trasera (normal / inversa)
- **H / Y**: ⬇️ Cara inferior (normal / inversa)

### 🖱️ Mouse

- **🖱️ Clic derecho + arrastrar**: 🔄 Rotar la vista del cubo
- **📜 Scroll del mouse**: 🔍 Zoom in/out

## 📁 Estructura del código

- 📄 `Cubo_Rubik.c`: Código fuente principal con toda la lógica del cubo de Rubik

## 👨‍💻 Autor

Luis Fernando Contreras Matla.

## 📚 Información Académica

Este proyecto fue desarrollado como parte de la Experiencia Educativa:

**Materia:** Graficación por Computadora.

**Universidad:** Universidad Veracruzana.

**Facultad:** Ingeniería Eléctrica y Electrónica.

**Docente:** Yuliana Berumen Diaz.

## 📄 Licencia

Este proyecto es de código abierto.

