# titanicCleaningData

Limpieza de un dataset de Titanoc

## Instalación de dependencias
Para realizar este proyecto se ha utilizado R 3.6+. Rcomander.

## Descripción de los ficheros
| Nombre del Fichero | Decripción |
|--------------------|------------|
| orphanetCrawler <ul><li>&#95;&#95;pycache&#95;&#95;</li><li>spiders</li><li>&#95;&#95;init&#95;&#95;.py</li><li>exporters.py</li><li>items.py</li><li>middlewares.py</li><li>pipelines.py</li><li>settings.py</li></ul> | Carpeta con el código del crawler <ul><li>Carpeta con la cache autogenerada por scrappy</li><li>Carpeta con la lógica de navegación y extracción</li><li>Fichero autogenerado por Scrapy</li><li>Fichero con lógica de exportación (separadores) </li><li>Fichero con la estructura del objeto a recolectar incluyendo los campos (Abstracción de la ER)</li><li>Fichero con la configuración generada por scrapy</li><li>Definición del proceso de iteración de los elementos, generado por scrapy</li><li>Configuraciones importantes como la de seguir o no las reglas del fichero robots.txt</li></ul> |
| README.md	| Fichero que contiene información del proyecto y de los ficheros|
| aditional_information.PNG | Captura de pantalla del recuadro de información adicional de la ER|
| alphabetical_list.PNG	| Captura de pantalla del listado alfabetico de las ER|
| disease.PNG	| Captura de pantalla de la ER |
| orphanCrawl.log | Fichero con los logs de la ejecución del crawler |
| rared_diseases_zebra.png | Imagen representativa del dataset |
| report.csv | Dataset generado que contiene todas las ER con su información recolectadas de www.orpha.net|
| scrapy.cfg | Fichero de configuración de scrapy|
| PRACTICA1.pdf | Fichero PDF con el informe de la práctica|
