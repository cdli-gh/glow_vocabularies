---
layout: default
title: "Geography: Location"
rank: 1
---


# Location
<p><font size=2>Geography Working Group</font><br><font size=1>Rune Rattenborg, Sebastian Borkowski, Manuel Molina, Jamie Novotny, Susanne Rutishauser</font></p>

## Description
The **location** entity defines _any discrete, physical location of an archaeological nature_. Being a geographical entity, a **location** may or may not be associated with an historical [place](./geography_place.md), which may in turn be associated with one or more [names](./geography_name.md).

A **location**, as understood here, corresponds in part to the **provenience** entity typically included in digital text catalogues in cuneiform studies. For a typical example of the latter, see the table of proveniences as employed by the [Cuneiform Digital Library Initiative](https://cdli.mpiwg-berlin.mpg.de/proveniences). The notion of **location** employed here differs, however, in that it makes a distinction between a **provenience** with a known geographic location and a **provenience** without a known geographic location. The latter entity is considered an historical **place** in the present data model [(see for a description of this entity the specific entry on place)](./geography_place.md).

When limiting **location** to known geographic locations, the entity corresponds more seamlessly to general archaeological features constituting site records in archaeological gazetteers, which will generally not include entities without a known geographic location.

The extended conceptual meaning of this entity as employed here is derived in large part from the [location](https://pleiades.stoa.org/help/conceptual-overview) entity type of the [Pleiades: A Gazetteer of Past Places](pleiades.stoa.org) repository. As such, the use of this entity need not be limited to finds of cuneiform inscriptions, but indeed to any known archaeological feature of relevance for a given data collection. 

The stable URI format for **location** records in Pleiades are described in more detail in the [Pleiades documentation](https://pleiades.stoa.org/help/what-are-pleiades-uris). Here, **location** URIs are subordinated to a single parent **place** record.

In a [Wikidata](https://www.wikidata.org/) ontology, this would correspond to the Wikidata item [Q839954 archaeological site](https://www.wikidata.org/wiki/Q839954) or a more specific subordinated item, next to a dedicated item record for the specific place.

## Recommended fields
Being a geographical entity, a **location** record should always include a geographical coordinate utilising the **WGS84** coordinate reference system. A geographical coordinate includes **longitude** (x) and **latitude** (y), stored as **decimal degrees**. A geographical coordinate should always be accompanied by a definition of observational [certainty](./utility_certainty.md) made according to a known ordinal value set. For a **location**, observational certainty should reflect the **geographical precision** of the geographical coordinate, _not_ the certainty of association between the **location** and an ancient **place**.

name | description
-----|---------------
longitude | Longitude (x) of the location geographical coordinate in decimal degrees
latitude | Latitude (y) of the location geographical coordinate in decimal degrees
certainty | Degree of geographical precision of the location geographical coordinate
cdli | Identifier of the corresponding entity record in the [Cuneiform Digital Library Initiative](https://cdli.mpiwg-berlin.mpg.de/proveniences)
pleiades | Identifier of the corresponding entity record in [Pleiades](pleiades.stoa.org)
wikidata | Identifier of the corresponding entity record in [WikiData](http://wikidata.org)

## Optional fields
Apart from the recommended basic fields described above, a wide range of external identifiers can also be optionally included. 

name | description
-----|--------------
geonames_id | Link to the corresponding record in [GeoNames](http://geonames.org)
osm_id | Link to corresponding record in [OpenstreetMap](http://openstreetmap.org)
osm_type | Type of geometry associated with **osm_id** in [OpenstreetMap](http://openstreetmap.org). Three different types of vector geometry are employed, namely **node**, **way**, and 


## Resources
* The [Cuneiform Inscriptions Geographical Site Index (CIGS)](https://zenodo.org/record/4960710) provides an exhaustive and thoroughly linked index of known locations where cuneiform has been found. For a description of the index, see [Rattenborg et al. 2021](http://www.cdli.ucla.edu/pubs/cdlj/2021/cdlj2021_001.html)

* [Ancient Records of Middle Eastern Policies (ARMEP)](https://www.armep.gwi.uni-muenchen.de) provides an excellent web map search interface for proveniences of cuneiform texts. Locations are derived from [Pleiades] (see below), where corresponding data records can be found

* The [Database of Neo-Sumerian Texts (BDTNS)](http://bdtns.filol.csic.es), provides a web map visualisation of in-house [provenience and collection records](http://bdtns.filol.csic.es/mapa.php?modo=colecciones&pais=+the+World)

* [Pleiades: A Gazetteer of Past Places](https://pleiades.stoa.org/) is a leading historical geographical database for Classics, but also with an increasing number of records for the Middle East and adjoining regions. The database holds upwards of 35,000 place records.

* For open access indices of archaeological locations in the Middle East, see the most recent version of the [ANE Site Placemarks for Google Earth](https://zenodo.org/record/6384045) and the description of the index given in [Pedersén 2012]()
