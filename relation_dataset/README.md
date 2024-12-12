## Relation Dataset

The .csv file contains all the PERSON-PLACE relations manually gathered from the input texts. It also contains geographic information on the included spatial entities. This geographic information is gathered from a mixture of [GeoNames](https://www.geonames.org/), [OpenStreetMap](https://www.openstreetmap.org), [Wikipedia](https://www.wikipedia.org/).


### Column Overview

| Column | Description |
|----------------------------------------|------------------|
|Place| Mask number(s) associated with PLACE entity/-ies in relation.|
|Relation Type| Type of the relation.|
|Context| List of words linking PERSON and PLACE entities.|
|Date| Mask number associated with DATE entity. (optional)|
|Sentence| Sentence number(s) in which the relation is found.|
|Sentence_Text| Marked up sentence text. Not coreferenced.|
|Sentence_Text_Cleaned| Sentence_Text without mark up.|
|Place_Text| Plain text of the PLACE entity/-ies.|
|Date_Text| Plain text of the DATE entity. (optional)|
|slug| Name of main person of the article written in slug style.|
|Notes| Any remarks about relation.|
|Place_Info| A JSON list of geographic information objects for each spatial entity. Includes coordinates and GeoNames description.|
|sentence_doc| Sentence object from spaCy NLP pipeline.|