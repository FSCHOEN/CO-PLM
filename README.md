# CO-PLM
CO-PLM is a core ontology for Product Lifecycle Management (PLM) based on the foundational ontology DOLCE+DnS Ultralite (DUL).
Its design and application is described in the listed publications.

## Repository Content
This repository consists of the following subdirectories.

- *Ontology Patterns:* .owl-files implementing the CO-PLM core ontology
- *Demo Instances*  
	- *Blue Train Instances:* .owl-files containing demo instances of the train model (see Technical Report)
	- *Large Part Numbers:* .owl-files containing synthetic product data with increasing part counts (see Technical Report)

The Technical Report is no longer updated in this repository. See DOI:10.3233/SSW210012 or https://ebooks.iospress.nl/volumearticle/56701 for the most recent published work on CO-PLM<sup>5</sup>.

## Ontology Patterns
CO-PLM consists of multiple ontology patterns, each combining a set of associated concepts.

### Product Part Information Entity Pattern
This is the most fundamental pattern of CO-PLM. It introduces information entities based on DUL.
### Product Part Information Object Pattern
Here, different information objects related to PLM are described.
### Product Part Information Realization Pattern
In this pattern the most common forms of information realizations in PLM context are formalized.
### Product Part Pattern
This pattern distinguishes between Product Part Masters (social objects) and Physical Product Parts (physical objects).

### PLM Workflow Pattern
Importing strukt <sup>2</sup>, this pattern integrates workflows into CO-PLM.

### Access Regulation Rule Pattern
Based on InFo <sup>3</sup>, this pattern allows specifying policies for access regulation in context of PLM.


### References

<sup>1</sup> Gangemi, A. (2016): DOLCE+DnS Ultralite (DUL): ontologydesignpatterns.org. URL: http://ontologydesignpatterns.org/wiki/Ontology:DOLCE+DnS_Ultralite

<sup>2</sup> Scherp, A.; Eißing, D.; Staab, S. (2011): strukt - A Pattern System for Integrating Individual and Organizational Knowledge Work: ISWC 2011, pp. 569-584. Springer, Berlin, Heidelberg.

<sup>3</sup> Kasten, A.; Scherp, A. (2015): Ontology-Based Information Flow Control of Network-Level Internet Communication. In: IJSC 9 (01) 2015, pp. 1–45.

### Publications
<sup>4</sup>Falko Schoenteich, Andreas Kasten, and Ansgar Scherp. A Pattern-Based Core Ontology for Product Lifecycle Management based on
DUL. In Workshop on Ontoloty Design and Patterns (WOP) colocated at International Semantic Web Coference (ISWC), CEUR Workshop
Proceedings. CEUR-WS.org, 2018

<sup>5</sup>Falko Schoenteich, Andreas Kasten, and Ansgar Scherp. Secure Product Lifecycle Management with CO-PLM. In Advances in Pattern based
Ontology Engineering. IOS Press, 2021