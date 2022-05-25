
# Herramientas de control de calidad para nombres taxonómicos

## Catalogue of Life
El [Catalogue of Life (COL)](https://www.catalogueoflife.org/) integra datos taxonómicos de todos los grupos de organismos para brindar acceso libre a una lista de taxones que incluye las especies actualmente aceptadas, sinónimos, nombre comunes y otros datos. Los datos son integrados a partir de múltiples trabajos taxonómicos realizados por taxónomos alrededor del mundo.  

COL brinda herramientas para que los taxónomos y otras partes interesadas puedan publicar y revisar listas de taxones, una interfaz para consultar la base de datos en internet, un [API](https://www.catalogueoflife.org/about/colusage#col-api) para integrar los servicios a otras herramientas y una versión anual de la lista de taxones que puede ser bajada del sitio, además de [actualizaciones mensuales](https://www.catalogueoflife.org/data/download).  

## GBIF Backbone Taxonomy
El [GBIF Backbone Taxonomy](http://rs.gbif.org/datasets/backbone/) constituye el núcleo de los datos taxonómicos que permite a GBIF integrar información basada en nombres obtenidos de diferentes recursos de datos, como datos de presencia, páginas de especies, nombres taxonómicos, o datos de fuentes externas como EOL, Genbank o la Unión Internacional para la Conservación de la Naturaleza (IUCN - International Union for Conservation of Nature). El Backbone permite realizar operaciones de búsqueda y proporciona medios para integrar los nombres taxonómicos de múltiples fuentes. 

La base de datos se actualiza periódicamente a través de un proceso automatizado en el que el COL actúa como punto de partida proporcionando también la clasificación superior completa por encima de las familias. Los nombres científicos adicionales que solo se encuentran en otros conjuntos de datos taxonómicos y nomenclaturales autorizados se combinan en el árbol, ampliando así el catálogo original y ampliando la cobertura de nombres disponibles en la base de datos. Los nombres disponibles actualmente provienen de más de 100 bases de datos.

La base de datos está disponible para descargarse y existe en un [API](https://www.gbif.org/es/developer/species) para para integrar los servicios a otras herramientas.

## Global Names Resolver
El [Global Name Resolver](https://resolver.globalnames.org/) verifica listas de taxones contra fuentes conocidas. La aplicación analiza los nombres de entrada, realiza búsquedas de coincidencias exactas o aproximadas según sea necesario y muestra una puntuación de confianza para cada coincidencia junto con su identificador. 

A la fecha el sistema utiliza 195 fuentes de nombre taxonómicos incluidas COL y GBIF.   El sistema tiene disponible una interfaz web y un [API] (https://resolver.globalnames.org/api) para integrar los servicios a otras herramientas. La aplicación fue desarrollada por Dmitry Mozzherin y David Shorthouse en el 2012-2013, el [código de la herramienta](https://github.com/GlobalNamesArchitecture/gni) está disponible en GitHub pero no está disponible la licencia de uso.
