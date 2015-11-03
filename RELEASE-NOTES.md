ddth-parent release notes
=========================

Parent POM for other DDTH's projects

v5 - 2015-10-03
---------------

Upgrade OSS parent to v9.

Defined properties:

```xml
    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <version.java>1.7</version.java>
        <version.junit>4.12</version.junit>
        <version.osgi>4.3.0</version.osgi>
        <version.spring>4.2.2.RELEASE</version.spring>
        <version.spring.osgi>1.2.1</version.spring.osgi>
        <version.guava>18.0</version.guava>
        <version.jackson>2.6.3</version.jackson>
        <version.slf4j>1.7.12</version.slf4j>
        <version.log4j>1.2.17</version.log4j>
    </properties>
```

Maven plugins:

- `org.apache.maven.plugins:maven-compiler-plugin:3.3`
- `org.apache.maven.plugins:maven-assembly-plugin:2.6`
- `org.apache.maven.plugins:maven-surefire-plugin:2.19`
- `org.apache.felix:maven-bundle-plugin:3.3.0`
- `org.apache.maven.plugins:maven-gpg-plugin:1.6`


v2 - 2014-10-09
---------------

Java version: `1.7`

Defined properties:

```xml
<properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <version.java>1.7</version.java>
    <version.junit>4.11</version.junit>
    <version.osgi>4.3.0</version.osgi>
    <version.spring>3.2.11.RELEASE</version.spring>
    <version.spring.osgi>1.2.1</version.spring.osgi>
    <version.guava>16.0.1</version.guava>
    <version.jackson>2.4.3</version.jackson>
    <version.slf4j>1.7.7</version.slf4j>
    <version.log4j>1.2.17</version.log4j>
</properties>
```

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

Maven plugins:

- `org.apache.maven.plugins:maven-compiler-plugin:3.1`
- `org.apache.maven.plugins:maven-assembly-plugin:2.4.1`
- `org.apache.maven.plugins:maven-surefire-plugin:2.17`
- `org.apache.felix:maven-bundle-plugin:2.5.3`


v1 - 2014-03-21
---------------

First release.
