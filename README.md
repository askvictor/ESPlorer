[![Stories in Ready](https://badge.waffle.io/4refr0nt/ESPlorer.png?label=ready&title=Ready)](https://waffle.io/4refr0nt/ESPlorer)
ESPlorer
========

Binary compiled from this fork is available at https://github.com/askvictor/ESPlorer/blob/master/ESPlorer/dist/ESPlorer.jar - this is built for Java 1.8


[![Join the chat at https://gitter.im/4refr0nt/ESPlorer](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/4refr0nt/ESPlorer?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
####Integrated Development Environment (IDE) for ESP8266 developers

###Package Description
The essential multiplatforms tools for any ESP8266 developer from luatool author’s, including a LUA for NodeMCU and MicroPython. Also, all AT commands are supported.

Required [JAVA](http://java.com/download) (Standard Edition - SE ver 7 and above) installed.

###Supported platforms
- Windows(x86, x86-64)
- Linux(x86, x86-64, ARM soft & hard float)
- Solaris(x86, x86-64)
- Mac OS X(x86, x86-64, PPC, PPC64)

###Detailed features list
- Syntax highlighting LUA and Python code
- Code editor color themes: default, dark, Eclipse, IDEA, Visual Studio
- Undo/Redo editors features
- Code Autocomplete (Ctrl+Space)
- Smart send data to ESP8266 (without dumb send with fixed line delay), check correct answer from ESP8266 after every lines.
- Code snippets
- Detailed logging
- and more, more more…

###Required libraries for build
* [jSSC](https://code.google.com/p/java-simple-serial-connector/)
* [rSyntaxTextArea](http://bobbylight.github.io/RSyntaxTextArea/)

###Discuss
* [English esp8266.com](http://www.esp8266.com/viewtopic.php?f=22&t=882)
* [Russian esp8266.ru](http://esp8266.ru/forum/threads/esplorer.34/)

###Home Page
[http://esp8266.ru/ESPlorer/](http://esp8266.ru/esplorer/)

###Latest binaries download
[esp8266.ru](http://esp8266.ru/esplorer/#download)

###How to build ESPlorer from sources
This fork will build on JDK 1.8, however, the upstream is (at time of writing) on 1.7. If you need to change the JDK number, change these in nbproject/project.properties:

    javac.source=1.8
    javac.target=1.8
    ...
    platform.active=JDK1.8

On my Ubuntu system, I built by installing openJDK 1.8 and ant. Once those were installed:
  
    $ ant -Dplatforms.JDK1.8.home=/usr/lib/jvm/java-8-openjdk-amd64 compile
    $ ant -Dplatforms.JDK1.8.home=/usr/lib/jvm/java-8-openjdk-amd64 jar

(change the JDK home path if it is installed elsewhere).


