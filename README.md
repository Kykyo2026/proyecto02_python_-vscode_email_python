# 📈 Financial Market Analysis & RPA Email Automation / Análisis Bursátil y Automatización por Correo (RPA)

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?style=flat&logo=visualstudiocode)](https://vscode.dev/github/Kykyo2026/proyecto02_python_-vscode_email_python/blob/main/proyecto02.ipynb)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![yfinance](https://img.shields.io/badge/API-yfinance-green)
![RPA](https://img.shields.io/badge/Automation-PyAutoGUI-orange)

---

## 🌐 English Description

### 📝 Overview
This project combines **financial data analysis** with **Robotic Process Automation (RPA)** in Python. The script extracts real-time stock market data, calculates key performance metrics, generates visual trends, and automatically drafts and sends an executive report via Gmail without manual intervention.

### 🎯 Key Features
1. **Financial Data Extraction:** Downloads historical closing prices for stock tickers (e.g., Apple `AAPL`) using the `yfinance` API.
2. **Statistical Analysis & Visualization:**
   * Generates price trend charts using `matplotlib`.
   * Computes key financial statistics: maximum, minimum, and average closing prices over the selected timeframe.
3. **Robotic Process Automation (RPA):**
   * Automates GUI interactions (clicks, keyboard strokes) via `PyAutoGUI`.
   * Leverages `pyperclip` for secure clipboard buffer handling to prevent encoding errors during text insertion.
   * Automates browser navigation and dispatches email reports to stakeholders.

### 🛠️ Tech Stack & Libraries
* **Python 3.x**
* **`yfinance`**: Financial data retrieval.
* **`matplotlib`**: Data visualization.
* **`pyautogui` & `pyperclip`**: Desktop/GUI automation and clipboard control.
* **`webbrowser` & `time`**: Browser automation and workflow timing control.

---

## 🌐 Descripción en Español

### 📝 Descripción General
Este proyecto combina **análisis de datos financieros** con **automatización de procesos (RPA)** en Python. El programa descarga información del mercado bursátil en tiempo real, procesa estadísticas clave sobre el rendimiento de las acciones y genera un reporte que envía por correo electrónico a través del navegador de manera 100% automatizada.

### 🎯 Funcionalidades Clave
1. **Extracción de Datos Financieros:** Descarga del histórico de precios de cierre para tickers bursátiles (ej. Apple `AAPL`) usando la librería `yfinance`.
2. **Análisis Estadístico y Visualización:**
   * Generación de gráficos de tendencias con `matplotlib`.
   * Cálculo de métricas clave: precio máximo, mínimo y promedio del periodo.
3. **Automatización RPA:**
   * Control dinámico de mouse y teclado con `PyAutoGUI`.
   * Manejo de portapapeles con `pyperclip` para evitar errores de caracteres especiales.
   * Redacción y envío automático del informe por correo electrónico.

---

## 🚀 How to Run / Cómo Ejecutar

### 💻 Open Online / Abrir en línea
Click to open and inspect the notebook directly in your browser:  
👉 [**Open Project in VS Code Web**](https://vscode.dev/github/Kykyo2026/proyecto02_python_-vscode_email_python/blob/main/proyecto02.ipynb)

### 🐍 Run Locally / Ejecución Local
1. Clone the repository / Clona el repositorio:
   ```bash
   git clone [https://github.com/Kykyo2026/proyecto02_python_-vscode_email_python.git](https://github.com/Kykyo2026/proyecto02_python_-vscode_email_python.git)
