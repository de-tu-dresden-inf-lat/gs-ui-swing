# Graphstream Swing UI for Java 11.

## This project is a fork of [GraphStream/gs-ui-swing](https://github.com/graphstream/gs-ui-swing), redistributed under CECILL-C license.


The GraphStream project is a java library that provides an API to model, analyze and visualize graphs and dynamic graphs.

This module contains a Swing implementation of the GraphStream Viewer.

Check out the original projects website <http://www.graphstream-project.org> for more information.

## Install

`gs-ui-swing` is a plugin to the  `gs-core` main project. 

Maven users may include major releases of `gs-core` and `gs-ui-swing` as dependencies: 

```xml
<dependencies>
    <dependency>
        <groupId>org.graphstream</groupId>
        <artifactId>gs-core</artifactId>
        <version>2.2</version>
    </dependency>

    <dependency>
        <groupId>org.graphstream</groupId>
        <artifactId>gs-ui-swing</artifactId>
        <version>2.2</version>
    </dependency>
</dependencies>
```


## Configure UI

`gs-core` needs to be told which UI implementation to use. Simply add a system property to you project:

```java
System.setProperty("org.graphstream.ui", "swing");
```

Or use the command line :

```bash
java -Dorg.graphstream.ui=swing YourClass
```

## Help

You may check the documentation on the [website](http://graphstream-project.org).

## License

See the COPYING file.
