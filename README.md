## Elasticsearch 

Elasticsearch is used for search, analyze, and store data. Elasticsearch provide JSON-based search and analytics engine designed for horizontal scalability, maximum reliability, and easy management.
 
 
 ### Installation using .zip package

```markdown

  wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.4.0.zip
  sha1sum elasticsearch-5.4.0.zip 
  unzip elasticsearch-5.4.0.zip
  cd elasticsearch-5.4.0/ 

   # Elasticsearch start and stop using the service command:
    ##Note: start > 
      $ ./bin/elasticsearch
    ##Note: stop > pressing Ctrl-C
    
```

### Installation using .deb package

```markdown

  wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.4.0.deb
  sha1sum elasticsearch-5.4.0.deb 
  sudo dpkg -i elasticsearch-5.4.0.deb

 # Elasticsearch start and stop using the service command:

  sudo -i service elasticsearch start
  sudo -i service elasticsearch stop
  
```
### Now Check on browser at http://localhost:9200
### Note : For more help https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html

## Kibana 

Kibana is an open source, Used for browser-based analytics and search on Elasticsearch.Kibana gives shape to your data and user interface (UI) for configuring and managing the Elastic Stack.


### Installation using .zip package

```markdown

  # Note: Change Linux 64bit package kibana-5.4.0-linux-x86_64.tar.gz or Linux 32bit package kibana-5.4.0-linux-x86.tar.gz
  
   wget https://artifacts.elastic.co/downloads/kibana/kibana-5.4.0-linux-x86_64.tar.gz  
   sha1sum kibana-5.4.0-linux-x86_64.tar.gz 
   tar -xzf kibana-5.4.0-linux-x86_64.tar.gz
   cd kibana/ 

   # Kibana start and stop using the service command:
    ##Note: start > 
      $ ./bin/kibana
    ##Note: stop > pressing Ctrl-C
    
```

### Installation using .deb package

```markdown

  # Note: Change Linux 64bit package kibana-5.4.0-amd64.deb or Linux 32bit package kibana-5.4.0-i386.deb

  wget https://artifacts.elastic.co/downloads/kibana/kibana-5.4.0-amd64.deb
  sha1sum kibana-5.4.0-amd64.deb 
  sudo dpkg -i kibana-5.4.0-amd64.deb

 # Kibana start and stop using the service command:

  sudo -i service kibana start
  sudo -i service kibana stop
  
```
### Now Check on browser at http://localhost:5601
### Note : For more help https://www.elastic.co/guide/en/kibana/current/install.html 

## X-Pack 

X-Pack is a plugin for Both Elasticsearch and Kibana. X-Pack is a combination of 6 different powerful features 
+ Security
+ Alerting (via Watcher)
+ Monitoring (formerly Marvel)
+ Reporting
+ Graph
+ Machine Learning (Beta)

```markdown

  # Installation in Elastic
  ## Note default Username:elastic and Password:changeme
  
  1 Install X-Pack into Elasticsearch
    bin/elasticsearch-plugin install x-pack

  2 Start Elasticsearch
    bin/elasticsearch

 # Installation in Kibana
 ## Note default Username:kibana and Password:changeme
  
  1 Install X-Pack into Kibana
    bin/kibana-plugin install x-pack

  2 Start Kibana
    bin/kibana

```

## Logstash 

Logstash is an open source,data processing pipeline.Logstash supports a variety of input and output modules, all at the same time.Logstash uses multiple input modules like Beat,Syslog,File etc. and also uses output modules likes Elasticsearch, MongoDB and File etc.Logstash also filters and parse them to converge on a common format for easier analysis and business value. 


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
