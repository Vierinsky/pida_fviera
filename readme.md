![alt text](_src/soyhenry_logo.png)

# Proyecto Individual: Análisis del Sector de Telecomunicaciones en Argentina

## Descripción
Este proyecto tiene como objetivo realizar un análisis integral del sector de telecomunicaciones en Argentina, enfocado en el acceso a internet. La empresa solicitante busca identificar oportunidades de crecimiento, optimizar la calidad de sus servicios y desarrollar soluciones personalizadas para sus clientes actuales y potenciales.

El análisis considera aspectos clave como:
- **Penetración del mercado:** Medida en accesos por cada 100 hogares.
- **Velocidad de conexión:** Promedios de Mbps por provincia.
- **Tecnología de conexión:** Uso de tecnologías como ADSL, Cablemodem, Fibra Óptica, Wireless y otras.

El resultado del proyecto incluye visualizaciones y un dashboard que facilita la interpretación de los hallazgos. Además, las recomendaciones están orientadas a identificar provincias con potencial de inversión en infraestructura y mejora del servicio.

---

## Estructura del Proyecto

### Archivos Principales
- `eda_etl_internet.ipynb`: Notebook principal que contiene:
  - Exploración de datos (EDA).
  - Transformaciones de datos (ETL).
  - Generación de métricas e indicadores clave (KPI).
- `Datasets/`: Carpeta que contiene los datasets utilizados en el proyecto.
  - Ejemplo: `penetracion_poblacion.csv`, `tecnologia_accesos.csv`.
- `PIDA_fviera.pbix`: Archivo de Power BI con las visualizaciones y el dashboard final.

### Resultados Clave
1. **Penetración del mercado:**
   - Provincias con alta y baja penetración por cada 100 hogares.
   - Identificación de oportunidades para aumentar la conectividad, destacando Mendoza, Santiago del Estero, Chaco, Corrientes y Misiones como regiones con potencial.

2. **Velocidad de conexión:**
   - Promedio de Mbps por provincia.
   - Análisis de provincias con velocidades bajas, como Mendoza, Santa Fe y Santiago del Estero, y su impacto en la calidad del servicio.

3. **Tecnología de conexión:**
   - Predominio de tecnologías como ADSL y Cablemodem en la mayoría de las provincias.
   - Crecimiento gradual de Fibra Óptica y Wireless, aunque estas no superan a las tecnologías más antiguas.

---

## Requisitos
Para reproducir el análisis, necesitarás:

### Herramientas y Entornos
- Python 3.8 o superior.
- Librerías principales:
  - `pandas`: Manejo y transformación de datos.
  - `numpy`: Cálculos numéricos.
  - `matplotlib` y `seaborn`: Visualizaciones.
- Power BI: Para crear y visualizar el dashboard.

### Instalación de Dependencias
Ejecuta el siguiente comando para instalar las librerías necesarias:
```bash
pip install -r requirements.txt
```

---

## Uso del Proyecto
1. **Exploración y Transformación de Datos**:
   - Abre el notebook `eda_etl_internet.ipynb`.
   - Sigue las celdas para comprender el proceso de limpieza, transformación y cálculo de métricas.

2. **Análisis Visual**:
   - Abre el archivo `PIDA_fviera.pbix` en Power BI.
   - Explora las visualizaciones del dashboard para identificar tendencias y oportunidades.

3. **Métricas Generadas**:
   - **Penetración del Mercado:** Accesos por cada 100 hogares. Se incluye un KPI que evalúa el crecimiento trimestral esperado del 2% en cada provincia.
   - **Velocidad Promedio:** Mbps por provincia, con un KPI que mide la mejora trimestral del 2%.
   - **Predominio Tecnológico:** Accesos por tecnología. Se incluye un KPI que evalúa el crecimiento trimestral por tecnología esperado del 2%

---

## Insights y Recomendaciones
- **Provincias con baja penetración:** Mendoza, Santiago del Estero, Chaco, Corrientes y Misiones representan oportunidades para ampliar la infraestructura de conexión.
- **Velocidades bajas:** Provincias como Santa Fe, Mendoza y Santiago del Estero necesitan mejoras en infraestructura para competir con provincias mejor desarrolladas.
- **Tecnologías predominantes:** Aunque ADSL y Cablemodem dominan, invertir en Fibra Óptica y Wireless puede ser clave para el futuro.

---

## Presentación y Contexto Adicional
Durante la presentación del proyecto, se destacará:
- La importancia de las tendencias al alza tanto en penetración como en velocidad, lo que refleja un mercado en constante crecimiento.
- El uso de KPIs para medir el rendimiento en cada provincia.
- Recomendaciones claras basadas en el análisis de datos: enfoque en mercados subexplotados y mejora de infraestructuras clave.