Download :

https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.5.2-windows-x86_64.zip
https://artifacts.elastic.co/downloads/kibana/kibana-7.5.2-windows-x86_64.zip
https://artifacts.elastic.co/downloads/logstash/logstash-7.5.2.zip

Configure elastic search first \
after kibana \
after logstash \

Edit location for sincedb_path
You can run logstash for multiple configurations.
If is not working you can use this link to configure log pattens
https://www.elastic.co/guide/en/logstash/7.5/plugins-filters-grok.html

Run elastic search
``elasticsearch.bat``

Run kibana
``kibana.bat``

Run LogStash
``.\logstash.bat -f E:\path\to\logstash\logstash-7.5.2\config\acccess-log.conf``


user slash in you config for logstash not backslash

Other info
https://qbox.io/blog/elasticsearch-logstash-kibana-apache-logs

search or define a pattern if you what customization

