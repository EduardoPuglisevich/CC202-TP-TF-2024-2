# CC202-TP-TF-2024-2
<h3>Objetivos</h3>
<hr/>

- Optimizar la búsqueda de referencias científicas: Explorar cómo el análisis de redes de artículos científicos puede mejorar la precisión y eficiencia al identificar relaciones de similitud de contenido entre artículos.

- Mejorar la identificación de similitudes mediante NLP: Evaluar cómo las técnicas de procesamiento de lenguaje natural pueden ser aplicadas para mejorar la identificación de similitudes entre artículos científicos.

- Determinar algoritmos adecuados para redes científicas: Identificar y analizar cuáles son los algoritmos más efectivos en redes complejas para comprender la estructura y dinámica de redes de artículos científicos de manera integral.

<h3>Descripción del dataset</h3>
<hr/>
Los datos provienen de Scopus, una de las bases de datos de literatura científica más reconocidas a nivel mundial. Se realizó un proceso de exportación, donde se extrajo 20 000 artículos científicos, ejecutado el 20 de septiembre de 2024. Este enfoque permite acceder de forma previa a una amplia gama de información relevante para el estudio de la conectividad y las relaciones entre los artículos. 

La recolección de este conjunto de datos se realizó para analizar las dinámicas de la investigación científica a través de la red de artículos. Scopus proporciona una vasta cantidad de información sobre publicaciones académicas, incluyendo metadatos y variedad de métricas que pueden ser extraídos gracias a su API Elsevier. Al utilizar esta fuente de datos y parámetros seleccionados, se busca construir una red que cumpla con el objetivo del proyecto. En la siguiente Tabla 1 se describen las características recogidas de cada artículo. 

<h3>Conclusiones</h3>
<hr/>

- Importancia del algoritmo de NLP (TF-IDF): Este permitió construir la red de artículos con precisión, identificando patrones significativos en la organización temática del conjunto de datos.

- Segmentación en comunidades: El algoritmo de Leiden destacó por su alta modularidad y su capacidad para identificar grupos cohesivos con temas relacionados.

- Métricas de centralidad: PageRank y Closeness Centrality identificaron artículos clave con mayor influencia y accesibilidad dentro de sus comunidades.

- Recomendaciones futuras: Incorporar modelos avanzados como Word2Vec o SBERT para mejorar la precisión en similitudes, aplicar análisis dinámicos de redes para estudiar la evolución de temas, y utilizar herramientas de visualización interactivas para ampliar el impacto de los resultados.

<!-- TEAM MEMBERS -->
## Integrantes

- Samuel Cano (U202116508@upc.edu.pe) 🐱
- Eduardo Puglisevich (U20201e850@upc.edu.pe)
- Nicolás Guerrero (U202115535@upc.edu.pe)
- Fernando Paredes (U202122837@upc.edu.pe)
