A simple tracker for pulling from a page that Garafa's GPS Kit provides. When you're sharing
your location with their iPhone app to the web, there's a kinda-secret URL you can goto with
a JSON object that contains your longitude and latitude.

This package compiles into a jar which will pull that JSON object and lodge it into a table.

###Build it
```
mvn clean package
```

###Run it
Stick the JAR file in the same directory with gson-2.1.jar and
mysql-connector-java-5.1.18.jar and execute it with

```
java -jar tracker-1.jar
```