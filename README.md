# 🎬 Netflix Data Analytics Platform

> **Un análisis integral del catálogo de Netflix utilizando la arquitectura de datos Medallion**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Data Engineering](https://img.shields.io/badge/Data-Engineering-red.svg)]()
[![Analytics](https://img.shields.io/badge/Analytics-Insights-green.svg)]()
[![Medallion Architecture](https://img.shields.io/badge/Architecture-Medallion-yellow.svg)]()

## 🌟 Descripción del Proyecto

Este proyecto implementa un pipeline de análisis de datos completo del catálogo de Netflix, aplicando la **arquitectura Medallion** (Bronze, Silver, Gold) para el procesamiento y transformación de datos. El objetivo es extraer insights valiosos sobre el contenido, tendencias y patrones de la plataforma de streaming más popular del mundo.

## 🏗️ Arquitectura Medallion

### 🥉 **Capa Bronze (Datos Crudos)**
- Ingesta de datos en su formato original
- Validación de calidad de datos
- Almacenamiento de datos históricos

### 🥈 **Capa Silver (Datos Limpios)**
- Limpieza y estandarización de datos
- Transformaciones de negocio
- Datos preparados para análisis

### 🥇 **Capa Gold (Datos Analíticos)**
- Tablas agregadas y optimizadas
- Métricas de negocio
- Datos listos para dashboards y reportes

## 📊 Fuentes de Datos

El proyecto utiliza datasets completos de Netflix que incluyen:

- **📁 netflix_titles.csv**: Catálogo completo con metadatos de títulos
- **📁 credits.csv**: Información detallada del cast y crew
- **📁 titles.csv**: Datos adicionales de títulos y clasificaciones

## 🔍 Análisis Implementados

### 📈 Análisis Exploratorio
- Distribución de contenido por tipo (Series vs Películas)
- Análisis temporal de lanzamientos
- Países con mayor producción de contenido

### 🎯 Insights de Negocio
- Géneros más populares por región
- Análisis de duración de contenido
- Tendencias de producción por año
- Análisis de rating y clasificaciones

### 🌍 Análisis Geográfico
- Mapa de contenido por países
- Análisis de contenido local vs internacional
- Preferencias regionales de géneros

## 🚀 Estructura del Proyecto

```
Netflix/
├── 📊 data/                    # Datasets originales
│   ├── credits.csv
│   ├── netflix_titles.csv
│   └── titles.csv
├── 📝 note/                    # Documentación técnica
│   ├── Bronze/                 # Procesos de capa Bronze
│   ├── Silver/                 # Transformaciones Silver
│   ├── gold/                   # Analytics Gold
│   └── job/                    # Configuración de jobs
└── 📖 README.md               # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **🐍 Python**: Lenguaje principal para análisis
- **🐼 Pandas**: Manipulación y análisis de datos
- **📊 Matplotlib/Seaborn**: Visualización de datos
- **🔢 NumPy**: Computación numérica
- **📈 Plotly**: Visualizaciones interactivas
- **🏗️ Medallion Architecture**: Patrón de arquitectura de datos

## 📋 Prerrequisitos

```bash
Python 3.8+
pandas
matplotlib
seaborn
plotly
numpy
jupyter
```

## 🚀 Cómo Empezar

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/miguelASL/Netflix.git
   cd Netflix
   ```

2. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar análisis**
   ```bash
   python main.py
   ```

## 📈 Resultados Esperados

- **Dashboard interactivo** con métricas clave de Netflix
- **Reportes automatizados** de tendencias de contenido
- **Insights accionables** para estrategias de contenido
- **Visualizaciones dinámicas** de patrones de datos

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Miguel Sarmiento**
- GitHub: [@miguelASL](https://github.com/miguelASL)
- LinkedIn: [Miguel Sarmiento](https://www.linkedin.com/in/miguel-sarmiento-levy/)

## 🙏 Agradecimientos

- Dataset proporcionado por la comunidad de Kaggle
- Inspiración en las mejores prácticas de Data Engineering
- Comunidad de Python y Data Science

---

⭐ ¡No olvides dar una estrella al proyecto si te resulta útil!
