# DirectoryIndexer

### Welcome to the DirectoryIndexer!
Application that allows you to index open direct download directories in order to obtain those that contain specific content.

### Execution steps

- mvn -s settings.xml clean compile assembly:single
- java -jar target/directoryindexer-0.0.1-jar-with-dependencies.jar exporter.properties
- scrapy crawl directories
- python manage.py runserver
