---
layout: default
title: "Bibliography - publication"
rank: 1
---

## Bibliography: publication

<font size=2>Bibliography Working Group</font><br/><font size=1>Manuel Molina (BDTNS), Wiebke Meinhold (Keibi), Georg Neumann (Keibi), Michaela Weszeli (Register Assyriologie), Adam Anderson (dubsar)

… </font>

## Description
The **publication** entity defines the features of any publication of a cuneiform artifact, which may act as a type of primary source publication. Secondary source references to cuneiform tablets, such as sign readings, translations, etc. will be dealt with in the Bibliography Reference Markdown. As included in digital catalogues in cuneiform studies, the publications feature consists of a standardized citation which typically includes: author, title, date, and other publication information for an artifact with a cuneiform inscription. For an example of these standardized citations found in bibliography **publication** entities as employed in digital catalogues in cuneiform studies, see the [CDLI](https://cdli.ox.ac.uk/wiki/abbreviations_for_assyriology) and the [Keilschrift Bibliographie](https://vergil.uni-tuebingen.de/keibi/index.php?r=volume/list). 

## Recommended fields
As a **publication** may contain multiple entity types, we utilize the fields from [Dublin Core](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#terms-bibliographicCitation) and [MARC](https://www.loc.gov/marc/umb/um01to06.html) standards. A **publication** should always include an **author** of the work, along with a **title** and **year** in which the work was published. 

name | description
-----|---------------
author | Last name, First name and/or initials (L, F) of the author of the publication
title | title information (which includes the title, subtitle, and other title information) of the publication
publication | publication information (which includes the title of the journal or book series)
publisher | name of the insitution or company who published the work
series | numeric series statement for book series if appropriate
vol | volume number if appropriate
issue | issue number if appropriate
pages | page numbers cited if appropriate (which may include chapter number, plate number, etc.)
add_PN | additional personal name entry (e.g. joint author, editor, or illustrator)
year | year (YYYY) of the publication
place | place of publication
lang | language ([ISO](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)) or languages of the publication

Example publication field:
name | value
-----|---------------
author | Abusch, Tzvi
title | Notes on a Pair of Matching Texts: A Shepherd’s Bulla and an Owner’s Receipt
publication | In Honor of Ernest R. Lacheman on His Seventy-fifth Birthday, April 29, 1981
publisher | Eisenbrauns
series | SCCNH
vol | 1
issue | Not applicable
pages | 1-9
add_PN | Not applicable
year | 1981
place | Winona Lake
lang | en

Linking the **publication** record to a corresponding **wikidata** identifier will also establish a link to all associated identifiers included by WikiData. As such, a WikiData identifier will usually link to corresponding identifiers from Wikipedia, Wikisources, Wikibooks, etc.

## Optional fields

name | description
-----|--------------
wikidata | Identifiers for the corresponding wikidata item ([Q-id](https://www.wikidata.org/wiki/Q43649390)), property ([P-id](https://www.wikidata.org/wiki/Q18616576)), or lexeme ([L-id](https://www.wikidata.org/wiki/Q51885771))
URL | Uniform Resource Locator ([URL](https://en.wikipedia.org/wiki/URL)) of the specific web page where the referenced content can be found
ISBN | International Standard Book Number (ISBN)
DOI | Digital Object Identifier ([DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)) for the publication
ORCID | Unique identifier for authors ([ORCID](https://info.orcid.org/documentation/))
LCCN | Library of Congress Control Number ([LCCN](https://en.wikipedia.org/w/index.php?title=Library_of_Congress_Control_Number&oldid=1078490046))
subj | topical [subject](https://en.wikipedia.org/wiki/Subject_(documents)) heading
edition | edition number, if not the first edition
month | month of publication for journal articles
note | annotation or summary note

## Resources
* For an updated index of Assyriology abbreviations used in citing primary publications of cuneiform texts, see the [Abbreviations for Assyriology](https://cdli.ox.ac.uk/wiki/abbreviations_for_assyriology)

* For examples of citations for publication types, see [Wikipedia Citing Sources](https://en.wikipedia.org/wiki/Wikipedia:Citing_sources#Examples)

* For citation formatting, see [Wikipedia Manual of Style](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style)

* For a list of metadata terms in Dublin Core, see [DCMI Metadata Terms](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#terms-bibliographicCitation) 

* For a general introduction to MARC, see [What is a MARC record and why is it important?](https://www.loc.gov/marc/umb/um01to06.html)
