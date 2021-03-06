![Jooby][jooby img]

[![][travis img]][travis]
[![][coverage img]][coverage]
[![][gitter img]][gitter]
[![][license img]][license]

# Jooby Samples
Simple samples based on [Jooby](http://jooby.org) a scalable, fast and modular micro web framework for Java.
 
## Introduction
Since **Jooby** is a pretty new thing in the Java-ecosystem, I decided to contribute to the project by providing a complete (I hope) set of samples on how to use this awesome framework.
The modules included in Jooby are a lot and some of them hide some interesting gems (did you check the Thread Model API? so cool!), so I want to try to show its potential.

## First Step
The first step of the project is to provide random samples keeping an eye on the pattern shown in the official [Jooby-Modules](http://jooby.org/modules) page.
There is no road-map for now, so there is no priority on which module will be completed first, hence be patient.
However if I'm able to get the right rhythm I might try to be less sketchy. This will be a checklist, so drop by whenever you need to check the progress:

* **Route Spec**
	* Script API samples: Jetty, Undertow, Netty
	* MVC API sample
	* Rest API sample: Gson, Jackson
* **Data: Jdbc**
* **Data: NoSQL**
* **Assets: CSS Processors**
* **Assets: Javascript Processors**
* **Renderer**
* **Parser**
* **Reactive & Async**
* **Http Session**
* **Caches**
* **Security**

### Addendum
Since Jooby provides different embedded-web-server integrations such as [Undertow](http://undertow.io), [Jetty](http://www.eclipse.org/jetty/) and [Netty](http://netty.io/), in order to simplify the job, by default all the provided samples are going to use Jetty.
Nothing really changes using one web-server for another, with Jooby is possible to replace the web-server integration dependency with your favourite transparently.

*Jetty has been chosen just following the trend shown on [Google Trends](https://trends.google.com/trends/explore?cat=732&q=undertow,jetty,netty) no biased decision.*

## Languages and Build Systems
For now just:
* **Oracle Java 8**
* **Apache Maven 3.3.9**

Then (I don't know when, sorry):
* **Gradle 3.x+**
* **Kotlin 1.x+**
* **Javascript**

In a dream of mine:
* **Ceylon 1.3.x+**

[jooby img]:https://raw.githubusercontent.com/trydent-io/jooby-samples/master/logo_jooby.png

[travis]:https://travis-ci.org/trydent-io/jooby-samples
[travis img]:https://travis-ci.org/trydent-io/jooby-samples.svg?branch=master

[coverage]:https://coveralls.io/github/trydent-io/jooby-samples?branch=master
[coverage img]:https://coveralls.io/repos/github/trydent-io/jooby-samples/badge.svg?branch=master

[gitter]:https://gitter.im/jooby-project/jooby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[gitter img]:https://badges.gitter.im/jooby-project/jooby.svg

[license]:LICENSE-2.0.txt
[license img]:https://img.shields.io/badge/License-Apache%202-blue.svg