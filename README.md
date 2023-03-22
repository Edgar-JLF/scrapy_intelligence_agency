
# Intelligence Agency
Intelligence Agency es un proyecto que tiene como objetivo recolectar y presentar los documentos y archivos desclasificados de las agencias de inteligencia más poderosas del mundo, como la CIA. Para llevar a cabo esta tarea se utiliza la técnica de Web Scraping profesional. El proyecto se desarrolla con un backend de datos hecho en Scrapy y se despliega en Scrapy Cloud.

## Funcionamiento
El spider comienza su ejecución en la URL principal https://www.cia.gov/readingroom/historical-collections. Luego, utiliza expresiones XPath para buscar enlaces a los documentos desclasificados en la página actual y seguir estos enlaces para obtener la información del título y el cuerpo del documento. Finalmente, la información se almacena en un archivo JSON.

## Despliegue
El proyecto se despliega en Scrapy Cloud, una plataforma de rascado web en la nube, que permite a los usuarios programar, ejecutar y supervisar rascadores web y programar el acceso a los datos a través de una API RESTful.

## Créditos
Este scraper fue creado por Edgar Javier para fines educativos. Este proyecto es de código abierto y puede ser utilizado y modificado libremente.


