<div align="center">

# 📊 Análisis de Series Temporales
### *Predicción de Vuelos mediante Técnicas Avanzadas de Machine Learning*

[![Python Version](https://img.shields.io/badge/python-3.12+-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5.svg?style=for-the-badge)](https://www.statsmodels.org/)
[![License](https://img.shields.io/badge/License-Educational-green.svg?style=for-the-badge)](LICENSE)

**[Explorar Documentación](#-documentación-del-proyecto)** • 
**[Instalación Rápida](#-guía-de-instalación)** • 
**[Ejemplos](#-uso-del-proyecto)** • 
**[Contribuir](#-cómo-contribuir)**

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

</div>

## 🎯 Visión General del Proyecto

Este proyecto implementa un sistema completo de **análisis predictivo de series temporales** aplicado específicamente a datos de vuelos. Utilizando técnicas estadísticas avanzadas y algoritmos de machine learning, el sistema permite identificar patrones, tendencias y comportamientos estacionales para realizar predicciones precisas sobre el tráfico aéreo futuro.

### 🌟 ¿Qué es una Serie Temporal?

<table>
<tr>
<td width="60%">

Una **serie temporal** es una secuencia de observaciones registradas cronológicamente a intervalos regulares. Cada punto de datos contiene:

- 📅 **Marca temporal** - Momento exacto de la observación
- 📊 **Valor medido** - Dato registrado en ese instante
- 🔗 **Dependencia temporal** - Relación con observaciones anteriores

La característica fundamental es que **el orden cronológico importa**: reordenar los datos destruye la información temporal contenida en ellos.

</td>
<td width="40%">

```
Ejemplo: Pasajeros Mensuales
━━━━━━━━━━━━━━━━━━━━━━━━━
Enero    →  12,450 pasajeros
Febrero  →  11,280 pasajeros
Marzo    →  13,670 pasajeros
Abril    →  14,520 pasajeros
...
```

</td>
</tr>
</table>

### 💡 ¿Por Qué Analizar Series Temporales?

<div align="center">

| 🎯 **Predicción** | 📈 **Planificación** | 🛡️ **Mitigación de Riesgos** |
|:---:|:---:|:---:|
| Anticipar valores futuros basándose en patrones históricos | Tomar decisiones estratégicas fundamentadas en datos | Prepararse para múltiples escenarios y reducir incertidumbre |

</div>

**Objetivo Principal:** Transformar la incertidumbre del futuro en pronósticos cuantificables mediante **forecasting** científico.

---

## 🌍 Aplicaciones en el Mundo Real

<table>
<tr>
<td align="center" width="25%">

### 🏢 Negocios
**Optimización de Inventarios**

Predecir ventas mensuales para ajustar stocks y reducir costos de almacenamiento

</td>
<td align="center" width="25%">

### 🌦️ Meteorología
**Pronóstico Climático**

Utilizar décadas de datos para generar predicciones meteorológicas precisas

</td>
<td align="center" width="25%">

### 🏥 Sector Salud
**Gestión de Recursos**

Anticipar afluencia en urgencias para planificar personal y equipamiento

</td>
<td align="center" width="25%">

### ✈️ Aviación
**Optimización de Rutas**

Predecir demanda de vuelos para maximizar eficiencia operativa

</td>
</tr>
</table>

---

## 🔬 Metodología: Descomposición de Series Temporales

Para comprender y modelar una serie temporal, la descomponemos en **tres componentes fundamentales**:

### 📈 1. Tendencia (Trend)

La **dirección general** que siguen los datos a largo plazo.

| Tipo | Característica | Ejemplo Práctico |
|:---:|:---|:---|
| **📈 Positiva** | Crecimiento sostenido en el tiempo | Incremento de usuarios en plataforma digital |
| **➡️ Estable** | Valores se mantienen constantes | Temperatura media anual en región templada |
| **📉 Negativa** | Decrecimiento progresivo | Ventas de tecnología obsoleta |

### 🔄 2. Estacionalidad (Seasonality)

**Patrones cíclicos** que se repiten en intervalos fijos y predecibles.

<table>
<tr>
<td align="center" width="33%">

**☀️ Estacionalidad Anual**

Variaciones que siguen el calendario:
- Ventas navideñas en diciembre
- Turismo en temporada estival
- Compras de material escolar en septiembre

</td>
<td align="center" width="33%">

**📅 Estacionalidad Semanal**

Patrones que se repiten cada semana:
- Mayor tráfico los viernes
- Menos actividad los domingos
- Picos de consumo a mitad de semana

</td>
<td align="center" width="33%">

**🕐 Estacionalidad Diaria**

Ciclos que ocurren cada día:
- Consumo eléctrico en horas pico
- Tráfico web al mediodía
- Uso de transporte público en rush hours

</td>
</tr>
</table>

### 🎲 3. Ruido (Noise)

**Variaciones aleatorias** que no siguen ningún patrón predecible.

- 🌩️ Eventos meteorológicos extremos inesperados
- 📊 Comportamientos anómalos sin precedente
- ⚙️ Errores de medición en sensores
- 🎉 Eventos extraordinarios (pandemias, crisis, etc.)

> 💡 **Nota Importante:** Los algoritmos estadísticos modernos están diseñados específicamente para identificar y filtrar el ruido, extrayendo únicamente las señales significativas.

---

## 🛠️ Stack Tecnológico

<div align="center">

### Tecnologías Core

| Herramienta | Versión Mínima | Descripción | Propósito en el Proyecto |
|:---:|:---:|:---|:---|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | **3.12+** | Lenguaje de programación principal | Base del ecosistema de análisis |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | **1.1.1+** | Entorno de desarrollo interactivo | Experimentación y documentación viva |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | **3.0.2+** | Librería de manipulación de datos | Procesamiento y transformación de datasets |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square) | **3.10.8+** | Motor de visualización | Generación de gráficos y dashboards |
| ![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5?style=flat-square) | **0.14.6+** | Suite de modelos estadísticos | Implementación de ARIMA, SARIMA y forecasting |

</div>

---

## 📁 Arquitectura del Proyecto

```
📦 analisis-temporales/
┣ 📂 docs/                              # 📚 Documentación y presentaciones
┃ ┗ 📄 Aprende-Analisis-de-Series-Temporales.pdf
┃
┣ 📂 notebooks/                         # 📓 Jupyter notebooks de análisis
┃ ┣ 📊 prediccion_vuelos.ipynb          #     Predicción Arima y Sarima
┣ ⚙️ pyproject.toml                     # 📦 Configuración y dependencias
┣ 🔒 uv.lock                            # 🔐 Lockfile de versiones
┣ 🔢 .python-version                    # Versión específica de Python
┣ 🚫 .gitignore                         # Archivos excluidos del control de versiones
┗ 📖 README.md                          # Este archivo
```

---

## 🚀 Guía de Instalación

### Requisitos del Sistema

<table>
<tr>
<td>

**Software Necesario:**
- ✅ Python 3.12 o superior
- ✅ pip (gestor de paquetes) o uv
- ✅ Git (control de versiones)
- ✅ 4GB RAM mínimo recomendado
- ✅ 500MB espacio en disco

</td>
<td>

**Opcional pero Recomendado:**
- 🔧 Visual Studio Code o PyCharm
- 🐳 Docker (para entornos containerizados)
- 📊 Git LFS (si se trabaja con datasets grandes)

</td>
</tr>
</table>

### Instalación Paso a Paso

#### 🔷 Paso 1: Clonar el Repositorio

```bash
# Clonar proyecto desde GitHub
git clone https://github.com/gemayc/analisis-temporales.git

# Navegar al directorio del proyecto
cd analisis-temporales
```

#### 🔷 Paso 2: Configurar Entorno Virtual

```bash
# Crear entorno virtual aislado
python -m venv venv

# Activar entorno virtual
# En sistemas Unix/Linux/macOS:
source venv/bin/activate

# En Windows (CMD):
venv\Scripts\activate.bat

# En Windows (PowerShell):
venv\Scripts\Activate.ps1
```

#### 🔷 Paso 3: Instalar Dependencias

**Opción A: Instalación con pip (tradicional)**

```bash
pip install --upgrade pip
pip install jupyter pandas matplotlib statsmodels
```

**Opción B: Instalación con uv (recomendado - más rápido)**

```bash
# Si no tienes uv instalado:
pip install uv

# Sincronizar dependencias del proyecto:
uv sync
```

#### 🔷 Paso 4: Verificar Instalación

```bash
# Verificar versión de Python
python --version

# Verificar instalación de paquetes
python -c "import pandas, matplotlib, statsmodels; print('✓ Todas las dependencias instaladas correctamente')"
```

---


## 🧠 Técnicas y Modelos Implementados

### 📊 Métodos Estadísticos Clásicos

<table>
<tr>
<td width="50%">

#### ARIMA (AutoRegressive Integrated Moving Average)

**Ideal para:**
- ✅ Series con tendencia clara
- ✅ Datos sin estacionalidad marcada
- ✅ Predicciones de corto-medio plazo

**Componentes:**
- **AR (p):** Componente autorregresivo
- **I (d):** Grado de diferenciación
- **MA (q):** Media móvil

</td>
<td width="50%">

#### SARIMA (Seasonal ARIMA)

**Ideal para:**
- ✅ Series con patrones estacionales
- ✅ Datos que varían según calendario
- ✅ Predicciones que consideran ciclos

**Parámetros adicionales:**
- **P, D, Q:** Componentes estacionales
- **s:** Periodicidad (12 para mensual, 7 para semanal)

</td>
</tr>
</table>




---

## 📖 Documentación del Proyecto

### 📚 Presentación Educativa Incluida

<div align="center">

**📄 [Aprende Análisis de Series Temporales](docs/Aprende-Analisis-de-Series-Temporales.pdf)**

<img src="https://img.shields.io/badge/Formato-PDF-red?style=for-the-badge&logo=adobe-acrobat-reader" alt="PDF">
<img src="https://img.shields.io/badge/Páginas-20+-blue?style=for-the-badge" alt="Pages">
<img src="https://img.shields.io/badge/Idioma-Español-green?style=for-the-badge" alt="Language">

</div>

#### 📋 Contenido de la Presentación:

- ✅ **Fundamentos Teóricos** - Conceptos básicos de series temporales
- ✅ **Componentes Detallados** - Tendencia, estacionalidad y ruido explicados
- ✅ **Casos de Uso Reales** - Aplicaciones en negocios, salud y aviación
- ✅ **Metodologías** - Comparativa de métodos estadísticos, ML y DL
- ✅ **Guías Visuales** - Diagramas y ejemplos ilustrativos
- ✅ **Best Practices** - Recomendaciones para proyectos reales

#### 🖥️ Visualizar la Presentación

```bash
# Linux/Unix
xdg-open docs/Aprende-Analisis-de-Series-Temporales.pdf

# macOS
open docs/Aprende-Analisis-de-Series-Temporales.pdf

# Windows
start docs/Aprende-Analisis-de-Series-Temporales.pdf
```

### 📚 Recursos de Aprendizaje Recomendados

<table>
<tr>
<th>Tipo</th>
<th>Recurso</th>
<th>Descripción</th>
</tr>
<tr>
<td>📘 Documentación</td>
<td><a href="https://www.statsmodels.org/">Statsmodels Official Docs</a></td>
<td>Guía completa de modelos estadísticos en Python</td>
</tr>
<tr>
<td>📘 Documentación</td>
<td><a href="https://pandas.pydata.org/docs/user_guide/timeseries.html">Pandas Time Series</a></td>
<td>Manipulación avanzada de series temporales</td>
</tr>
<tr>
<td>📘 Documentación</td>
<td><a href="https://matplotlib.org/stable/gallery/index.html">Matplotlib Gallery</a></td>
<td>Galería de ejemplos de visualización</td>
</tr>
<tr>
<td>📖 Libro</td>
<td>"Forecasting: Principles and Practice"</td>
<td>Rob J Hyndman & George Athanasopoulos</td>
</tr>
<tr>
<td>📖 Libro</td>
<td>"Time Series Analysis and Applications"</td>
<td>Robert H. Shumway & David S. Stoffer</td>
</tr>
<tr>
<td>📖 Libro</td>
<td>"Análisis de Series Temporales"</td>
<td>Daniel Peña (en español)</td>
</tr>
</table>

---

## 🤝 Cómo Contribuir

¡Las contribuciones son bienvenidas y valoradas! Aquí te explicamos cómo participar:

### 🌟 Formas de Contribuir

<table>
<tr>
<td align="center" width="25%">

**🐛 Reportar Bugs**

Encontraste un error? [Abre un issue](https://github.com/gemayc/analisis-temporales/issues/new)

</td>
<td align="center" width="25%">

**💡 Sugerir Features**

Tienes ideas? Compártelas en las [discusiones](https://github.com/gemayc/analisis-temporales/discussions)

</td>
<td align="center" width="25%">

**📝 Mejorar Docs**

Ayuda a mejorar la documentación y los ejemplos

</td>
<td align="center" width="25%">

**🔧 Código**

Implementa nuevas funcionalidades o mejoras

</td>
</tr>
</table>

### 📝 Proceso de Contribución

```bash
# 1. Fork el proyecto
# Haz click en "Fork" en la página de GitHub

# 2. Clona tu fork
git clone https://github.com/TU-USUARIO/analisis-temporales.git
cd analisis-temporales

# 3. Crea una rama para tu feature
git checkout -b feature/nueva-funcionalidad

# 4. Realiza tus cambios y commitea
git add .
git commit -m "feat: descripción de la nueva funcionalidad"

# 5. Push a tu fork
git push origin feature/nueva-funcionalidad

# 6. Abre un Pull Request en GitHub
```

### ✅ Guías de Estilo

- 🐍 Seguir [PEP 8](https://pep8.org/) para código Python
- 📝 Documentar funciones con docstrings
- ✅ Incluir tests cuando sea posible
- 📊 Agregar ejemplos de uso
- 🔄 Actualizar README si es necesario

---

## 👥 Autores

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<img src="https://github.com/gemayc.png" width="100px;" alt="Gema"/><br>
<sub><b>Gema Yágüez</b></sub><br>
<a href="https://github.com/gemayc">
<img src="https://img.shields.io/badge/GitHub-gemayc-181717?style=flat-square&logo=github" alt="GitHub gemayc">
</a>
</td>
<td align="center" width="50%">
<img src="https://github.com/mcarenashd.png" width="100px;" alt="Camila"/><br>
<sub><b>Camila Arenas</b></sub><br>
<a href="https://github.com/mcarenashd">
<img src="https://img.shields.io/badge/GitHub-mcarenashd-181717?style=flat-square&logo=github" alt="GitHub mcarenashd">
</a>
</td>
</tr>
</table>

### 💭 Filosofía del Proyecto

> *"Las series temporales nos recuerdan que cada dato tiene un ritmo, una historia y una señal por descubrir.*  
> *El análisis de datos convierte ese movimiento en decisiones más claras y un futuro mejor entendido."*

</div>

---

## 📝 Licencia

Este proyecto está disponible bajo licencia educativa para fines de aprendizaje e investigación.

```
Copyright © 2026 Gema Yágüez & Camila Arenas
Todos los derechos reservados para uso educativo y académico.
```

---

## 🙏 Agradecimientos

<div align="center">

Agradecemos profundamente a:

**🌐 La Comunidad Open Source**
- Mantenedores de Python, Pandas, Matplotlib y Statsmodels
- Contribuidores de Jupyter y el ecosistema científico de Python

**📚 La Comunidad Académica**
- Investigadores que comparten conocimiento abiertamente
- Autores de libros y papers que inspiran este trabajo

**💻 Plataformas de Desarrollo**
- GitHub por el hosting y herramientas de colaboración
- Stack Overflow por resolver nuestras dudas

**👥 Colaboradores Futuros**
- Todos los que contribuyan a mejorar este proyecto

</div>

---

## 📞 Contacto y Soporte

<div align="center">

| Canal | Descripción | Enlace |
|:---:|:---|:---:|
| 🐛 **Issues** | Reportar bugs o problemas | [Abrir Issue](https://github.com/gemayc/analisis-temporales/issues) |
| 💬 **Discussions** | Preguntas y conversaciones | [Ir a Discusiones](https://github.com/gemayc/analisis-temporales/discussions) |
| 📧 **Email** | Contacto directo con autores | Ver perfiles de GitHub |
| ⭐ **Star** | Apoya el proyecto | [Dale una estrella](https://github.com/gemayc/analisis-temporales) |

</div>

---

## ⚠️ Notas Importantes

> 🔴 **Versión de Python:** Este proyecto requiere Python 3.12 o superior  
> 🟡 **Entorno Virtual:** Altamente recomendado para evitar conflictos  
> 🟢 **Secuencia de Notebooks:** Ejecutar en orden numérico para mejor comprensión  
> 🔵 **Datos de Ejemplo:** Los notebooks incluyen datasets de demostración

---

<div align="center">

## 🌟 ¿Te Resulta Útil Este Proyecto?

**¡Considera darle una estrella en GitHub!** ⭐

[![GitHub stars](https://img.shields.io/github/stars/gemayc/analisis-temporales?style=social)](https://github.com/gemayc/analisis-temporales/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gemayc/analisis-temporales?style=social)](https://github.com/gemayc/analisis-temporales/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/gemayc/analisis-temporales?style=social)](https://github.com/gemayc/analisis-temporales/watchers)

---

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

**Hecho con ❤️ por Gema & Camila**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-💚-green.svg?style=for-the-badge)
![Python](https://img.shields.io/badge/Powered%20by-Python-blue.svg?style=for-the-badge&logo=python)

**Última actualización:** Abril 2026 | **Versión:** 1.0.0

</div>