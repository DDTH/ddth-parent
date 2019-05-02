# ddth-parent

Parent POM for other DDTH's projects.

Project home:
[https://github.com/DDTH/ddth-parent](https://github.com/DDTH/ddth-parent)

_`ddth-parent` migrated to **Java 11** since v11._

## License

See [LICENSE.txt](LICENSE.txt) for details. Copyright (c) 2014-2019 Thanh Ba Nguyen.

Third party libraries are distributed under their own license(s).


## Release notes

Latest release: `version 11`.

See [RELEASE-NOTES.md](RELEASE-NOTES.md).


## Content

Java version: **`Jdk11`**

Defined properties:

```xml
    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <version.java>11</version.java>
    </properties>
```

Maven plugins:

- `org.apache.maven.plugins:maven-compiler-plugin:3.8.0`
- `org.apache.maven.plugins:maven-javadoc-plugin:3.1.0` (with flag `-Xdoclint:none`)
- `org.apache.maven.plugins:maven-assembly-plugin:3.1.1`
- `org.apache.maven.plugins:maven-surefire-plugin:2.22.1`
- `org.apache.felix:maven-bundle-plugin:4.2.0`
- `org.apache.maven.plugins:maven-gpg-plugin:1.6`

Custom repositories:

```xml
<repositories>
	<repository>
		<id>sonatype-org</id>
		<name>Sonatype Releases</name>
		<url>http://oss.sonatype.org/content/repositories/releases/</url>
	</repository>
</repositories>
```
