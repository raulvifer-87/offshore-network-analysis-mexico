# offshore-network-analysis-mexico
Análisis reproducible de coincidencias y redes offshore con datos públicos, entity matching y análisis de redes.
# Offshore Network Analysis — México

Proyecto de análisis de datos orientado a identificar coincidencias potenciales y patrones de red entre listas controladas de personas/empresas de interés y la Offshore Leaks Database publicada por ICIJ.

## Objetivo

Construir un flujo reproducible para limpiar nombres, detectar coincidencias potenciales, clasificar niveles de confianza y analizar redes entre personas, entidades offshore, intermediarios, direcciones y jurisdicciones.

## Alcance inicial

La primera versión del proyecto no busca hacer acusaciones ni inferencias legales. El objetivo es construir una metodología de análisis de datos para:

* normalizar nombres de personas y empresas,
* realizar coincidencias exactas y aproximadas,
* clasificar coincidencias por nivel de confianza,
* construir redes entre nodos y relaciones,
* documentar hallazgos de forma ética y verificable.

## Método

El proyecto utiliza un enfoque de:

* limpieza y normalización de datos,
* entity resolution,
* fuzzy matching,
* análisis de redes,
* documentación metodológica reproducible.

## Fuentes de datos previstas

* Offshore Leaks Database de ICIJ.
* Lista controlada de agentes, empresas o entidades de interés.
* Fuentes públicas complementarias para validación manual.

## Advertencia metodológica

La aparición de una persona o entidad en una base de filtraciones offshore no implica por sí misma ilegalidad ni conducta indebida. Este proyecto identifica coincidencias potenciales y patrones relacionales que requieren validación manual con fuentes adicionales.

## Stack técnico

* Python
* pandas
* rapidfuzz
* networkx
* matplotlib
* Jupyter Notebook
* GitHub

## Estructura del repositorio

```text
offshore-network-analysis-mexico/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ notebooks/
│  ├─ 01_data_sources.ipynb
│  ├─ 02_clean_names.ipynb
│  ├─ 03_entity_matching.ipynb
│  └─ 04_network_analysis.ipynb
├─ reports/
│  ├─ methodology.md
│  ├─ matching_protocol.md
│  └─ ethics_disclaimer.md
├─ data/
│  ├─ raw/
│  ├─ private/
│  ├─ sample/
│  └─ processed/
└─ outputs/
   ├─ matches/
   └─ networks/
```

## Estado del proyecto

En desarrollo.
