# elasticsearch-workshop

Elasticsearch workshop to learn the basics of this search engine.

Used technologies
-----------------

```
- Docker for Mac
- Elasticsearch v6.5.4
- Flask v1.0.2
- Python v3.7.1
```

Docker setup
------------
This workshop will use an elasticsearch docker image. A manual installation of elasticsearch and server side stuffs will be not covered.

Documentation: 

https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html

For more information about installation and configuration:

https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html
https://www.elastic.co/guide/en/elasticsearch/reference/current/settings.html
https://www.elastic.co/guide/en/elasticsearch/reference/current/important-settings.html
https://www.elastic.co/guide/en/elasticsearch/reference/current/system-config.html

Running project
---------------

```
$ git clone git@github.com:sihades/elasticsearch-workshop.git
$ cd elasticsearch-workshop
$ docker-compose build
$ docker-compose up -d
```

##### Urls
- Elasticsearch: http://127.0.0.1:9200
- Web app: http://127.0.0.1:5000
