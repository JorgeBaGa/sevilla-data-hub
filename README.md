# Sevilla Data Hub

Repositorio de análisis de datos municipales de la provincia de Sevilla.

El objetivo de este proyecto es construir una base de trabajo con datos públicos municipales y desarrollar distintos análisis económicos, demográficos y territoriales sobre los municipios sevillanos.

El proyecto parte de datos públicos procedentes principalmente del Banco de Datos Estadísticos de Andalucía (BADEA), del Instituto de Estadística y Cartografía de Andalucía, y podrá incorporar otras fuentes públicas cuando sea necesario.

## Objetivo

El objetivo principal es analizar la realidad municipal de la provincia de Sevilla mediante datos abiertos.

Este repositorio servirá como espacio de trabajo para distintos análisis, entre ellos:

- evolución de la población
- estructura demográfica
- envejecimiento municipal
- renta y nivel económico
- actividad económica
- mercado laboral
- impuestos municipales
- deuda pública local
- comparación entre municipios
- clasificación de municipios mediante técnicas de clustering

Uno de los primeros análisis será un clustering jerárquico de todos los municipios de Sevilla. Este análisis permitirá clasificar los municipios en grupos con características socioeconómicas similares.

A partir de esa clasificación se estudiará el caso de Morón de la Frontera, comparándolo con los municipios que pertenezcan a su mismo grupo y añadiendo, cuando sea necesario, otros municipios cercanos para enriquecer la comparación territorial.

## Estructura del repositorio

```text
sevilla-data-hub/
│
├── raw/
│   └── sevilla/
│       └── badea_datos_sevilla/
│
├── README.md
└── notebooks de análisis
