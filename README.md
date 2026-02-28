# Evolución y Transición del Empleo Sectorial en Colombia (1958-2018) 🇨🇴📊

## Descripción del Proyecto
Este proyecto realiza un proceso completo de Extracción, Transformación y Carga (ETL) y un Análisis Exploratorio de Datos (EDA) sobre las series históricas de ocupación laboral en Colombia, utilizando datos oficiales del DANE (Departamento Administrativo Nacional de Estadística). 

El objetivo principal es evidenciar, mediante análisis cuantitativo, la transición estructural de la fuerza laboral colombiana, pasando de una economía predominantemente rural a una economía enfocada en el sector terciario (servicios y comercio).

## Tecnologías Utilizadas
* **Python** (Lógica principal)
* **Pandas** (Limpieza, transformación de datos y manejo de valores nulos)
* **Matplotlib** (Visualización de datos y generación de paneles múltiples)
* **Jupyter Notebook** (Entorno de desarrollo analítico)

## Retos Técnicos Resueltos
1. **Limpieza de "Dirty Data":** Eliminación de metadatos, notas al pie y columnas residuales presentes en los formatos gubernamentales.
2. **Manejo de Datos Faltantes (NaN):** Identificación y justificación analítica de vacíos en las variables de subempleo debido a cambios en la recolección de encuestas.
3. **Empalme Metodológico (Solapamiento):** Análisis crítico del periodo 2002-2011, donde convergen la metodología histórica y la moderna (GEIH), resolviendo la discrepancia mediante sub-gráficos comparativos en lugar de uniones a ciegas.

## Insights Principales (Hallazgos)
* **Declive Agrícola:** La participación de la agricultura cayó drásticamente desde un ~54% en 1958 hasta menos del 16% en 2018.
* **Dominancia del Sector Terciario:** Los servicios se han consolidado como el motor del empleo moderno, absorbiendo consistentemente más del 34% de la fuerza laboral en las últimas dos décadas.
* **Estancamiento Industrial:** La ocupación en la industria manufacturera ha mantenido un comportamiento plano, oscilando entre el 11% y el 13%, indicando una falta de industrialización masiva en el empleo.

## Cómo explorar este proyecto
El código completo y las visualizaciones están documentados paso a paso en el cuaderno principal:
[Ver el Cuaderno de Análisis (Jupyter Notebook)](https://github.com/Felipe-CG-ING/analisis-empleo-colombia/blob/main/analisis_empleo_colombia.ipynb)
