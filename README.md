eluder-parent
=============

Parent project for all org.eluder maven projects


#### Continuous integration

Travis CI builds eluder-parent with Oracle JDK 7. All successfully built snapshots are deployed to Sonatype OSS
repository.

[![Build Status](https://travis-ci.org/trautonen/eluder-parent.png)](https://travis-ci.org/trautonen/eluder-parent)


#### Clirr Maven Plugin

Check binary compatibility against a specific version:

```
mvn clirr:check -DcomparisonVersion=<version>
```


#### Versions Maven Plugin

Display dependency updates:

```
mvn versions:display-dependency-updates
```

Display plugin updates:

```
mvn versions:display-plugin-updates
```
