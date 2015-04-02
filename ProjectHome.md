maven-web-plugin is a plugin that allows dependency management on projects that does not define default paths for dependecies.

it is based on the maven-war-plugin and maven-dependency-plugin but aims to permit maven dependency management on project developed on languages other then java, like php, asp, jsp.

A pom.xml sample:

```xml

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">

<modelVersion>4.0.0

Unknown end tag for &lt;/modelVersion&gt;



<groupId>com.br.webcentro

Unknown end tag for &lt;/groupId&gt;



<artifactId>webapp

Unknown end tag for &lt;/artifactId&gt;



<packaging>web

Unknown end tag for &lt;/packaging&gt;



<version>0.1

Unknown end tag for &lt;/version&gt;



<name>Sample Web App

Unknown end tag for &lt;/name&gt;



<description>A sample Web App using Maven-web-plugin

Unknown end tag for &lt;/description&gt;



<url>http://code.google.com/p/maven-web/

Unknown end tag for &lt;/url&gt;




<build>

<plugins>

<plugin>

<groupId>com.br.webcentro

Unknown end tag for &lt;/groupId&gt;



<artifactId>maven-web-plugin

Unknown end tag for &lt;/artifactId&gt;



<extensions>true

Unknown end tag for &lt;/extensions&gt;



<version>0.1

Unknown end tag for &lt;/version&gt;



<configuration>

<folders>

<folder classifier="cake">path/to/somewhere

Unknown end tag for &lt;/folder&gt;



<folder classifier="vendor">path/to/somewhere

Unknown end tag for &lt;/folder&gt;





Unknown end tag for &lt;/folders&gt;





Unknown end tag for &lt;/configuration&gt;





Unknown end tag for &lt;/plugin&gt;





Unknown end tag for &lt;/plugins&gt;





Unknown end tag for &lt;/build&gt;



<dependencies>

<dependency>

<groupId>org.cakephp

Unknown end tag for &lt;/groupId&gt;



<artifactId>cakephp-core

Unknown end tag for &lt;/artifactId&gt;



<version>1.2.6

Unknown end tag for &lt;/version&gt;



<classifier>cake

Unknown end tag for &lt;/classifier&gt;





Unknown end tag for &lt;/dependency&gt;





Unknown end tag for &lt;/dependencies&gt;





Unknown end tag for &lt;/project&gt;



```