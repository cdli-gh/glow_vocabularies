---
layout: default
title: "Chronology: Period"
rank: 5
---

# Period
Chronology Working Group 
<font size=1>Émilie Pagé-Perron, Jamie Novotny, Heather Baker, Bertrand Lafont, Damien Agut-Labordere, Bruno Gombert, Mirko Novak, and David Danzig</font>  

## 
      
## Description
A period entity includes a conceptual definition of a relatively well-defined cultural or historical complex with an approximate chronological timespan and an approximate geographical extent.   
  
A period is a conceptual entity associating a relatively well-defined cultural or historical complex with an approximate chronological timespan and an approximate geographical extent. The name of the cultural or historical complex is typically derived from specialist nomenclature in fields such as philology, archaeology, or history, the temporal duration of which can be defined approximately defined as spanning one to several centuries, sometimes also millennia. Since a period is typically defined with reference to a specific cultural complex, it also implies a finite geographical extent, typically including a relatively well-established, if geographically fuzzy historical region. As such, a period constitutes an easy means for the approximate chronological and geographical location of an object or an event. The more accurate definition of this location, however, is dependent to a large extent on the intellectual premises that underlie the definition of the period in spatial and temporal terms, namely according to what criteria the chronological timespan and the geographical extent are defined.
  
## Recommended fields
There is only one field for this entity type.  
  
Virtually all projects within the disciplinary domain of Assyriology employ variations of the standard CDLI period set (see above, 5). Records in this period set consist of a single text string containing a period label followed by a year range with starting year and ending year in parentheses, e.g. ‘Ur III (2100-2000 BCE)’. Some projects, e.g. on ORACC, employ truncated versions of these strings (at least in their public interfaces), typically leaving out the year range, or employ new values by merging two or more standard values in order to account for temporal uncertainty or longer timespans (e.g. ‘Old Akkadian; Ur III’).

## Optional fields
The table below provides an overview of recommended basic attributes. It should be noted that PeriodO offers a well-defined ontology and vocabularies for most of these, see [PeriodO – Technical Overview](https://perio.do/technical-overview/).

| attribute    | type     | comments                                                                                                       |
|--------------|----------|----------------------------------------------------------------------------------------------------------------|
| id           | integer  | record identifer                                                                                               |
| period_label | string   | name of period                                                                                                 |
| start_y      | integer  | earliest year of period                                                                                        |
| end_y        | integer  | latest year of period                                                                                          |
| extent       | geometry | polygon of surface extent in WGS84, alternatively linked ID to corresponding PeriodO record                    |
| notes        | string   | commentary field                                                                                               |
| chronology   | string   | absolute chronological framework to which start_y and end_y are related, for example Middle or Low Chronology. |

## Resources
There are several digital indices available already that should be used or augmented rather than relying on print resources. For periods used for cuneiform inscriptions and related artefacts in the Cuneiform Digital Library Initiative, Open Richly Annotated Cuneiform Corpus and others, see:

- https://cdli.ox.ac.uk/wiki/doku.php?id=adopted_periodisation_in_cdli
- https://cdli.mpiwg-berlin.mpg.de/periods
  
For archaeological and historical periods relating to the Middle East more generally, see:
- https://client.perio.do/   
Note, however, that this resource do not currently include much in the way of up-to-date period sets for the cuneiform world.

*- Rune Rattenborg*
