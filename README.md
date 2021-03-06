# PrimeFaces Showcase - JSF Tools version

### Getting Started

Deployable version of **PrimeFaces Showcase** war file can be downloaded manually or build it from sources.  

##### Prebuilt war

For a full list of the available downloads, please visit the [download page](http://www.primefaces.org/downloads). Scroll down to showcase for war file link.

##### Build from sources

```
git clone https://github.com/primefaces/showcase.git
cd showcase
mvn clean                  -- clean temp files from target folder
mvn package                -- create war file (under target directory)
mvn jetty:run              -- run showcase project locally
```

##### Run from local sources

Running showcase with `PrimeFaces 5.3-SNAPSHOT`
```
mvn clean jetty:run -Pdev
OR 
mvn clean jetty:run  
```

Running showcase with `PrimeFaces 5.2` stable release
```
mvn clean jetty:run -Pcommunity-stable
```

Running showcase with `PrimeFaces 5.2.2-SNAPSHOT` elite release
```
mvn clean jetty:run -Pelite-dev
```

##### Create installable WAR file

Development version 
```
mvn clean package
```
Stable version
```
mvn clean package -Pcommunity-stable
```
Elite version
```
mvn clean package -Pelite-dev
```

[http://localhost:8080/showcase/](http://localhost:8080/showcase)

[http://localhost:8080/showcase/mobile/index.xhtml](http://localhost:8080/showcase/mobile/index.xhtml)

### License

Licensed under the Apache License, Version 2.0 (the "License") [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
