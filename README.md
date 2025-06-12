# Sistema de Detección de Emociones 🤖🎭  
> **Proyecto de Matemáticas Aplicadas II** – Universidad Icesi  

**Integrantes**  
- 🧑🏾Juan Diego Balanta Molina  
- 👩🏾Sara Castrillón Roldán  
- 👨🏻Alejandro Rendón  
- 👨🏿Camilo Vargas  

---

## 📚 Descripción

Este proyecto demuestra cómo los conceptos de **álgebra lineal**, **funciones de varias variables** y **optimización** se integran en un sistema de visión por computador que detecta emociones (felicidad, enojo y neutralidad) a partir de imágenes o video.  

El modelo se apoya en la librería **Ultralytics YOLO** (versión 11) para la detección facial y en análisis geométrico de puntos clave representados mediante **vectores** y **matrices**, tal como se estudia en Matemáticas Aplicadas II.

---

## 🛠️ Prerrequisitos

| Herramienta | Versión recomendada | Nota |
|-------------|--------------------|------|
| **Anaconda/Miniconda** | 23.x o superior | Facilita la gestión de entornos y dependencias |
| **Python** | 3.10 | Se instala dentro del entorno `conda` |
| **Git Bash** | Cualquier versión reciente | Usado para ejecutar los comandos en Windows |

> **Importante:** Clona o descomprime el repositorio y abre **Git Bash** directamente en la carpeta raíz donde se encuentran `README.md`, `best.pt` (modelo entrenado) y `main.py`.

---

## ⚙️ Instalación paso a paso

1. **Ejecuta estos codigos en serie al abrir GitBash en el directorio**  


conda active


conda create -n facial python=3.10 -y 


conda activate facial


pip install ultralytics


python main.py

