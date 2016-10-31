# PredictionIO

Install in ubuntu

Download Apache PredictionIO (incubating)

wget http://download.prediction.io/PredictionIO-0.9.6.tar.gz
tar zxvf PredictionIO-0.9.6.tar.gz

Installing Dependencies
mkdir tar PredictionIO-0.9.6/vendors

Spark Setup

Apache Spark is the default processing engine for PredictionIO. Download and extract it.

$ wget http://d3kbcqa49mib13.cloudfront.net/spark-1.5.1-bin-hadoop2.6.tgz
$ tar zxvfC spark-1.5.1-bin-hadoop2.6.tgz PredictionIO-0.9.6/vendors

If you decide to install Apache Spark to another location, you must edit PredictionIO-0.10.0-incubating/conf/pio-env.sh and change the SPARK_HOME variable to point to your own Apache Spark installation.

Elasticsearch is the default metadata store for PredictionIO. Download and extract it.

$ wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.4.4.tar.gz
$ tar zxvfC elasticsearch-1.4.4.tar.gz PredictionIO-0.9.6/vendors

HBase is the default event data store for PredictionIO. Download and extract it.
wget http://archive.apache.org/dist/hbase/hbase-1.0.0/hbase-1.0.0-bin.tar.gz
tar zxvfC hbase-1.0.0-bin.tar.gz PredictionIO-0.9.6/vendors
