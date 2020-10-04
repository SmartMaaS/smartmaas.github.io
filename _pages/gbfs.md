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

* Conversion of GBFS archives to Linked Data 
* Computation of the [Linked Connections](https://linkedconnections.org/) graph

## SPARQL API/Service Features

The presented novel service:
* Performs SPARQL queries against non-RDF datasets.
* Is not dependent of a certain source format, as long as the source to be queried is structured.

## System Overview

![image-center](/assets/images/GBFS_call_sequence.png){: .align-center}