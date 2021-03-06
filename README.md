ftp4j [![Build Status](https://travis-ci.org/asbachb/ftp4j.svg?branch=master)](https://travis-ci.org/asbachb/ftp4j)
=====

ftp4j is a java implementation of the ftp, ftps and ftpes protocol.

The artefacts are also published via github pseudo maven repository. So if you want to use ftp4j as dependency in your maven project just add following repository definition to your pom.xml

    <repositories>
        <repository>
            <id>github-asbachb-releases</id>
            <url>https://raw.github.com/asbachb/mvn-repo/master/releases</url>
        </repository>
    </repositories>
    
To add ftp4j as dependency just add following declaration to your pom.xml

    <dependency>
        <groupId>it.sauronsoftware.ftp4j</groupId>
        <artifactId>ftp4j</artifactId>
        <version>1.7.2</version>
    </dependency>

original source from
* http://www.sauronsoftware.it/projects/ftp4j/
by
* Carlo Pelliccia
