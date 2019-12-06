---
title: "GBFS"
permalink: "/gtfs/"
layout: single
author_profile: false
classes: wide
---
We provide a free and ready-to-use data processing system which transforms and publishes [General Transit Feed Specification (GTFS)](https://developers.google.com/transit/gtfs) archives into Linked Data using the [Linked GTFS](https://github.com/OpenTransport/linked-gtfs) and [Linked Connections](https://linkedconnections.org/) vocabularies.

## Features

* Conversion of GTFS archives to Linked Data 
* Computation of the [Linked Connections](https://linkedconnections.org/) graph
* HDT compression and indexing 
* Spatial indexing of `gtfs:Stop` instances
* Triple store setup, configuration and data loading
* REST API exposing [Linked GTFS](https://github.com/OpenTransport/linked-gtfs) and [Linked Connections](https://linkedconnections.org/) triples in various RDF serialization formats  


## Domain Model
![image-center](/assets/images/gtfs_domain_model.png){: .align-center}

Our domain model uses the terms defined in
* the [Linked GTFS vocabulary](http://vocab.gtfs.org/gtfs.ttl#)
* the [Linked Connection vocabulary](http://semweb.mmlab.be/ns/linkedconnections#)
* the [DBPedia vocabulary](http://dbpedia.org/ontology/)




## System Overview

![image-center](/assets/images/gtfs_stack.png){: .align-center}

