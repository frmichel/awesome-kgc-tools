# Awesome KGC Tools

Links and description of Knowledge Graphs Construction Tools

## KGC Materializers
* [Morph-KGC](https://github.com/oeg-upm/morph-kgc) - R2RML and RML processor to generate RDF knowledge graphs from heterogeneous data sources at scale.
* [Chimera](https://github.com/cefriel/chimera) - Framework based on Apache Camel to define composable semantic data transformation pipelines (lifting/lowering to/from RDF)
* [RMLMapper](https://github.com/RMLio/rmlmapper-java/) - The RMLMapper executes RML rules to generate high quality Linked Data from multiple originally (semi-)structured data sources 
* [RMLStreamer](https://github.com/RMLio/RMLStreamer/) - The RMLStreamer executes RML rules to generate high quality Linked Data from multiple originally (semi-)structured data sources in a streaming way. 
* [xls2rdf](https://github.com/sparna-git/xls2rdf) - converts Excel files containing a "magic line" into RDF.

## KGC Virtualizers
* [Ontop](https://github.com/ontop/ontop) - Ontop is a platform to query relational databases as Virtual RDF Graphs using SPARQL (R2RML)

## KGC Pre-processors
* [MEL](https://w3id.org/kgcp/MEL-TNNT/) - (*Metadata Extractor & Loader*) - A tool to extract metadata (and textual content) from various file formats, as JSON objects.
* [FunMap](https://github.com/SDM-TIB/FunMap) - Efficient preprocessing of transformation rules described in RML+FnO mappings.

## NLP for KGC
* [TNNT](https://w3id.org/kgcp/MEL-TNNT/) - (*The NLP/NER Toolkit*) - A tool that automates the extraction of categorised named entities from the unstructured information encoded in the source documents, using diverse NLP tools and NER models.

## Mapping specifications
* [RML](https://rml.io/specs/rml/) - The RDF Mapping language (RML) is a mapping language defined to express customized mapping rules from heterogeneous data structures and serializations to the RDF data model. 
* [Target in RML](https://rml.io/specs/rml-target/) - Alignment between RML and Target to describe how your knowledge graph should be exported to one or multiple targets.
* [DataIO](https://rml.io/specs/dataio/) - Target, a formal model and a common representation for specifying how a Knowledge Graph should be exported to a given target
* [FnO](https://fno.io/spec/) - Function Ontology (FnO), a way to semantically declare and describe implementation-independent functions, and their relations to related concepts such as parameters, outputs, related problems, algorithms, mappings to concrete implementations, and executions.
* [YARRRML](https://rml.io/yarrrml/spec/) - YARRRML is a human readable text-based representation for declarative generation rules.
* [J2RM](https://w3id.org/kgcp/J2RM/) - J2RM mappings and its engine compose a tool to process mappings from JSON data to RDF triples guided by an OWL2 ontology structure.
* [xls2rdf](https://skos-play.sparna.fr/play/convert?lang=en#documentation) - The documentation for the "magic line" of the xls2rdf converter.

## Mapping Editors
* [Mapeathor](https://morph.oeg.fi.upm.es/tool/mapeathor) - Definition of Excel-based mappings and translation to [R2]RML mappings.
* [Matey](https://rml.io/yarrrrml/matey/) - Matey is a web based editor for YARRRML rules.
* [RMLEditor](https://github.com/RMLio/rmleditor-ce) - RMLEditor offers a Graphical User Interface to enable data publishers, who are domain experts, to model knowledge derived from heterogeneous distributed data.
* [RMLx Visual Editor](https://pebbie.org/mashup/rml) - A web based editor for RML rules. 
* [Square](https://square.semvis.pl/projects) - SPARQL Queries and R2RML mappings Environment
* [Map-On](https://github.com/arc-lasalle/Map-On) - A web-based editor for visual ontology mapping for R2RML documents (DEPRECATED)

## KGC Pipelines
* [KGCP](http://w3id.org/kgcp/) - "_KG Construction Pipeline_" - A suite of software artifacts to automate the creation of KGs from heterogeneous data sources.
