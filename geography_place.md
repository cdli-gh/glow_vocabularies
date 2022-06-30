---
layout: default
title: "Geography: Place"
rank: 1
---
# Place
<p><font size=2>Geography Working Group</font><br>
<font size=1>Rune Rattenborg, Sebastian Borkowski, Manuel Molina, Jamie Novotny, Susanne Rutishauser</font></p>

## Description
The **place** entity defines _any discrete, historical place_. A place, as understood in the present context, is not a geographical, but a conceptual entity, separate from a [location](./geography_location.md), which is a geographical entity, and a [names](./geography_name.md), which is a linguistic entity. The majority of digital text catalogues in cuneiform studies currently maintain historical places, archaeological proveniences, and their names in a single table, thereby conflating the above entities within a single dimension.

The basis for conceptually separating a historical place and its physical [location](./geography_location.md) lies with the uncertainty and fuzziness of historical geographical information. A **place** may be known through a [name](./geography_name.md), or through an archaeological [location](./geography_location.md). Maintaining **place**, [name](./geography_name.md), and [location](./geography_location.md) as separate entities within a relational data structure allows for the association of one **place** with none, one, or more than one [location](./geography_location.md) or none, one, or more than one [name](./geography_name.md). It also allows for the qualification of associations between each of these entities with separate levels of relational [certainty](utilities_certainty.md). 

The **place** entity as understood in the present context is largely identical to the [place](https://pleiades.stoa.org/help/conceptual-overview) entity type employed by the [Pleiades: A Gazetteer of Past Places](pleiades.stoa.org) repository. Within this data ontology, a **place** is an entirely abstract, conceptual entity, that can exist in name only (as a place mentioned in an inscription) or in location only (as the archaeological site of an ancient place without a name). Since [connections](https://pleiades.stoa.org/help/conceptual-overview) between **places** are an integral part of the [Pleiades](pleiades.stoa.org) ontology, a **place** can then be located relative to another **place**, without necessitating a geographical **location**.

## Recommended fields
As an abstract, conceptual entity, a **place** will typically be defined either through its association with a [name](./geography_name.md) or a [location](./geography_location.md), or both. When having a known association with a geographical [location](./geography_location.md), a **place** can usually be linked to an external identifier conflating **place** and **location** without any problems.

name | description
-----|---------------
cdli_id | Identifier of the related provenience entity record in the [Cuneiform Digital Library Initiative](http://cdli.mpiwg-berlin.mpg.de/proveniences)
pleiades_id | Identifier of the corresponding entity record in [Pleiades](pleiades.stoa.org)
wikidata | Identifier of the corresponding entity record in [WikiData](http://wikidata.org)

## Optional fields
Additional links predominantly include identifiers from historical and geographical gazetteers, depending again on whether the association between a **place** and a **location** is known or not known.
name | description
-----|---------------
whg | Identifier of the corresponding entity record in [World History Gazetteer](pleiades.stoa.org)

## Resources
* For an updated index of archaeological locations where cuneiform texts have been found, see the most recent version of the [Cuneiform Inscriptions Geographical Site Index (CIGS)]() and the description of the index given in [Rattenborg et al. 2021](http://www.cdli.ucla.edu/pubs/cdlj/2021/cdlj2021_001.html)

* For an index and searchable web map of archaeological locations associated with artefacts included in the [Ancient Records of Middle Eastern Policies (ARMEP)]()

* For an index and searchable web map of archaeological locations associated with artefacts included in the [Database of Neo-Sumerian Texts (BDTNS)]()

* For open access indices of archaeological locations in the Middle East, see the most recent version of the [ANE Site Placemarks for Google Earth](https://zenodo.org/record/6384045) and the description of the index given in [Pedersén 2012]()



