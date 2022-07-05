---
layout: default
title: "Geography: Place"
rank: 1
---
# Place
<p><font size=2>Geography Working Group</font><br>
<font size=1>Rune Rattenborg, Sebastian Borkowski, Manuel Molina, Jamie Novotny, Susanne Rutishauser</font></p>

## Description
The **place** entity defines _any discrete, historical place_. A place, as understood in the present context is a historical and conceptual entity, separate from a [location](./geography_location.md), which is a geographical entity, and a [name](./geography_name.md), which is a linguistic entity. The majority of digital text catalogues in cuneiform studies currently maintain historical places, archaeological proveniences, and their names in a single table, but this practice conflates the above entities within a single dimension.

The basis for conceptually separating a historical place and its physical [location](./geography_location.md) lies with the uncertainty and fuzziness of historical geographical information. A **place** may be known through a [name](./geography_name.md), or through an archaeological [location](./geography_location.md). Maintaining **place**, [name](./geography_name.md), and [location](./geography_location.md) as separate entities within a relational data structure allows for the association of one **place** with none, one, or more than one [location](./geography_location.md) or none, one, or more than one [name](./geography_name.md). It also allows for the qualification of associations between each of these entities with separate levels of relational [certainty](utilities_certainty.md). 

The **place** entity as understood in the present context is largely identical to the [place](https://pleiades.stoa.org/help/conceptual-overview) entity type employed by the [Pleiades: A Gazetteer of Past Places](pleiades.stoa.org) repository. Within this data ontology, a **place** is an entirely abstract, conceptual entity, that can exist in name only (as a place mentioned in an inscription) or in location only (as the archaeological site of an ancient place without a name). Since [connections](https://pleiades.stoa.org/help/conceptual-overview) between **places** are an integral part of the [Pleiades](pleiades.stoa.org) ontology, a **place** can then be located relative to another **place**, without necessitating a geographical **location**.

The stable URI format for **place** records in Pleiades are described in more detail in the [Pleiades documentation](https://pleiades.stoa.org/help/what-are-pleiades-uris). Here, **place** URIs act as a parent identifier to related **name**, **location**, and **connection** records.

In the [Wikidata](https://www.wikidata.org/) ontology, a **place** appears related to a range of different item types, depending on the nature of the particular record. Next to a dedicated item record for the specific place, a **place** may then be an instance of e.g. [Q15661340 ancient city](https://www.wikidata.org/wiki/Q15661340), [Q486972 human settlement](https://www.wikidata.org/wiki/Q486972), or any type more specific to the exact character of the historical place in question.

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
* [Pleiades: A Gazetteer of Past Places](https://pleiades.stoa.org/) is a leading historical geographical database for Classics, but also with an increasing number of records for the Middle East and adjoining regions. The database holds upwards of 35,000 place records.



