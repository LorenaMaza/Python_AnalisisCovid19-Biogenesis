# 📊 Análisis de COVID-19 y Estrategias de Vacunación en América Latina  

## 📌 Descripción del Proyecto  
Este proyecto forma parte del **Proyecto Individual del Módulo 4** del Bootcamp de Data Science en Henry.  

El objetivo fue analizar la evolución del COVID-19 en América Latina y evaluar la relación entre los casos confirmados, la tasa de letalidad, la vacunación y la disponibilidad de personal de salud.  

El análisis permitió identificar qué países presentan condiciones más favorables para la **expansión de laboratorios farmacéuticos**, considerando tanto los indicadores sanitarios como la infraestructura médica.  

---

## ⚙️ Tecnologías Utilizadas  

### 🔹 Python (Análisis Exploratorio de Datos - EDA)  
- **pandas** → manipulación y limpieza de datos.  
- **numpy** → operaciones numéricas y vectorizadas.  
- **matplotlib** → visualizaciones base.  
- **seaborn** → gráficos avanzados y mapas de calor.  

### 🔹 Power BI  
- Modelado de datos.  
- Creación de medidas en **DAX**.  
- Construcción de dashboards interactivos.  

### 🔹 DAX (KPIs en Power BI)  
- Cálculo de incidencia, tasa de letalidad y cobertura de vacunación.  
- Normalización de indicadores por población.  

---

## 🧮 KPIs Calculados  
- **Incidencia de casos confirmados (por 100k hab.)**  
- **Casos fallecidos (por 100k hab.)**  
- **% de población vacunada**  
- **Vacunas administradas por habitante**  
- **Tasa de letalidad (%)**  
- **Personal de salud por cada 1000 habitantes** (médicos + enfermeros)  

---

## 🔍 Análisis Exploratorio en Python  

Durante la etapa de EDA se realizaron los siguientes pasos:  

- **Limpieza de datos**: imputación de valores faltantes (media para variables ambientales, forward-fill para acumulados).  
- **Análisis temporal**: evolución de casos confirmados, fallecidos y vacunación por semana y mes.  
- **Mapas de correlación**: relación entre variables climáticas, casos y mortalidad.  
- **Comparación entre países**:  
  - Tasa de letalidad.  
  - Incidencia acumulada.  
  - Estrategias de vacunación ajustadas por población.  
- **Visualizaciones**:  
  - Series temporales.  
  - Histogramas y gráficos de densidad (ej. temperatura y humedad).  
  - Gráficos de barras comparativos.  
  - Heatmaps de correlación.  

---

## 📊 Dashboard en Power BI  

El tablero se organizó en **3 secciones principales**:  

1. **Globales** → Evolución de casos, letalidad y población vacunada.  
2. **Personal de Salud** → Comparación de médicos y enfermeros disponibles en cada país.  
3. **Vacunación** → Cobertura y dosis administradas ajustadas por población.  

Incluye segmentaciones dinámicas por:  
- Año  
- Mes  
- País  

---

## 🔎 Hallazgos Principales  
- **Chile y Argentina** presentan la **mayor cobertura de vacunación** relativa a su población.  
- **Brasil y México** muestran alta incidencia de casos, lo que implica un mercado relevante pero con mayores desafíos sanitarios.  
- **Chile destaca en personal de salud por habitante**, lo que lo posiciona favorablemente en términos de infraestructura médica.  
- **La tasa de letalidad promedio en la región se mantiene cercana al 2%**, con ligeras variaciones por país.  

---

## 🚀 Conclusión  
A partir del análisis, se recomienda priorizar la expansión en países con **alta cobertura de vacunación** y **buena infraestructura sanitaria** (como **Chile y Argentina**), sin descuidar mercados grandes como **Brasil y México**, que aunque presentan mayores riesgos, ofrecen un potencial de impacto considerable.  

---

## 📂 Estructura del Repositorio  
- 📁 data → dataset original y limpio.
- 📁 notebooks → notebooks de Python con el análisis exploratorio.
- 📁 dashboard → archivo .pbix del tablero en Power BI.
- 📄 README.md → este documento.

---

✒️ **Autor**: Lorena Maza  
📅 **Año**: 2025  

