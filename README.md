# directoryindexer
Aplicación que permite indexar directorios abiertos de descarga directa para poder obtener aquellos que contengan un contenido específico.
mvn -s settings.xml clean compile assembly:single
java -jar target/directoryindexer-0.0.1-jar-with-dependencies.jar exporter.properties
scrapy crawl directories
python manage.py runserver
