---
layout: page
title: Projects
permalink: projects.html
---

This page lists a set of selected projects that I've worked on. It includes contributions done to the open source projects as well as some projects I've implemented to satisfy course requirements in grad school.

* Open Source Contributions  
	- [Apache Rampart](#os-rampart)  
	- [WSO2 Identity Server](#os-wso2is)  
	- [Google Summer of Code](#os-gsoc)
* Course Projects
	- [Using Dijkstra’s Shortest Paths to Route Packets in a Network Overlay](#cp-overlay)
	- [Corpus Analysis Using MapReduce: Zeitgeist and Language Evolution](#cp-nio)
	- [Using Thread Pools to Manage Active Network Connections](#cp-mapred)
* [Github](#github)

---

### Open Source Contributions

#### <a name="os-rampart"></a>Apache Rampart
I am a committer and a project management committee member for [Apache Axis2](http://axis.apache.org/axis2/java/core/), a leading open source web services engine. I contributed mainly to its security module, [Rampart](http://axis.apache.org/axis2/java/rampart/) where I authored the [SAML 2.0](http://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf) support for [WS-Trust](http://docs.oasis-open.org/ws-sx/ws-trust/200512/ws-trust-1.3-os.html) module of Rampart in addition to various bug fixes and improvements.

#### <a name="os-wso2is"></a>WSO2 Identity Server
While employed at [WSO2](http://wso2.com), I contributed to [WSO2 Identity Server](http://wso2.com/products/identity-server/) which is an open source identity and entitlement management server. Some of my major contributions are SAML 2.0 based single sign on implementation, OAuth 2.0 identity provider support, Security Token Service improvements and implementing XMPP based multi-factor authentication.

#### <a name="os-gsoc"></a>Google Summer of Code
I am a two times [Google Summer of Code](https://developers.google.com/open-source/soc/?csw=1) winner in 2008 and 2009. In Summer 2008, I contributed to Apache Tuscany by implementing Tuscany Service Component Architecture support in Apache Geronimo. I started contributing to Apache Rampart through GSoC 2009 by improving its test coverage.

---
### Selected Course Projects

#### <a name="cp-overlay"></a>Using Dijkstra’s Shortest Paths to Route Packets in a Network Overlay
A distributed overlay network in which the routing plans are calculated using Dijkstra's algorithm. The overlay network is formed according to a Cayley graph. The communication layer is implemented using Java TCP sockets. [[Source](https://github.com/thilinamb/network-overlay)]

#### <a name="cp-nio"></a>Java NIO based Server backed by a home grown threadpool manager
Java NIO based server implementation backed by a configurable thread pool implemented from the ground up. The thread pool is capable of handling incoming network connections, processing traffic and sending out data. This implementation is extensible such that a custom message processing logic can be plugged-in. This implementation was tested upto 200 concurrent users with a thread-pool with 5 worker threads. [[Source](https://github.com/thilinamb/java-nio-server)]

#### <a name="cp-mapred"></a>Corpus Analysis Using MapReduce: Zeitgeist and Language Evolution
A MapReduce program that analyzes a corpus comprised of books published by authoris spanning centuries. As part of the analysis, Flesch Reading Ease and Flesch–Kincaid Grade Level scores along with the Term Frequency-Inverse Document Frequency (TF-IDF) scores are calculated based on the extracted N-grams. This program was implemented targeting Hadoop MapReduce runtime and was tested for a corpus of 1000 books obtained from Project Guttenberg. [[Source](https://github.com/thilinamb/corpus-analysis-with-hadoop)]

---
### <a name="github"></a> Projects on Github
Some of the projects I have worked on can be found on my [Github](http://github.com/thilinamb) page. 