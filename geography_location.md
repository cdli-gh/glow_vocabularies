---
layout: default
title: "Geography: Location"
rank: 1
---


# Location
<font size=2>Geography Working Group</font>

<font size=1>Rune Rattenborg, Sebastian Borkowski, Manuel Molina, Jamie Novotny, Susanne Rutishauser</font>

## Description
The **location** entity defines any discrete, physical location of an archaeological nature, generally corresponding to the **provenience** entity typically included in digital catalogues in cuneiform studies, and the archaeological feature constituting a site in an archaeological gazetteer. For a typical example of **location** entities as employed in digital catalogues in cuneiform studies, see the documentation of the

The extended conceptual meaning of this entity as employed here is derived in large part from the **location** entity type of the [Pleiades: A Gazetteer of Past Places](pleiades.stoa.org) repository, where it need not refer solely to a known archaeological provenience of a cuneiform inscription, but indeed to any known physical location. A **location** may correspond to the provenience of a cuneiform inscription, or a historical **place** related to one or more **names** found in one or several cuneiform inscriptions, or an archaeological feature otherwise included in a given data collection, for example on the basis of historical contemporaneity.

## Recommended fields
As a geographical entity, a **location** record should always include a geographical coordinate utilising the **WGS84** coordinate reference system. A geographical coordinate includes **longitude** (x) and **latitude** (y), stored as **decimal degrees**. A geographical coordinate should always be accompanied by a definition of observational [certainty](./utility_certainty.md) made according to a known ordinal value set. For a **location**, observational certainty should reflect the **geographical precision** of the geographical coordinate, _not_ the certainty of association between the **location** and an ancient **place**.

name | description
-----|---------------
longitude | Longitude (x) of the location geographical coordinate in decimal degrees
latitude | Latitude (y) of the location geographical coordinate in decimal degrees
certainty | Degree of geographical precision of the location geographical coordinate
wikidata | Identifier of the corresponding entity record in [WikiData](http://wikidata.org)

Linking the **location** record to a corresponding **wikidata** identifier will also establish a link to all associated identifiers included by WikiData. As such, a WikiData identifier will usually link to corresponding identifiers from GeoNames, OpenStreetMap,

## Optional fields
Apart from the recommended basic fields described above, a wide range of external identifiers can also be optionally included. 

name | description
-----|--------------
geonames_id | Link to the corresponding record in [GeoNames](http://geonames.org)
osm_id | Link to corresponding record in [OpenstreetMap](http://openstreetmap.org)
osm_type | Type of geometry associated with **osm_id** in [OpenstreetMap](http://openstreetmap.org). Three different types of vector geometry are employed, namely **node**, **way**, and 
pleiades_id | Link to corresponding record in [Pleiades](pleiades.stoa.org)

## Resources
* For an updated index of archaeological locations where cuneiform texts have been found, see the most recent version of the [Cuneiform Inscriptions Geographical Site Index (CIGS)]() and the description of the index given in [Rattenborg et al. 2021](http://www.cdli.ucla.edu/pubs/cdlj/2021/cdlj2021_001.html)

* For open access indices of archaeological locations in the Middle East, see the most recent version of the [ANE Site Placemarks for Google Earth](https://zenodo.org/record/6384045) and the description of the index given in [Pedersén 2012]()
