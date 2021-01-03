Original Maven Archetypes
==========================

* [com.nerdhead:maven-archetype-webapp-custom:1.0.0](#maven-archetype-webapp-custom)

## Usage

> for Terminal

```bash
mvn archetype:generate -DarchetypeCatalog=https://nerdhead.github.io/maven-archetypes/archetype-catalog.xml
```

> for Eclipse

* Go to `Preferences > Maven > Archetypes` and `Add Remote Catalog`

```
Catalog File: `https://nerdhead.github.io/maven-archetypes/archetype-catalog.xml`   
Description: `NERDHEAD's archetypes`
```

> for IntelliJ

* Go to `Create New Project > Java > Maven`
* Add a Check `Create from archetype`
* Select Button `Add Archetype...`

```
GroupId: com.ogaclejapan
ArtifactId: {{archetype}}  #e.g. maven-archetype-webapp-custom
Version: {{version}}       #e.g. 1.0.0
Repository: https://github.com/NERDHEAD/maven-archetypes
```

## Archetypes

> maven-archetype-webapp-custom:1.0

_This archetype generates a stand alone application project in Java._

Based on:
* JDK 11
* Servlet 3.1
* Spring 4.1.6.RELEASE
* log4j 1.2.17
* slf4j 1.6.6

- Spring security 4.0.1.RELEASE
- mybatis + ojdbc6 + spring-orm + mybatis-spring + commons-dbcp

See https://nerdhead.github.io/maven-archetypes/archetype-catalog.xml



## Reference

> archetype-catalog

   * https://github.com/ogaclejapan/maven-archetypes/edit/master/README.md

> archetype-repository

   * https://github.com/ogaclejapan/maven-archetypes
