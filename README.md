<img src="https://www.minlessika.com/com/webviewer/img/logo.svg" width="64px" height="64px"/>

[![EO principles respected here](https://www.elegantobjects.org/badge.svg)](https://www.elegantobjects.org)
[![DevOps By Rultor.com](http://www.rultor.com/b/ppom/ppom)](http://www.rultor.com/p/ppom/ppom)

[![Javadoc](http://www.javadoc.io/badge/com.minlessika.erp/ppom.svg)](http://www.javadoc.io/doc/com.minlessika.erp/ppom)
[![PDD status](http://www.0pdd.com/svg?name=minlessika/ppom)](http://www.0pdd.com/p?name=minlessika/ppom)
[![Maven Central](https://img.shields.io/maven-central/v/com.minlessika.erp/ppom.svg)](https://maven-badges.herokuapp.com/maven-central/com.minlessika.erp/ppom)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/minlessika/ppom/blob/master/LICENSE.txt)

[![Test Coverage](https://img.shields.io/codecov/c/github/minlessika/ppom.svg)](https://codecov.io/github/minlessika/ppom?branch=master)
[![Hits-of-Code](https://hitsofcode.com/github/minlessika/ppom)](https://hitsofcode.com/github/minlessika/ppom/view)

Project architect: [baudoliver7](https://github.com/baudoliver7)

This is a parent [POM](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html) for all Minlessika Maven projects. Include it in project section of `pom.xml`:
```xml
  <modelVersion>4.0.0</modelVersion>
  <parent>
    <groupId>com.minlessika.erp</groupId>
    <artifactId>ppom</artifactId>
    <version><!-- use latest version --></version>
  </parent>
  <artifactId><!-- your artifact id --></artifactId>
  <version>1.0-SNAPSHOT</version>
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

