<img src="https://www.minlessika.com/com/webviewer/img/logo.svg" width="64px" height="64px"/>

[![EO principles respected here](https://www.elegantobjects.org/badge.svg)](https://www.elegantobjects.org)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Minlessika/ppom/blob/master/LICENSE.txt)

This is a parent [POM](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html) for all
Minlessika Maven projects. Include it in project section of `pom.xml`:
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

