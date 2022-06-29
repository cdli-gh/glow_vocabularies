---
layout: default
title: "Geography: Place"
rank: 1
---
# Place
<font size=2>Geography Working Group</font><br>
<font size=1>Rune Rattenborg, Sebastian Borkowski, Manuel Molina, Jamie Novotny, Susanne Rutishauser</font>

## Description
The **place** entity defines _any discrete, historical place_ with which one or more [names](./geography_name.md) or [locations](./geography_location.md) can be associated. A place, as understood in the present context, is then not a geographical, but a conceptual entity.

The basis for conceptually separating a historical place and its physical [location](./geography_location.md) lies with the uncertainty and fuzziness of historical geographical information. A **place** may be known through a [name](./geography_name.md) found in a cuneiform inscription, or through the inferrence of a past settlement from the scientific investigation of an archaeological [location](./geography_location.md). Maintaining **place**, [name](./geography_name.md), and [location](./geography_location.md) as separate entities within a relational data structure allows for the association of one **place** with more than one [location](./geography_location.md) or more than one [name](./geography_name.md), and for the qualification of each association with separate levels of relational [certainty](utilities_certainty.md). 

The **place** entity as understood in the present context is largely identical to the [place](https://pleiades.stoa.org/help/conceptual-overview) entity type employed by the [Pleiades: A Gazetteer of Past Places](pleiades.stoa.org) repository. Within this data ontology, a **place** is an entirely abstract, conceptual entity, that can exist in name only (as a place mentioned in an inscription) or in location only (as the archaeological site of an ancient place without a name). Since [connections](https://pleiades.stoa.org/help/conceptual-overview) between **places** are an integral part of the [Pleiades](pleiades.stoa.org) ontology, a **place** can then be located relative to another **place**, without necessitating a geographical **location**.

## Recommended fields
As an abstract, conceptual entity, a **place** 

name | description
-----|---------------
pleiades_id | Identifier of the corresponding entity record in [Pleiades](pleiades.stoa.org)
wikidata | Identifier of the corresponding entity record in [WikiData](http://wikidata.org)

## Optional fields
name | description
-----|---------------
whg | Identifier of the corresponding entity record in [World History Gazetteer](pleiades.stoa.org)

## Resources



