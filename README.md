<img src="https://www.minlessika.com/com/webviewer/img/logo.svg" width="64px" height="64px"/>

[![EO principles respected here](https://www.elegantobjects.org/badge.svg)](https://www.elegantobjects.org)
[![DevOps By Rultor.com](http://www.rultor.com/b/ppom/ppom)](http://www.rultor.com/p/ppom/ppom)

[![Javadoc](http://www.javadoc.io/badge/com.minlessika.incubator/ppom.svg)](http://www.javadoc.io/doc/com.minlessika.incubator/ppom)
[![PDD status](http://www.0pdd.com/svg?name=Minlessika/ppom)](http://www.0pdd.com/p?name=Minlessika/ppom)
[![Maven Central](https://img.shields.io/maven-central/v/com.minlessika.incubator/ppom.svg)](https://maven-badges.herokuapp.com/maven-central/com.minlessika.incubator/ppom)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Minlessika/ppom/blob/master/LICENSE.txt)

[![Test Coverage](https://img.shields.io/codecov/c/github/Minlessika/ppom.svg)](https://codecov.io/github/Minlessika/ppom?branch=master)
[![Hits-of-Code](https://hitsofcode.com/github/Minlessika/ppom)](https://hitsofcode.com/github/Minlessika/ppom/view)

Project architect: [baudoliver7](https://github.com/baudoliver7)

This is a parent [POM](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html) for all Minlessika Maven projects. Include it in project section of `pom.xml`:
```xml
  <modelVersion>4.0.0</modelVersion>
  <artifactId><!-- your artifact id --></artifactId>
  <version>1.0-SNAPSHOT</version>
  <parent>
    <groupId>com.minlessika</groupId>
    <artifactId>ppom</artifactId>
    <version><!-- use latest version --></version>
  </parent>
```

## How to contribute

Fork repository, make changes, send us a pull request. We will review
your changes and apply them to the `master` branch shortly, provided
they don't violate our quality standards. To avoid frustration, before
sending us your pull request please run full Maven build:

```
$ mvn clean install -Pqulice
```

To avoid build errors use Maven 3.2+.

