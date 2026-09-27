# 📊 Análisis de Acciones & Automatización de Reportes / Stock Analysis & Automated Reporting

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?logo=visualstudiocode)](https://vscode.dev/github/stiven-escobar/proyecto02_python_-vscode_email_python)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![yfinance](https://img.shields.io/badge/Library-yfinance-green)](https://pypi.org/project/yfinance/)
[![PyAutoGUI](https://img.shields.io/badge/Automation-PyAutoGUI-orange)](https://pypi.org/project/PyAutoGUI/)

---

## 🌐 Español

### 📌 Descripción del Proyecto
Este proyecto es una solución automatizada desarrollada en Python para la extracción, análisis estadístico y envío automatizado de métricas del mercado bursátil[cite: 1, 2]. 

Permite consultar los datos históricos de cotización de cualquier acción (ej. Apple - `AAPL`) utilizando la API de `yfinance`, procesar sus métricas clave (precio máximo, mínimo y promedio)[cite: 1, 2] y automatizar la notificación de los resultados por correo electrónico a través de `pyautogui` y `pyperclip`[cite: 2, 3].

### 🛠️ Tecnologías y Librerías Utilizadas
* **Python 3.x**[cite: 1]
* **`yfinance`**: Descarga de datos históricos de cotizaciones bursátiles[cite: 1].
* **`matplotlib`**: Generación de gráficos de líneas para visualizar la evolución del precio de cierre[cite: 1].
* **`pyautogui` & `pyperclip`**: Automatización GUI para la interacción con la plataforma de correo electrónico[cite: 2, 3].
* **`webbrowser` & `time`**: Control del navegador web y tiempos de espera de la ejecución[cite: 2, 3].

### ⚙️ Funcionalidades Principales
1. **Extracción de Datos de Mercado**: Descarga interactiva de datos de cotización de acciones según el símbolo del ticker y el rango de tiempo deseado[cite: 1].
2. **Visualización Gráfica**: Generación de gráficos simples del precio de cierre histórico[cite: 1].
3. **Análisis Estadístico de Métricas**: Cálculo automático de:
   * Precio máximo alcanzado en el período[cite: 2].
   * Precio mínimo registrado[cite: 2].
   * Valor medio/promedio de la cotización[cite: 2].
4. **Automatización de Notificaciones**: Envío automatizado de resúmenes analíticos vía e-mail[cite: 2, 3].

---

## 🌐 English

### 📌 Project Overview
This project is an automated Python pipeline designed to extract, analyze, and automatically send financial performance metrics for publicly traded stocks[cite: 1, 2].

It allows querying historical stock data (e.g., Apple - `AAPL`) using the `yfinance` library, calculating key summary metrics (maximum, minimum, and average prices)[cite: 1, 2], and automating email dispatch of reports using `pyautogui` and `pyperclip`[cite: 2, 3].

### 🛠️ Tech Stack & Libraries
* **Python 3.x**[cite: 1]
* **`yfinance`**: Historical stock market data extraction[cite: 1].
* **`matplotlib`**: Time-series visualization of closing prices[cite: 1].
* **`pyautogui` & `pyperclip`**: GUI automation for web browser and email composition[cite: 2, 3].
* **`webbrowser` & `time`**: Browser navigation control and execution delay handling[cite: 2, 3].

### ⚙️ Key Features
1. **Market Data Retrieval**: Interactive prompt to download stock ticker data for customized timeframes[cite: 1].
2. **Data Visualization**: Automatic plotting of historical close prices[cite: 1].
3. **Financial Metric Calculation**: Automatically computes:
   * Maximum stock price in period[cite: 2].
   * Minimum stock price in period[cite: 2].
   * Mean/average stock value[cite: 2].
4. **Automated Email Reporting**: End-to-end automation to format and send market summaries via email[cite: 2, 3].

---

## 👤 Autor / Author

**Stiven Escobar Carabalí**[cite: 4, 5]  
* Profesional en Administración Comercial y Mercadeo
* Tecnólogo en Análisis y Desarrollo de Software (ADSO)
* Especialista en Analítica de Datos

[![GitHub](https://img.shields.io/badge/GitHub-stiven--escobar-181717?logo=github)](https://github.com/stiven-escobar)[cite: 4]
