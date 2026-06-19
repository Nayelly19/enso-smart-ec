# ENSO-SMART Ecuador

[![Astro 6](https://img.shields.io/badge/Astro-6-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Tailwind CSS 4](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-84cc16?style=for-the-badge)](./LICENSE)

**Sistema Inteligente de Predicción Climática y Riesgo de Inundaciones basado en IA**

ENSO-SMART Ecuador es una iniciativa de investigación aplicada para monitorear variables climáticas, analizar patrones ENSO y estimar riesgo de inundaciones en Ecuador mediante datos públicos, modelos predictivos e interfaces visuales.

**Sitio web:** [http://192.168.56.1:3000/](http://192.168.56.1:3000/)

## 🎯 Estado del Proyecto

**Fase 1 - MVP funcional y reproducible** 
El MVP se basa exclusivamente en fuentes públicas y abiertas (NOAA, CHIRPS, GPM IMERG, ERA5/Copernicus) para reducir dependencias y aumentar reproducibilidad científica.

## 🛠️ Stack Tecnológico

- **Frontend:** Astro 6, Tailwind CSS 4, MDX
- **Backend/IA:** Python, Pandas, Scikit-learn, XGBoost, NGBoost
- **Datos:** GeoPandas, xarray, netCDF4
- **Dashboard:** Streamlit
- **Base de datos:** PostgreSQL/PostGIS
- **Búsqueda:** Pagefind

## 🚀 Quick Start

```bash
-**npm install**
-**npm run dev**

## 📁 Estructura del Proyecto
.
|-- public/
|-- src/
|   |-- components/
|   |-- content/
|   |-- data/
|   |-- layouts/
|   `-- pages/
|-- astro.config.mjs
|-- package.json
|-- site.config.mjs
`-- tsconfig.json

## License

[MIT](./LICENSE)


