# Análisis de Ventas de Videojuegos

## Descripción del proyecto

Este proyecto analiza datos históricos de ventas de videojuegos con el objetivo de identificar patrones relacionados con el éxito comercial de distintos títulos, plataformas y géneros.

El análisis incluye exploración de datos, limpieza, visualizaciones y pruebas estadísticas para detectar tendencias del mercado y generar insights orientados a la toma de decisiones.

## Funcionalidades del análisis

- **Limpieza y preparación de datos**
  - Normalización de columnas
  - Conversión de tipos de datos
  - Tratamiento de valores ausentes y duplicados

- **Análisis exploratorio (EDA)**
  - Juegos lanzados por año
  - Plataformas más exitosas
  - Géneros con mayores ventas
  - Comparación de ventas por región

- **Análisis estadístico**
  - Correlación entre puntuaciones y ventas
  - Pruebas de hipótesis
  - Comparaciones entre mercados

- **Visualizaciones**
  - Histogramas
  - Boxplots
  - Diagramas de dispersión
  - Gráficos de barras

## Tecnologías utilizadas

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) – análisis y manipulación de datos
- [NumPy](https://numpy.org/) – operaciones numéricas
- [Matplotlib](https://matplotlib.org/) – visualización de datos
- [SciPy](https://scipy.org/) – pruebas estadísticas
- [Jupyter Notebook](https://jupyter.org/) – entorno de desarrollo

Cómo ejecutar el proyecto localmente

Clona el repositorio:

git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>

2. Crea y activa un entorno virtual:
   ```bash
   python -m venv env
   source env/bin/activate   # macOS/Linux
   env\Scripts\activate      # Windows

Instala las dependencias:

pip install pandas numpy matplotlib scipy jupyter

Ejecuta Jupyter Notebook:

jupyter notebook
Abre el archivo .ipynb
Principales conclusiones
Los géneros Action y Sports lideran las ventas globales.
Las preferencias de los usuarios cambian según la región.
Algunas plataformas presentan ciclos de vida claramente definidos.
Las puntuaciones de críticos muestran relación con el rendimiento comercial de ciertos videojuegos.
