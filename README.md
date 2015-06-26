## GenRestJson-J (Generic Rest/Json Java Project)

This is a simple example that shows how to deploy a simple http/https server serving rest/json services in java.
It uses jetty, gson, jersey , everything is packaged in a single jar that embeds the server. This project can help
deploying quickly a webserver for demo purpose. It serves also static pages defined in the project. It support jsonp calls.

### Packages to install on Ubuntu

One jdk, the oracle one or openjdk one
```
$ sudo apt-get install openjdk-7-jre
```
Maven
```
$ sudo apt-get install maven
```

### How to build 
```
$ mvn package
```

### Launch
```
$  java -jar ./jetty-generic-ws.jar
```

