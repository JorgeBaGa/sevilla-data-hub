# Análisis Socioeconómico de los Municipios de Sevilla

Análisis multivariante de los municipios de la provincia de Sevilla a partir de indicadores demográficos, económicos y territoriales del IECA (BADEA).

## Objetivo

Identificar grupos de municipios con perfiles socioeconómicos similares mediante Análisis de Componentes Principales (PCA) y Clustering. Este análisis sirve como base para estudios posteriores más específicos sobre Morón de la Frontera y su entorno.

## Estructura del proyecto

- `data/processed/` — Tabla final municipios × variables
- `notebooks/` — Cuadernos de trabajo (ETL y análisis)
- `src/` — Funciones reutilizables
- `reports/` — Informe final en Quarto
- `docs/` — HTML renderizado para GitHub Pages

## Datos

Los datos crudos están en el repositorio [sevilla-data-hub](https://github.com/JorgeBaGa/sevilla-data-hub). Para ejecutar este análisis es necesario clonarlo como carpeta hermana.

## Tecnologías

Python 3, pandas, scikit-learn, scipy, matplotlib, seaborn, Quarto.

## Autor

Jorge Bautista García