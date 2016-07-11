ddth-parent
===========

Parent POM for other DDTH's projects.

Project home:
[https://github.com/DDTH/ddth-parent](https://github.com/DDTH/ddth-parent)


## License ##

See [LICENSE.txt](LICENSE.txt) for details. Copyright (c) 2014-2016 Thanh Ba Nguyen.

Third party libraries are distributed under their own license(s).


## Release-notes ##

Latest release: `version 6`.

See [RELEASE-NOTES.md](RELEASE-NOTES.md).


## Content ##

Java version: `1.8`

Defined properties:

```xml
    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <version.java>1.8</version.java>
    </properties>
```

Maven plugins:

- `org.apache.maven.plugins:maven-compiler-plugin:3.5.1`
- `org.apache.maven.plugins:maven-assembly-plugin:2.6`
- `org.apache.maven.plugins:maven-surefire-plugin:2.19.1`
- `org.apache.felix:maven-bundle-plugin:3.0.1`
- `org.apache.maven.plugins:maven-gpg-plugin:1.6`

Custom repositories:

```xml
<repositories>
    <repository>
        <id>com.springsource.repository.bundles.release</id>
        <name>EBR Spring Release Repository</name>
        <url>http://repository.springsource.com/maven/bundles/release</url>
    </repository>
    <repository>
        <id>com.springsource.repository.bundles.external</id>
        <name>EBR External Release Repository</name>
        <url>http://repository.springsource.com/maven/bundles/external</url>
    </repository>
    <repository>
        <id>sonatype-org</id>
        <name>Sonatype Releases</name>
        <url>http://oss.sonatype.org/content/repositories/releases/</url>
    </repository>
</repositories>
```
