# Web Traffic Simulation & Performance Analytics

## Objetivo  
El objetivo principal de este proyecto es **correlacionar las métricas de rendimiento web** con las **palabras clave** específicas en los títulos de contenido. El análisis busca identificar la **estrategia temática** y las **tácticas lingüísticas** que generan consistentemente el mayor compromiso (engagement) de los usuarios (alto Tiempo en Página y baja Tasa de Rebote).

EL proyecto aborda la necesidad crítica de los equipos de Marketing: pasar de medir la **cantidad** (Visitas) a medir la **calidad** y la **interacción profunda** del lector. El análisis proporciona una visión estratégica para guiar la inversión en contenido hacia aquellos temas que tienen una fuerte correlación estadística con un bajo porcentaje de abandono y una lectura prolongada

## Sobre el Dataset  
El análisis se basa en un dataset creado y simulado artificialmente, una decisión metodológica tomada debido a que el acceso directo a las APIs de analítica web requiere credenciales privadas. Esta simulación permitió aislar la fase de análisis y NLP del desafío de la autenticación, garantizando que la lógica del proyecto fuera el foco central. El dataset fue construido utilizando librerías en Python, empleando una semilla aleatoria para asegurar que, aunque los valores parecen aleatorios, todos los resultados sean completamente reproducibles para cualquiera que desee replicar el análisis. El DataFrame resultante representa fielmente las métricas críticas que un Analista de Marketing obtendría en la vida real, como el título del contenido, el tiempo en página, la tasa de rebote y las visitas.

## Guía de uso 
1. **Para el Análisis y Código del Proyecto**: Puedes ver el [script](notebooks/002.ipynb) en línea, o si prefieres descargar el Notebook para ejecutarlo localmente en tu servidor de Jupyter.
2. **Para la Configuración y Dependencias**: Dale un vistazo a los [requerimientos](requirements.txt).

## Conclusiones  
Basado en este análisis de datos completo, tu informe de Analista Junior al equipo de Marketing debería ser:
1. **Priorizar Contenido Técnico y de Guía**: Duplicar los esfuerzos en la creación de contenido de formato **"Guía Completa"** y temas de **integración de datos** (API, Python, Pandas), ya que esto está altamente correlacionado con el **mayor Tiempo en Página**.
2. **Optimizar para Temas Específicos**: Asegurar que los títulos contengan las palabras clave ganadoras como "**API**", "**Google Analytics**" y "**Python**" o "**Redes Sociales**" y "**Errores Comunes**".
3. **Depuración de Stopwords**: Aunque la palabra "**cómo**" apareció más (11 veces), esto es probablemente una stopword residual y no una palabra clave de valor. Se recomienda añadir "cómo" a la lista de stopwords y volver a correr el análisis para obtener una mayor precisión.
