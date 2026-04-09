# Análisis de Series Temporales

Proyecto de análisis temporal para la predicción de vuelos utilizando Python y Jupyter notebooks.

## 📋 Descripción

Este proyecto se centra en el análisis de series temporales aplicado a datos de vuelos, implementando técnicas estadísticas y de machine learning para el análisis, visualización y predicción de patrones temporales. Desarrollado en Python, utiliza notebooks interactivos para facilitar la exploración y experimentación con diferentes modelos y técnicas.

## 🛠️ Tecnologías y Dependencias

El proyecto está construido con las siguientes tecnologías:

- **Python**: >= 3.12
- **Jupyter**: >= 1.1.1 - Entorno interactivo para notebooks
- **Pandas**: >= 3.0.2 - Manipulación y análisis de datos
- **Matplotlib**: >= 3.10.8 - Visualización de datos
- **Statsmodels**: >= 0.14.6 - Modelos estadísticos para series temporales

## 📁 Estructura del Proyecto

```
analisis-temporales/
├── docs/              # Documentación y presentaciones del proyecto
├── notebooks/         # Jupyter notebooks con análisis y experimentación
├── main.py           # Script principal de ejecución
├── pyproject.toml    # Configuración del proyecto y dependencias
├── uv.lock          # Archivo de bloqueo de dependencias
├── .python-version  # Versión de Python especificada
├── .gitignore       # Archivos y carpetas ignorados por git
└── README.md        # Documentación del proyecto
```

## 🚀 Instalación

### Requisitos Previos

- Python 3.12 o superior
- pip o uv (gestor de paquetes Python)

### Pasos de Instalación

1. **Clonar el repositorio:**
```bash
git clone https://github.com/gemayc/analisis-temporales.git
cd analisis-temporales
```

2. **Crear un entorno virtual (recomendado):**
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. **Instalar dependencias:**

Usando pip:
```bash
pip install -r pyproject.toml
```

O usando uv (si está disponible):
```bash
uv sync
```

## 💻 Uso

### Ejecutar el script principal

```bash
python main.py
```

### Trabajar con notebooks

1. Iniciar Jupyter Lab o Jupyter Notebook:
```bash
jupyter lab
# o
jupyter notebook
```

2. Navegar a la carpeta `notebooks/` y abrir el notebook deseado.

### Notebooks Disponibles

Los notebooks en el directorio `notebooks/` contienen análisis exploratorio, modelado y visualización de series temporales aplicadas a datos de vuelos.

## 📊 Características Principales

- **Análisis Exploratorio**: Exploración y visualización de patrones en datos de vuelos
- **Preprocesamiento**: Limpieza y transformación de datos temporales
- **Modelado Estadístico**: Implementación de modelos ARIMA, SARIMA y otros modelos de series temporales
- **Visualizaciones**: Gráficos interactivos para análisis de tendencias, estacionalidad y patrones
- **Predicción**: Forecasting de variables relacionadas con vuelos

## 🔍 Métodos y Técnicas

El proyecto implementa diversas técnicas de análisis de series temporales, incluyendo:

- Descomposición de series temporales (tendencia, estacionalidad, residuos)
- Análisis de autocorrelación (ACF y PACF)
- Modelos ARIMA y variantes
- Validación cruzada para series temporales
- Métricas de evaluación (MAE, RMSE, MAPE)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está disponible para uso educativo y de investigación.

## 👤 Autor

**gemayc**
- GitHub: [@gemayc](https://github.com/gemayc)
- GitHub: [@mcarenashd](https://github.com/mcarenashd)

## 🙏 Agradecimientos

- A la comunidad de Python y los mantenedores de las librerías utilizadas
- A todos los contribuidores que ayuden a mejorar este proyecto

## 📚 Recursos Adicionales

- [Documentación de Statsmodels](https://www.statsmodels.org/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Jupyter Documentation](https://jupyter.org/documentation)

## 📖 Documentación del Proyecto

En la carpeta `/docs` encontrarás documentación adicional sobre el proyecto:

- **Presentación del Proyecto**: Documento PDF con la descripción general, objetivos, metodología y resultados del análisis de series temporales aplicado a datos de vuelos.

Para acceder a la presentación completa:
```bash
# Ver archivos en la carpeta docs
ls docs/

# Abrir la presentación (desde la raíz del proyecto)
# En Linux/Mac
xdg-open docs/[Aprende-Analisis-de-Series-Temporales].pdf

# En Windows
start docs/[Aprende-Analisis-de-Series-Temporales].pdf
```

## ⚠️ Notas

- Asegúrate de tener instalada la versión correcta de Python (>= 3.12)
- Los notebooks están diseñados para ejecución secuencial
- Se recomienda trabajar en un entorno virtual para evitar conflictos de dependencias

---

