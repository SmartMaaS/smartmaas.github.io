---
title: "GBFS"
permalink: "/gbfs/"
layout: single
author_profile: false
classes: wide
---
General Bikeshare Feed Specification, abbreviated as GBFS, provides a standardized data feed for bike share system. [GBFS](https://github.com/amohoste/gbfs-linked) makes real-time data feeds in a uniform format publicly available online, with an emphasis on findability. [GBFS](https://github.com/amohoste/gbfs-linked) is intended to make information publicly available online; therefore information that is personally identifiable is not currently and will not become part of the core specification. [GBFS](https://github.com/amohoste/gbfs-linked) is intended as a specification for real-time, read-only data - any data being written back into individual bikeshare systems are excluded from this spec

We provide a free and ready-to-use data processing system which transforms and publishes [GBFS](https://github.com/amohoste/gbfs-linked) archives into [Linked Data](https://github.com/amohoste/gbfs-linked) using Linked GBFS and [Linked Connections](https://linkedconnections.org/) vocabularies.

## GBFS  Features

* SPARQL service to query GBFS live data 
* Conversion of GBFS archives to Linked Data 
 

## SPARQL API/Service Features

The presented offline novel solution is a micro-service, allows to send semantic queries against the legacy Web interfaces directly, and returns the result in RDF. The service API follows the SPARQL 1.1 Query API specification, and also supports federated queries over distributed endpoints, allowing an easy and accessible way for semantically enriched data integration over legacy endpoints. 

* Performs SPARQL queries against non-RDF datasets.
* Is not dependent of a certain source format, as long as the source to be queried is structured.

## System Overview

![image-center](/assets/images/GBFS_call_sequence.png){: .align-center}

## SPARQL WRAPPER

![image-center](/assets/images/GBFS_sparql_wrapper.png){: .align-center}

## Usage

### System and Environment Requirements


### Building the system

```
git clone [BLA]
cd [BLA]
./docker-build.sh
```

### Processing a GTFS archive

```
./docker-run.sh --no-port /opt/gtfs-converter/import.sh https://opendata.rnv-online.de/sites/default/files/rnv-GTFS_145.zip rnv 2019-11-27
```

### Publishing the GTFS archive

```
./docker-run.sh
```

## Performance
65475475
67971898