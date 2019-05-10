Usage:

Install the latest 8.x version of logstash.

Download and unzip the latest version of cities500.zip file from
http://download.geonames.org/export/dump/

$ curl -O -L http://download.geonames.org/export/dump/cities500.zip
$ unzip cities500.zip

Start logstash:

$ path/to/logstash_home/bin/logstash -f cities.conf < cities500.txt
