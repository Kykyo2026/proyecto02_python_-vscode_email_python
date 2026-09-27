# 📈 Financial Market Analysis & RPA Email Automation / Análisis Bursátil y Automatización por Correo (RPA)

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?style=flat&logo=visualstudiocode)](https://vscode.dev/github/Kykyo2026/proyecto02_python_-vscode_email_python/blob/main/proyecto02.ipynb)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![yfinance](https://img.shields.io/badge/API-yfinance-green)
![RPA](https://img.shields.io/badge/Automation-PyAutoGUI-orange)

---

<!-- Versión en Español -->
[![Volver arriba](https://img.shields.io/badge/Volver_arriba-top-blue?style=flat-square)](#)

# 📈 Análisis Bursátil y Automatización por Correo (RPA)

## 📝 Descripción General
Este proyecto combina **análisis de datos financieros** con **automatización de procesos (RPA)** en Python. El programa extrae datos del mercado bursátil en tiempo real, calcula métricas clave de rendimiento, genera un gráfico de tendencias de las acciones y envía un reporte ejecutivo por correo electrónico de forma 100% automatizada.

---

## ⚙️ Funcionalidades Clave
1. **Extracción de Datos Financieros:** Descarga del histórico de precios para activos bursátiles (ej. Apple) usando la librería `yfinance`.
2. **Análisis Estadístico y Visualización:**
   * Generación de gráficos de tendencias con `matplotlib`.
   * Cálculo de métricas clave: precios máximos, mínimos y promedios del periodo.
3. **Automatización RPA:**
   * Control de interacciones de mouse y teclado mediante `pyautogui`.
   * Manejo de portapapeles con `pyperclip` para evitar errores con caracteres especiales.
   * Redacción y envío automático del informe por correo electrónico.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3
* **Librerías:**
  * `yfinance`: Extracción de datos financieros.
  * `matplotlib`: Visualización de datos.
  * `pyautogui` & `pyperclip`: Automatización de interfaz gráfica (GUI) y portapapeles.
  * `webbrowser` & `time`: Automatización de navegador y control de flujos de tiempo.

---

## 🚀 Cómo Ejecutar / How to Run

### 🌐 Abrir en línea (VS Code Web)
Inspecciona el cuaderno directamente en tu navegador sin instalar nada:  
[![Open in VS Code Web](https://img.shields.io/badge/Open_in-VS_Code_Web-blue?style=flat-square&logo=visualstudiocode)](https://github.dev/stiven-escobar/proyecto02_python_-vscode_email_python)

### 💻 Ejecución Local
```bash
# 1. Clonar el repositorio
git clone [https://github.com/stiven-escobar/proyecto02_python_-vscode_email_python.git](https://github.com/stiven-escobar/proyecto02_python_-vscode_email_python.git)

# 2. Entrar al directorio
cd proyecto02_python_-vscode_email_python
