# Análisis de Datos de COVID-19

## Descripción
Este proyecto realiza un análisis exploratorio y visualización de datos relacionados con el COVID-19 utilizando el dataset `owid-covid-latest.csv` de Our World in Data. El objetivo es examinar tendencias globales, identificar los países con mayor número de muertes, explorar la relación entre vacunación y mortalidad, y visualizar patrones mensuales de casos por país.

## Requisitos
Para ejecutar este proyecto, necesitas las siguientes bibliotecas de Python:
- `pandas`
- `matplotlib`
- `numpy`
- `seaborn`
- `pathlib`

Puedes instalarlas con:
```bash
pip install pandas matplotlib numpy seaborn
```

## Estructura del Proyecto
- **Datos**: El archivo `owid-covid-latest.csv` debe estar ubicado en el directorio `../Data/` relativo al notebook.
- **Notebook**: El análisis está contenido en un Jupyter Notebook con las siguientes secciones:
  1. Importación de librerías y carga de datos.
  2. Exploración inicial de los datos.
  3. Limpieza de datos (manejo de valores nulos).
  4. Visualizaciones:
     - Tendencias globales de casos y muertes diarias.
     - Países con mayor número de muertes.
     - Relación entre vacunación y mortalidad por continente.
     - Mapa de calor de casos mensuales por país.

## Instrucciones de Uso
1. Asegúrate de que el archivo `owid-covid-latest.csv` esté en el directorio `../Data/`. Si no lo tienes, descárgalo desde [Our World in Data](https://ourworldindata.org/covid-deaths).
2. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook
   ```
3. Ejecuta las celdas en orden para reproducir el análisis y las visualizaciones.

## Notas Importantes
- El dataset `owid-covid-latest.csv` es un snapshot de datos recientes y puede no ser ideal para análisis temporales completos. Para tendencias históricas, considera usar `owid-covid-data.csv`.
- Los valores NaN en `people_fully_vaccinated_per_hundred` se rellenan con 0, lo que podría afectar las interpretaciones.

## Resultados Principales
- **Tendencias Globales**: Gráfico de líneas mostrando casos y muertes diarias a nivel mundial.
- **Países Más Afectados**: Barra con los 10 países con mayor número de muertes totales.
- **Vacunación vs Mortalidad**: Dispersión que explora la relación entre personas vacunadas y muertes por millón, segmentada por continente.
- **Patrones Mensuales**: Heatmap de casos nuevos por país y mes.

## Mejoras Futuras
- Usar un dataset histórico para análisis temporales más robustos.
- Agregar análisis estadísticos (correlaciones, regresiones).
- Incluir conclusiones escritas basadas en las visualizaciones.

## Autor
[Tu Nombre] - Creado el 24 de abril de 2025.