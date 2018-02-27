# Ant tomcat example

## Getting Started

1. Install tomcat 7>
2. Set roles for tomcat "tomcat-users.xml"
3. Copy from "tomcat.properties.dist" to "tomcat.properties"
    Unix:
    ```
    cp tomcat.properties.dist tomcat.properties
    ```
4. Set config tomcat to "tomcat.properties"

Compile

```
ant compile
```

Create war

```
ant war
```

Deploy war

```
ant deploy
```

Undeploy

```
ant undeploy 
```

Clear dir

```
ant clean
```

## Built With

* [Tomcat](http://tomcat.apache.org/)
* [jUnit](https://junit.org/junit4/)
* [Ant](https://ant.apache.org/)
* [ivy](http://ant.apache.org/ivy/)
