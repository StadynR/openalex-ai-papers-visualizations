# Análisis Visual de Tendencias en Publicaciones de IA

Este proyecto presenta un análisis exhaustivo y visual de la evolución académica de la Inteligencia Artificial (IA) utilizando datos de la plataforma **OpenAlex**. A través de una serie de visualizaciones interactivas, exploramos el crecimiento del campo, la evolución de sus temas clave, la distribución geográfica de la investigación y el impacto de la colaboración internacional y el acceso abierto.

## 🚀 Visualizaciones en Vivo

Para una experiencia interactiva completa (treemaps navegables y tooltips detallados), visita la versión web del proyecto:

👉 **[https://stadynr.github.io/openalex-ai-papers-visualizations/](https://stadynr.github.io/openalex-ai-papers-visualizations/)**

---

## 📊 Preguntas de Investigación

El análisis está estructurado en 7 preguntas clave:

1.  **Tendencias Temporales:** ¿Cómo ha crecido el volumen de publicaciones desde 1950 hasta la actualidad?
2.  **Temas Emergentes:** ¿Qué áreas de investigación han experimentado el crecimiento más explosivo (XAI, Robustez, LLMs)?
3.  **Popularidad Temática:** ¿Cuáles son los pilares técnicos de la IA moderna?
4.  **Distribución Geográfica:** ¿Cómo se reparte la producción científica entre bloques globales (China, EE. UU., India, Europa)?
5.  **Volumen vs. Impacto:** ¿Existe una correlación entre cuántos papers se publican y cuántas citas reciben?
6.  **Colaboración Internacional:** ¿Publicar con autores de otros países realmente aumenta el impacto de una investigación?
7.  **Impacto del Open Access:** ¿El Acceso Abierto genera una ventaja real en citas o es un efecto de la "calidad" del tema?

## 🛠️ Tecnologías Utilizadas

-   **[Quarto](https://quarto.org/):** Sistema de publicación técnico-científica para la creación del documento narrativo.
-   **Python:** Procesamiento de datos y lógica de análisis.
-   **[Altair](https://altair-viz.github.io/):** Utilizado para la mayoría de gráficos estadísticos (barras, líneas, áreas).
-   **[Plotly](https://plotly.com/python/):** Utilizado para visualizaciones complejas e interactivas como el mapa coroplético y el treemap jerárquico.
-   **Pandas:** Manipulación y limpieza de los datasets de OpenAlex.

## 📖 Estructura del Repositorio

-   `visualizations.qmd`: Documento fuente principal que contiene la narrativa y el código de las visualizaciones.
-   `_quarto.yml`: Configuración del proyecto Quarto.
-   `ai_topic_year_counts_clean.csv`: Datos limpios por tema y año.
-   `ai_geo_year_counts.csv`: Datos agregados por geografía.
-   `ai_papers_sample.csv`: Muestra de papers para análisis de citas e impacto.
-   `docs/`: Contiene el sitio estático generado para GitHub Pages.

---
*Proyecto realizado como parte del curso de Visualización de Datos.*
