Search API for geolocation fields

This module allows the geolocation fields to be indexed in the ElasticSearch as geolocable fields.

The module creates a widget type for facet filters that can filter the values according to the geolocation of the values.
This allows:
- use an ajax map as facet filter in conjunction with other facet filters
- be able to render many points on the map without having performance problems (grouping is done by ElasticSearch, not by php or js)
- filter each time the map is scrolled or zoomed

Important !!: This module only works with search_api and elasticsearch_connector.
It has been specifically tested with ElasticSearch v7
