# ambari-presto-service [![BuildStatus](https://travis-ci.org/prestosql/ambari-presto-service.svg?branch=master)](https://travis-ci.org/prestosql/ambari-presto-service)

This project contains the code and configuration needed to integrate Presto with Ambari.

1、trino 447 needs JDK 22, install JDK to `/usr/local` every node.  
2、update `java_home` in `package/scripts/params.py`.  
3、update trino rpm urls in `package/scripts/download.ini`.  
4、unzip this package to `/var/lib/ambari-server/resources/stacks/HDP/3.1/services/PRESTO`.  
5、restart ambari-server.  

