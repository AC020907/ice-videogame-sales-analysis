```markdown
# Análisis de Ventas de Videojuegos - Ice Store

📋 Descripción del Proyecto
Este proyecto analiza patrones de éxito en la industria de videojuegos utilizando datos históricos de ventas, reseñas y características de juegos hasta 2016. El objetivo es identificar proyectos prometedores y planificar campañas publicitarias efectivas para la tienda online Ice, proporcionando insights estratégicos para el año 2017.

🎯 Objetivos
Identificar patrones de éxito en videojuegos basados en datos históricos
Analizar tendencias temporales y ciclos de vida de plataformas
Segmentar mercados regionales (Norteamérica, Europa, Japón)
Evaluar correlaciones entre reseñas y ventas
Realizar pruebas estadísticas para validar hipótesis de mercado
Proporcionar recomendaciones estratégicas para campañas publicitarias
📊 Conjunto de Datos
Período de análisis: 1980-2016 (enfoque en 2013-2016)  
Volumen: 16,715 registros de videojuegos

Estructura de datos:
Variables principales:
- name: Nombre del videojuego
- platform: Plataforma de lanzamiento (PS4, Xbox One, PC, etc.)
- year_of_release: Año de lanzamiento
- genre: Género del juego (Action, Sports, RPG, etc.)
- na_sales, eu_sales, jp_sales, other_sales: Ventas por región (millones USD)
- critic_score: Puntuación de críticos (0-100)
- user_score: Puntuación de usuarios (0-10)
- rating: Clasificación ESRB (E, T, M, etc.)

🛠️ Tecnologías Utilizadas
Python 3.9+
Pandas: Manipulación y análisis de datos
NumPy: Cálculos numéricos y estadísticas
Matplotlib: Visualización de datos y gráficos
SciPy: Pruebas estadísticas (t-test)
Jupyter Notebook: Entorno de desarrollo
🔧 Metodología de Análisis
1. Preparación de Datos
Normalización: Conversión de nombres de columnas a minúsculas
Conversión de tipos: Estandarización de formatos numéricos y fechas
Tratamiento de valores ausentes: Manejo estratégico de datos faltantes
Cálculo de métricas: Creación de columna total_sales
2. Análisis Exploratorio
Tendencias temporales: Evolución de lanzamientos por año
Análisis de plataformas: Identificación de líderes de mercado
Distribución por géneros: Patrones de popularidad
Correlaciones: Relación entre reseñas y ventas
3. Segmentación Regional
Perfiles de usuario: Análisis por región (NA, EU, JP)
Preferencias de plataforma: Top 5 por mercado
Géneros populares: Diferencias culturales
Clasificaciones ESRB: Impacto por región
