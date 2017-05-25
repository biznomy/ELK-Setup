## Elasticsearch 

Elasticsearch is used for search, analyze, and store data. Elasticsearch provide JSON-based search and analytics engine designed for horizontal scalability, maximum reliability, and easy management.


 ### Installation using .zip package

```markdown

  wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.4.0.zip
  sha1sum elasticsearch-5.4.0.zip 
  unzip elasticsearch-5.4.0.zip
  cd elasticsearch-5.4.0/ 

   # Elasticsearch start and stop using the service command:
    start > ./bin/elasticsearch
    stop > pressing Ctrl-C
    
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

## Kibana 

Kibana is an open source, Used for browser-based analytics and search on Elasticsearch.Kibana gives shape to your data and user interface (UI) for configuring and managing the Elastic Stack.

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

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/technolabshq/ELK-Setup/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
