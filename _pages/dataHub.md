---
title: "Linked Data Hub"
permalink: "/datahub/"
layout: single
author_profile: false
classes: wide
---
We provide a list of endpoints(queries) to acquire data from. 


## List:

* ### /api/v1/providers/
    Paginates all available gtfs:Providers as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId:.+}
    Requests a particular gtfs:Provider
* ### /api/v1/providers/{providerId}/itinerary/
    Paginates itinerary information available gtfs:Connections as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/stations/{stationId}
    Requests a particular gbfs:Station
* ### /api/v1/providers/{providerId}/stations/
    Paginates all available gbfs:Stations as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/status/
    Paginates all available gbfs:Status as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/status/{statusId}
    Requests a particular gbfs:Status
* ### /api/v1/providers/{providerId}/hours/
    Paginates all available gbfs:Hours as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/hours/{hourId}
    Requests a particular gbfs:Hours
* ### /api/v1/providers/{providerId}/routes/{routeId:.+}
    Requests a particular gtfs:Route
* ### /api/v1/providers/{providerId}/routes/
    Paginates all available gtfs:Routes as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/stops/{stopId}
    Requests a particular gtfs:Stop
* ### /api/v1/providers/{providerId}/stops/nearBy
    Paginates all gtfs:Stops nearby a given geographical position
* ### /api/v1/providers/{providerId}/stops/search
    Paginates all gtfs:Stops found by a text query
* ### /api/v1/providers/{providerId}/stops/
    Paginates all available gtfs:Stops as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/trips/{tripId:.+}
    Requests a particular gtfs:Trip
* ### /api/v1/providers/{providerId}/trips/
    Paginates all available gtfs:Trips as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/connections/
    Paginates all available gtfs:Connections as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/connections/{connectionId:.+}
    Requests a particular gtfs:Connection
* ### /api/v1/providers/{providerId}/agencies/
    Paginates all available gtfs:Agencies as hydra:PartialCollectionViews
* ### /api/v1/providers/{providerId}/agencies/{agencyId:.+}
    Requests a particular gtfs:Agency   
* ### / 