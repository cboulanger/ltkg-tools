# Legal Theory Knowledge Graph Project - Tools and Resources
[![DOI](https://zenodo.org/badge/770897493.svg)](https://zenodo.org/doi/10.5281/zenodo.10809341)

Christian Boulanger

Last updated: 2024/03/12

The following links point to resources collected during the exploratory phase of the [Legal Theory Graph Project at the Max Planck Institute for Legal History and Legal Theory](https://www.lhlt.mpg.de/2514927/03-boulanger-legal-theory-graph). This is _not_ a comprehensive list of available resources or scholarship, but a selection based on the needs of the project and personal preferences. Most of the research for this list was done in 2021-2023, prior to the release of ChatGPT and other major language models that have revolutionized the NLP technology landscape. While some aspects of these newer developments have been incorporated, the list mostly reflects the pre-LLM state of the art.

The list differentiates between
1. **Graph Technologies** in general, wich refer to standards and tools for collecting, editing, and presenting (visualizing) graph data;
2. **Knowledge Organizing Systems** (KOS), which provide standards for the dissemination and reuse of information;
3. **Data Sources** : metadata providers and source data from which metadata for node and edge data can be imported;
4. **Corpus Lingustic Technologies** which serve to quantatively analyze full texts and can generate node and edge data from text corpora;
5. **Bibliometry/Citation Analysis** which specifically deals with citations as research data, often using a graph

## Table of Contents

- [1\. Graph Technologies](#1-Graph-Technologies "1. Graph Technologies")
  - [Scholarship](#Scholarship "Scholarship")
  - [Projects/Services with similar/related goals](#ProjectsServices-with-similarrelated-goals "Projects/Services with similar/related goals")
  - [Projects/Services using Graph Technologies/Linked Data](#ProjectsServices-using-Graph-TechnologiesLinked-Data "Projects/Services using Graph Technologies/Linked Data")
  - [Public knowledge graph / linked data repositories, data sources & services](#Public-knowledge-graph--linked-data-repositories-data-sources-amp-services "Public knowledge graph / linked data repositories, data sources & services")
  - [Tools/Software](#ToolsSoftware "Tools/Software")
  - [Stores for non graph-specific metadata](#Stores-for-non-graph-specific-metadata "Stores for non graph-specific metadata")
- [2\. Knowledge Organizing Systems (KOS) / Semantic Web](#2-Knowledge-Organizing-Systems-KOS--Semantic-Web "2. Knowledge Organizing Systems (KOS) / Semantic Web")
  - [Theory](#Theory "Theory")
  - [Organizations](#Organizations "Organizations")
  - [Implementation languages](#Implementation-languages "Implementation languages")
  - [Standardization hubs/initiatives/tools](#Standardization-hubsinitiativestools "Standardization hubs/initiatives/tools")
  - [Specialized Ontologies / Vocabularies / Taxonomies for producing semantic metadata](#Specialized-Ontologies--Vocabularies--Taxonomies-for-producing-semantic-metadata "Specialized Ontologies / Vocabularies / Taxonomies for producing semantic metadata")
  - [Software tools](#Software-tools "Software tools")
- [3\. Metadata retrieval and generation](#3-Metadata-retrieval-and-generation "3. Metadata retrieval and generation")
  - [Metadata providers (with Web API)](#Metadata-providers-with-Web-API "Metadata providers (with Web API)")
  - [Metadata extraction](#Metadata-extraction "Metadata extraction")
- [4\. Corpus Linguistics](#4-Corpus-Linguistics "4. Corpus Linguistics")
  - [General issues](#General-issues "General issues")
  - [Creation & Analysis of Text Corpora](#Creation-amp-Analysis-of-Text-Corpora "Creation & Analysis of Text Corpora")
  - [Text mining](#Text-mining "Text mining")
  - [NLP tasks/problems](#NLP-tasksproblems "NLP tasks/problems")
  - [Text annotation for machine learning](#Text-annotation-for-machine-learning "Text annotation for machine learning")
  - [Possibly relevant corpora](#Possibly-relevant-corpora "Possibly relevant corpora")
- [5\. Bibliometrics / Citation Analysis](#5-Bibliometrics--Citation-Analysis "5. Bibliometrics / Citation Analysis")
  - [Initiatives](#Initiatives "Initiatives")
  - [Research graphs web services](#Research-graphs-web-services "Research graphs web services")
  - [Scholarship](#Scholarship1 "Scholarship")
  - [Automatic article corpus aggregation](#Automatic-article-corpus-aggregation "Automatic article corpus aggregation")
  - [Metadata extraction/annotation software and services](#Metadata-extractionannotation-software-and-services "Metadata extraction/annotation software and services")
  - [Data exchange formats](#Data-exchange-formats "Data exchange formats")
  - [Matching/normalization of citations](#Matchingnormalization-of-citations "Matching/normalization of citations")
  - [Applications for data analysis](#Applications-for-data-analysis "Applications for data analysis")
  - [Multi-purpose libraries](#Multi-purpose-libraries "Multi-purpose libraries")


See also:

- [Frey-Endres/Simon, 2021, Digitale Werkzeuge zur textbasierten Annotation, Korpusanalyse und Netzwerkanalyse in den Geisteswissenschaften](https://tuprints.ulb.tu-darmstadt.de/17850/1/Digital_Philology__Working_Papers_in_Digital_Philology_vol002.pdf)- comprehensive German language description of available tools, much more detailed and more general purpose
- [Bibliography on Digital Research in Law](https://www.zotero.org/groups/4370759/computational_sociolegal_and_historical_legal_studies): A Zotero group, still under development
- Discover research tools for studying texts https://tapor.ca/home
- Awesome DHTools
  https://dh-tech.github.io/awesome-digital-humanities/

## 1. Graph Technologies

### Scholarship

- **Bibliographies**
  - https://graphentechnologien.hypotheses.org/bibliographie
  - https://www.zotero.org/groups/2224334/ag_graph/library
  - http://historicalnetworkresearch.org/bibliography/#top

- **Graphentechnologien in den Digitalen Geisteswissenschaften**
  http://doi.org/10.1515/abitech-2017-0042

- **ZfdG** - Zeitschrift für digitale Geisteswissenschaften
  https://zfdg.de

### Projects/Services with similar/related goals

Of interest are projects that cover the humanities/social sciences and which generate citation and/or other graph data (including German language scholarship)

- **Linked Open Citation Database**: Development of a Linked Open Data database for the indexing of citations of electronic and print media
  <https://locdb.bib.uni-mannheim.de/blog/en/>

- **EXCITE/OUTCITE**: aims to extract citations from social science publications and to make more citation data available to researchers
  <https://excite.informatik.uni-stuttgart.de>

- **GEOCITE**: Monitoring-Tool zur Wissenschaftsbeobachtung, based on EXCITE
  https://geographische-netzwerkstatt.uni-passau.de/de/geocite

- **Scholia** is a service that creates visual scholarly profiles for topics, people, organizations, species, chemicals, etc using bibliographic and other information in Wikidata.
  <https://scholia.toolforge.org>

- **PhiWiki** ist eine sich in der Entwicklung befindliche Software-Anwendung, die es zunächst Philosoph:innen, prinzipiell aber auch anderen Geisteswissenschaftler:innen, ermöglichen soll, Daten zu den Ideen und Begriffen ihrer Disziplin semantisch zu erfassen und neue Verbindungen innerhalb dieser Daten zu entdecken
  https://zenodo.org/records/8386456

### Public knowledge graph / linked data repositories, data sources & services

- **Wikidata**
  <https://www.wikidata.org/wiki/Wikidata:Introduction>
- 
- **Open Research Knowledge Graph**
  <https://projects.tib.eu/orkg>
  <https://gitlab.com/TIBHannover/orkg>

- **OpenAIRE Research Graph**
  <https://graph.openaire.eu/about>

- **Druid, the place to store, share and query Linked Data**
  <https://druid.datalegend.net>

- **Histograph**: Graph-based exploration and crowd-based indexation for multimedia collections
  <http://histograph.eu>

- **DBpedia**: extracts structured content from Wikimedia projects as an open knowledge graph
  <https://www.dbpedia.org/about>

- **Palladio**: Visualization of complex historical data
  <https://hdlab.stanford.edu/palladio>

- **Geovistory Toolbox**: Store, visualize and share historical and geographical data  
  <https://www.geovistory.com>

- **FRED**: web service & API that automatically extracts rich and highly connected linked data from a text
  <http://wit.istc.cnr.it/stlab-tools/fred/>

- **Open Knowledge Maps**: A visual interface to the world's scientific knowledge
  https://openknowledgemaps.org/


### Tools/Software

For tools for scientometric/bibliometric graph data, see [section on general bibliometric technologies](#5-Bibliometrics--Citation-Analysis)

#### Overviews and comparisons

- Besta et al. (2021) Demystifying Graph Databases: Analysis and Taxonomy of Data Organization, System Designs, and Graph Queries
  https://arxiv.org/abs/1910.09017

- Elise Devaux (2019) List of free graph visualization applications
  https://elise-deux.medium.com/list-of-free-graph-visualization-applications-9c4ff5c1b3cd

- Elise Devaux (2019) List of graph visualization libraries
  https://elise-deux.medium.com/the-list-of-graph-visualization-libraries-7a7b89aab6a6


#### Graph databases, editors, stores, analysis & visualization

- **Neo4j Desktop** for graph data & queries (Commercial with community edition)
  <https://www.neo4j.com>
  - Connection to R/RStudio <https://github.com/neo4j-rstats/neo4r>
  - Visualization libraries:
      - https://neo4j.com/developer/tools-graph-visualization/
      - https://github.com/neo4j-contrib/neovis.js/

- **Open Native Graph Database**: An Open Source fork of Neo4J
  <https://www.graphfoundation.org/>

- **GraphStack**: Builds on ONgDB to provide enterprise solutions
  <https://graphstack.io/>

- **Cayley Graph Database** (Open Source)
  <https://cayley.gitbook.io>

- **NodeGoat**: a web-based research environment for the humanities
  <https://nodegoat.net>

- **VIVO**: creates a knowledge graph of the scholarly work of an organization
  <https://duraspace.org/vivo/>

#### Visualization software/platforms

- **Gephi**: Open Graph Vizualization
  https://gephi.org/

- **Cytoscape**: open source software platform for complex network analysis and visualization (originally designed for biological research).
  https://cytoscape.org/

- **ArcadeDB**: Open Source Graph Visualization Tool. Integrates  with Neo4j
  https://arcadedb.com/analytics

- **Constellation**: free open source software for data visualisation & analytics
  https://www.constellation-app.com/

- **Graph Commons**: Transform your data into interactive maps (freemium)
  https://graphcommons.com/

- **GraphVis**: platform for interactive visual graph mining and relational learning.
  https://networkrepository.com/graphvis.php

- **GrapViz**: graph visualization software based on a graph representation language (DOT).
  <https://graphviz.org/>
  - https://www.tonyballantyne.com/graphs.html

- **GUESS**: exploratory data analysis and visualization tool for graphs and networks.
  http://graphexploration.cond.org

- **Apache Zeppelin**: Web-based notebook that enables data-driven,
  interactive data analytics and collaborative documents with SQL, Scala, Python, R and more

- **draw.io** Online Graph Editor (auch als Offline-App)
  https://www.diagrams.net/
  https://github.com/jgraph/drawio-desktop/

#### Methodological questions

##### Community detection

- https://www.r-bloggers.com/2020/03/community-detection-with-louvain-and-infomap/

##### Temporality

- https://kateto.net/polnet2017.html (scroll down to "7.2 Network evolution animations")
- https://github.com/michalgm/ndtv-d3/blob/master/README.md
- https://cran.r-project.org/web/packages/networkDynamic/vignettes/networkDynamic.pdf

#### Software libraries/APIs

- **igraph**: a collection of network analysis tools for R, Python and C
  <https://igraph.org>

##### Python

- **NetworkX**: Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks
  https://networkx.org/

- **graph-tool**: Python package for network analysis and visualization with C++ backend <https://graph-tool.skewed.de/>

- **WebWeb**: tool for creating, displaying, and sharing interactive network visualizations on the web
  https://webwebpage.github.io/

- **openmappr**: visually browse and discover patterns in networks
  https://www.openmappr.org

- **pyvis**
  https://pyvis.readthedocs.io

  - https://www.askpython.com/python/examples/customizing-pyvis-interactive-network-graphs

- **ipycytoscape**
  https://blog.jupyter.org/interactive-graph-visualization-in-jupyter-with-ipycytoscape-a8828a54ab63

##### JavaScript

- **D3**: JavaScript library for manipulating documents based on data, useful for graph visualization
  https://d3js.org/

- **vis.js community edition**: A dynamic, browser based visualization library.
  https://visjs.org/
  - https://visjs.github.io/vis-network/examples/

- **Dracula.js** is a set of tools to display and layout interactive connected graphs and networks, along with various related algorithms from the field of graph theory.
  https://www.graphdracula.net/

- **Cytoscape.js**: Javascript visualization of Cytoscape data
  https://js.cytoscape.org/

- **sigma.js**: a JavaScript library aimed at visualizing graphs of thousands of nodes and edges
  https://www.sigmajs.org/

- **ccNetViz**: is a lightweight, high-performance javascript library for large network graphs (see graph theory) visualization using WebGL
  https://helikarlab.github.io/ccNetViz/

##### R

- https://datastorm-open.github.io/visNetwork/
- https://briatte.github.io/ggnet/
- https://mr.schochastics.net/material/netVizR/
- https://r-graph-gallery.com/network.html
- https://r-graph-gallery.com/network-interactive.html
- https://www.r-bloggers.com/2019/06/interactive-network-visualization-with-r/
  - https://r-graph-gallery.com/257-input-formats-for-network-charts.html
  - https://www.statworx.com/en/content-hub/blog/interactive-network-visualization-with-r/
- https://github.com/michalgm/ndtv-d3/blob/master/README.md


##### Java

- **Apache Jena**: A free and open source Java framework for building Semantic Web and Linked Data applications
  https://jena.apache.org

### Stores for non graph-specific metadata

The following list is specific to this project, not an exhaustive overview.

- **Zotero**: app for managing bibliographic data, nice UI + Web API, slow, poor query features
  https://www.zotero.org
  - Web API/Clients
      https://www.zotero.org/support/dev/web_api/v3/start
  - ZotPrime: a fully packaged on-premise solution:
      <https://github.com/ZotPrime/zotprime>
  - Cita: a Wikidata addon for Zotero with citations metadata support
      <https://github.com/diegodlh/zotero-cita>

- **Endatabas**: Open Source SQL Document Database with Full History, allowing to record data change over time. Still in beta
  https://www.endatabas.com/

- **Couchbase**: JSON document database: excellent query support, many clients
  https://docs.couchbase.com/tutorials/getting-started-ce/install-manage/tutorial_en.html
  - Couchbase Store for @retorquere/zotero-sync
      https://github.com/cboulanger/zotero-sync-couchbase



## 2. Knowledge Organizing Systems (KOS) / Semantic Web

### Theory

- [Lists, Taxonomies, Lattices, Thesauri and Ontologies: Paving a Pathway Through a Terminological Jungle](https://www.ergon-verlag.de/isko_ko/downloads/ko_41_2014_3_d.pdf)
- [Ontologies (as knowledge organization systems)](https://www.isko.org/cyclo/ontologies)

### Organizations

- Kompetenzzentrum Interoperable Metadaten (KIM)
  https://dini.de/standards

### Implementation languages

- **Resource Description Framework (RDF)**
  <https://www.w3.org/TR/rdf-concepts/>
  <https://www.w3.org/OWL/>

- **Terse RDF Triple Language**, a concrete syntax for RDF
  <https://www.w3.org/TR/turtle/>

- **Web Ontology Language (OWL)**
  <https://www.w3.org/TR/owl-ref/>

- **Shapes Constraint Language (SHACL)**: validation of RDF ontologies
  <https://www.w3.org/TR/shacl/>

- **Simple Knowledge Organization System (SKOS)**
  https://www.w3.org/2009/08/skos-reference/skos.html
  https://www.w3.org/2006/07/SWD/SKOS/skos-and-owl/master.html
  https://www.w3.org/2004/02/skos/vocabs

### Standardization hubs/initiatives/tools

- **SkoHub**: KOS-based content subscription (for structural metadata such as taxonomies)
  <https://skohub.io>

- **RDA Registry**: contains vocabularies that represent the RDA entities, elements, and controlled terminologies
  <http://www.rdaregistry.info>

- **Dariah Vocabs Services**
  <https://vocabs.dariah.eu/en/>

-  **Standardization Survival Kit**: A collection of research use case scenarios illustrating best practices in Digital Humanities and Heritage research
   <http://ssk.huma-num.fr>

- **PARTHENOS Virtual Research Environment**: integrates cloud storage with services and tools for Digital Humanities
  <https://parthenos.d4science.org/web/parthenos_vre>
  - [Training Suite](https://training.parthenos-project.eu): provides training modules and resources in DH

- **Linked Pipes**: Registry of web-based linked data services based on WikiData
  <http://linkedpipes.xyz/>

### Specialized Ontologies / Vocabularies / Taxonomies for producing semantic metadata

- Example from legal history: Regulatory Matters of Police Ordinances
  https://github.com/rg-mpg-de/vocabs-polmat

#### Bibliographic Data

- **The Bibliographic ontology (BIBO)**
  https://bibliontology.com/

- **FRBR-aligned Bibliographic Ontology (FaBiO)**
  http://www.sparontologies.net/ontologies/fabio#fabio_3

- **Comparison of FaBiO and BIBO**
  https://opencitations.wordpress.com/2011/06/29/comparison-of-bibo-and-fabio/

- **Categorising bibliographic resources with FaBiO and SKOS**
  https://opencitations.wordpress.com/2011/06/29/categorising-bibliographic-resources-with-fabio-and-skos/

- **BIBO2SPAR**: RDF Mapping of BIBO to the SPAR Ontologies
  https://opencitations.wordpress.com/2011/06/29/bibo2spar-an-rdf-mapping-of-bibo-to-the-spar-ontologies/

- **Citation Typing Ontology (CiTO)**
  https://sparontologies.github.io/cito/current/cito.html

- **OpenCitations Data Model** (referencing many pertinent ontologies)
  https://opencitations.net/model
  [article (2020)](https://doi.org/10.1007/978-3-030-62466-8_28)\]

- **Web of Science**
  https://images.webofknowledge.com/images/help/WOS/hs_wos_fieldtags.html

#### Scholars

- **GND Ontology**
  <https://d-nb.info/standards/elementset/gnd> ([WebVOWL](http://visualdataweb.de/webvowl/#iri=https://d-nb.info/standards/elementset/gnd_20191015.rdf))

- **Scholarly Ontology**
  https://scholarlyontology.herokuapp.com/

- FOAF ontology
  http://xmlns.com/foaf/spec/

- SCoRO, the Scholarly Contributions and Roles Ontology
  https://sparontologies.github.io/scoro/current/scoro.html

- RELATIONSHIP: A vocabulary for describing relationships between people
  https://vocab.org/relationship/

- BIO: A vocabulary for biographical information
  <https://vocab.org/bio/>

#### Organizations

- The Organization Ontology
  https://www.w3.org/TR/vocab-org

### Software tools

#### Web-based

- Skosmos: Open source web-based SKOS browser and publishing tool
  <http://skosmos.org/> ([Demo](http://skosmos.dev.finto.fi/en/))

- DARIAH Vocabs Editor <https://github.com/acdh-oeaw/vocabseditor>

- DARIAH Vocabs API Server <https://vocabs-api.acdh.oeaw.ac.at/>

- Mobi: platform which links native data sources into a knowledge graph, features Ontology editor
  <https://mobi.inovexcorp.com/docs>

- Vitro: Vitro is a general-purpose web-based ontology and instance editor with customizable public     browsing, part of VEVO
  <https://github.com/vivo-project/Vitro>

- WebVOWL: Web-based Visualization of Ontologies
  <http://vowl.visualdataweb.org/webvowl.html>  ([Example](http://visualdataweb.de/webvowl/#iri=https://raw.githubusercontent.com/athenarc/scholarly-ontology/main/ScholarlyOntology_Schema_and_ActyivityTypes_v1.3.owl))

- RDFShape: web service offering RDF format conversion, validation, querying and OWL inference
  <https://rdfshape.weso.es/>

#### Desktop Applications

- RDF Studio: RDF Vocabulary Writer For Windows
  http://www.linkeddatatools.com/rdf-studio

- Protégé Ontology Editor
  https://protegeproject.github.io/protege/


#### Libraries/Specifications/Tools

- Linked Data
  https://github.com/digitalbazaar/jsonld.js

- Graphical Framework for OWL Ontologies
  https://essepuntato.it/graffoo/
  https://essepuntato.it/graffoo/specification/

- Turtle Editors (Online/Desktop)
  https://marketplace.visualstudio.com/items?itemName=markstoehr.skos-ttl-editor
  https://perfectkb.github.io/yate/
  http://onto.fel.cvut.cz/turtle-editor/turtle-editor.html

- Ontologics: R package to handle Ontologies
  https://cran.r-project.org/web/packages/ontologics

## 3. Metadata retrieval and generation

### Metadata providers (with Web API)

#### General

- **Wikidata**: a free, collaborative, multilingual, secondary database, collecting structured data to provide support for Wikipedia, Wikimedia Commons, the other wikis of the Wikimedia movement, and to anyone in the world.
  <https://www.wikidata.org>

  - [Introduction](https://www.wikidata.org/wiki/Wikidata:Introduction)
  - **Projects/Initiatives**:
      - [WikiProject Source Metadata](https://www.wikidata.org/wiki/Wikidata:WikiProject_Source_MetaData)
      - [WikiCite intiative](https://meta.wikimedia.org/wiki/WikiCite)
        - [Roadmap (& scaling prolems)](https://www.wikidata.org/wiki/Wikidata:WikiCite/Roadmap)
      - [LD4 Wikidata Affinity Group](https://www.wikidata.org/wiki/Wikidata:WikiProject_LD4_Wikidata_Affinity_Group)

- **API clients/Tools**:
  Programmatic WikiData edits should be made with a bot account, see https://www.wikidata.org/wiki/Wikidata:Bots
  - CLI:
      - https://github.com/maxlath/wikibase-cli
  - Python:
      - https://github.com/LeMyst/WikibaseIntegrator
      - https://github.com/SuLab/WikidataIntegrator
      - https://github.com/andrewtavis/wikirepo
  - JavaScript/NodeJS
      - https://github.com/maxlath/wikibase-sdk
      - https://github.com/maxlath/wikibase-edit
  - R:
      - https://github.com/TS404/WikidataR
  - Ruby:
      - https://github.com/wilg/wikidata

- **Data model**:
  - [Bibliographic Properties](https://www.wikidata.org/wiki/Template:Bibliographic_properties)
  - [Property "cites work"](https://www.wikidata.org/wiki/Property_talk:P2860)

- **OpenAlex**: An open and comprehensive catalog of scholarly papers, authors, institutions, and more
  https://docs.openalex.org/api

- **OpenAire Knowledge Graph**: maps the Scholarly Communication Knowledge Model: collection of interlinked descriptions of concepts, entities, relationships and events
  https://graph.openaire.eu/what-is-the-openaire-graph

- **SemOpenAlex**: Scholarly knowledge graph with over 26 billion RDF triples built upon OpenAlex:
  https://semopenalex.org

- **The General Index**:
  - https://archive.org/details/GeneralIndex
  - https://www.nature.com/articles/d41586-019-02142-1

#### Articles / Citations / Bibliometric data

- **OpenAlex**: An open and comprehensive catalog of scholarly papers, authors, institutions, and more
  https://docs.openalex.org/api

- **Semantic Scholar**: A free, AI-powered research tool for scientific literature
  - API: https://www.semanticscholar.org/product/api#Documentation
  - Snapshot: https://api.semanticscholar.org/corpus

- **Open Academic Graph**: large knowledge graph unifying two billion-scale academic graphs: Microsoft Academic Graph (MAG) and AMiner (large snapshot, no API)
  https://www.aminer.cn/oag

- **OpenCitations**
  <https://opencitations.net>
  - [API](https://opencitations.net/index/api/v1)
  - [Article (2020)](https://doi.org/10.1162/qss_a_00023)
  - Initiative for Open Citations
      <https://i4oc.org/>
  - CROCI, the Croudsourced Open Citations Index (for items with DOI)
      https://opencitations.net/index/croci

- **CrossRef**
  https://www.crossref.org
  - [API](https://www.crossref.org/education/retrieve-metadata/rest-api/)
  - [NodeJS API Client](https://www.npmjs.com/package/crossref)
  - [SimpleTextQuery](https://doi.crossref.org/simpleTextQuery)

- **Unpaywall**: An open database of free scholarly articles
  - API: https://unpaywall.org/products/api
  - Python client: https://pypi.org/project/unpywall/

- **Internet Archive Scholar**
  <https://scholar.archive.org/>

  - **Fatcat**: a scalable, versioned, API-oriented catalog of bibliographic entities and file metadata.
      <https://api.fatcat.wiki/redoc>

  - **Refcat**, the Internet Archive Scholar Scholar Index
      - Info: <http://blog.archive.org/2021/10/19/internet-archive-releases-refcat-the-ia-scholar-index-of-over-1-3-billion-scholarly-citations/>


- **Web of Science** (commercial, requires license)
  - https://pypi.org/project/wos/
  - https://developer.clarivate.com/apis/wos
  - https://github.com/rafguns/wosfile

- **Scopus**: Like Web of Science, but from Elsevier
  https://www.scopus.com



- **Google Scholar** (no API, but with scraping libraries, which often break. Google actively prevents scraping)
  - https://pypi.org/project/scholarly/

#### Books

- **OpenLibrary**
  - https://openlibrary.org/dev/docs/api/books
  - https://github.com/jayfajardo/openlibrary

- **Google Books API**
  - https://developers.google.com/books/docs/v1/using
  - https://medium.com/@akramhelil/google-books-api-with-rails-or-ruby-a931cece427a

- **Share-VDE: linked data for libraries**
  https://wiki.share-vde.org/wiki/Main_Page

- **WorldCat Search API (commercial)**
  - <https://www.oclc.org/developer/develop/web-services/worldcat-search-api.en.html>
  - <https://platform.worldcat.org/api-explorer/apis/wcapi>


##### National Libraries

- **Deutsche Nationalbibliothek (DNB)**
  - [DNB Linked Data](https://www.dnb.de/DE/Professionell/Metadatendienste/Datenbezug/LDS/lds_node.html)
  - [DNB SRU Interface](https://www.dnb.de/EN/Professionell/Metadatendienste/Datenbezug/SRU/sru_node.html)
      - [EXPLAIN XML](https://services.dnb.de/sru/dnb?operation=explain&version=1.1)
      - [Schnittstellen (PDF)](https://www.dnb.de/SharedDocs/Downloads/DE/Professionell/Metadatendienste/linkedDataZugriff.pdf?__blob=publicationFile&v=3)

- lobid.org : provides Linked Open Data (LOD) services
  - [GND](https://lobid.org/gnd/api)
  - [hbz](https://lobid.org/resources)

- Library of Congress SRU
  <https://www.loc.gov/standards/sru/>

- https://blog.ldodds.com/2014/10/08/accessing-the-british-national-bibliography-using-sparql/


#### Scholars

- VIAF: Virtual International Authority File (Persons)
  <https://viaf.org/>

  Clients
  - R: https://rdrr.io/cran/viafr/
  - PHP: https://packagist.org/packages/gbv/viaf-jskos
  - NodeJS: https://github.com/phette23/viaf-npm

- DNB Normdaten, via dariah.eu (Persons)
  [https://wiki.de.dariah.eu](https://wiki.de.dariah.eu/display/publicde/DARIAH-DE+Normdatendienste#DARIAHDENormdatendienste-GemeinsameNormdatei(GND))

- GND via (http://lobid.org/gnd) (Linked Open Data API)
  OpenRefine interface:
  https://lobid.org/gnd/reconcile
  https://blog.lobid.org/2018/08/27/openrefine.html

- orcid.org API
  <https://info.orcid.org/documentation/integration-guide/registering-a-public-api-client/>

- Google Scholar (only scholar-maintained info, see below)
  <https://scholar.google.com>

- ISNI: global standard number for contributors to creative works and those active in their distribution
  - Online Search: <https://isni.oclc.org/>
  - Linked Data: <https://isni.org/page/linked-data>

#### Venues/Journals/Sources

- ZDB (Zeitschriftendatenbank)
  - API: https://zeitschriftendatenbank.de/api
  - via lobig.org: https://blog.lobid.org/2018/09/04/zdb.html
-
- https://docs.openalex.org/api-entities/sources

#### Institutions

- Research Organization Registry
  <https://ror.org>

- ISNI: global standard number for contributors to creative works and those active in their distribution
  - Online Search: <https://isni.oclc.org/>
  - Linked Data: <https://isni.org/page/linked-data>



### Metadata extraction

#### End-to-end solutions

- annif. Tool for automated subject indexing and classification of documents
  https://annif.org/

#### OCR Software

- OCR-D: Complete Open Source OCR-Workflow for Libraries & Archives, using multiple OCR engines
  https://ocr-d.de/en/use

- OCR4All: OCR as a Web application (comes as a Docker image, intended for smaller & mainly historical projects)
  https://github.com/OCR4all/docker_image

- Tesseract Open Source OCR engine
  https://github.com/tesseract-ocr/tesseract

  - Tesseract to PAGE: analyse document page with Tesseract and convert to PAGE XML format
      https://www.primaresearch.org/tools/TesseractOCRToPAGE
  - TesseractXplore: a graphical interface to tesseract
      <https://github.com/JKamlah/tesseractXplore>
  - Clients
      https://github.com/zapolnoch/node-tesseract-ocr
      https://www.npmjs.com/package/node-ts-ocr


- **Apache Tika** - a content analysis toolkit, including Tesseract OCR
  https://tika.apache.org/
  https://medium.com/@masreis/text-extraction-and-ocr-with-apache-tika-302464895e5f

- **PDFSandwich**: combines tesseract, convert, unpaper
  http://www.tobias-elze.de/pdfsandwich/

- **OCRmyPDF**: adds an optical character recognition (OCR) text layer to scanned PDF files, allowing them to be searched.
  https://ocrmypdf.readthedocs.io/en/latest

- **Abbyy Cloud OCR **: commercial OCR service, expensive but very good results for modern texts
  https://cloud.ocrsdk.com
  https://github.com/cboulanger/abbyy-cloud-ocr

#### Other OCR engines/applications (mainly for historical or handwritten documents)

- **eScriptorium**: A project providing digital recognition of handwritten documents using machine learning techniques.
  https://escriptorium.fr/

- **Transkribus**: platform for the digitisation, AI-powered text recognition, transcription and searching of historical documents
  https://readcoop.eu/de/transkribus/

- **Kraken**: turn-key OCR system
  http://kraken.re/

#### Document Layout Description

- **Analyzed Layout and Text Object (ALTO)**: XML Schema for describing the layout and content of physical text
  resources, such as pages of a book or a newspaper.
  https://www.loc.gov/standards/alto/
  https://github.com/Mewel/abbyy-to-alto
  https://github.com/ironymark/AbbyyToAlto

- **Page Analysis and Ground-Truth Elements (PAGE)**
  http://www.primaresearch.org/publications/ICPR2010_Pletschacher_PAGE
  https://www.primaresearch.org/tools/PAGEViewer
  https://github.com/PRImA-Research-Lab/PAGE-XML
  https://github.com/PRImA-Research-Lab/prima-page-converter

- **ocr-fileformat**: Validate and transform between OCR file formats (hOCR, ALTO, PAGE, FineReader)
  https://github.com/UB-Mannheim/ocr-fileformat

- https://github.com/UB-Mannheim/crass
- https://pikepdf.readthedocs.io/en/latest/

#### OCR Postprocessing (Spellchecking / Error Correction)

- Survey of Automatic Spelling Correction
  https://www.mdpi.com/2079-9292/9/10/1670/pdf

- Automatic evaluation of OCR quality, using https://github.com/saffsd/langid.py
  https://ryanfb.github.io/etc/2015/03/16/automatic_evaluation_of_ocr_quality.html
  https://gist.github.com/cboulanger/cb4a99f7e03fb86141e511f15e3cfc5e (Implementation)

- **Pocoweb**: Platform for manual and semi-automatic postcorrection
  https://github.com/cisocrgroup/pocoweb (Browser-based, docker/server)

- **LanguageTool**: Style and Grammar Checker for 25+ Languages (server-based)
  https://github.com/languagetool-org/languagetool


#### Document ingestion (content structure analysis)

- **pub2tei**: A set of style sheets for converting XML documents encoded in various scientific publisher formats (such as JATS) into a common TEI format
  https://github.com/kermitt2/Pub2TEI


#### PDF handling & manipulation

- PDF editing libraries for Node
  https://www.npmjs.com/package/scissors

- Fixing page numbers
  https://github.com/lovasoa/pagelabels-py

#### Metadata enhancement / correction / annotation

- OpenRefine (to clean up, normalize/enrich existing data and reconcile with authority databases)
  https://openrefine.org/
  OpenRefine command line tool: https://github.com/opencultureconsulting/orcli

- Recogito: Collaborative Semantic Annotation
  https://recogito.pelagios.org/

## 4. Corpus Linguistics

### General issues

- Graduate course on Corpus Linguistics
  https://alvinntnu.github.io/NTNU_ENC2036_LECTURES/

- List of Tools for Corpus Linguistics
  https://corpus-analysis.com/

- Computerlinguistische Werkzeuge zur Erschließung und Exploration großer Textsammlungen aus der Perspektive fachspezifischer Theorie
  https://zfdg.de/sb001_013

- Text und Data Mining mit urheberrechtlich geschützten Textbeständen
  https://zfdg.de/2020_006

- Text Preprocessing for NLP and Machine Learning Tasks (terms and workflows)
  https://medium.com/sciforce/text-preprocessing-for-nlp-and-machine-learning-tasks-3e077aa4946e

### Creation & Analysis of Text Corpora

#### Software

- R-Studio (IDE), using Corpus Linguistics packages
  https://www.rstudio.com/

- MALLET: semi-automated Topic modeling analysis
  http://mallet.cs.umass.edu/topics.php
  Tutorial: https://programminghistorian.org/en/lessons/topic-modeling-and-mallet

- CorpusExplorer (free, Windows/Mono)
  https://notes.jan-oliver-ruediger.de/software/corpusexplorer-overview/
  https://github.com/notesjor/CorpusExplorer.Terminal.Console

- WordCruncher (free, Windows/Mac)
  https://www.wordcruncher.com

- Open Semantic Search Server
  https://www.opensemanticsearch.org

#### Services

- Constellate: builds corpora from JSTOR data
  https://constellate.org/builder/

- Unpaywall API
  https://unpaywall.org/products/api

### Text mining

### NLP tasks/problems

#### Keyword extraction

- https://www.analyticsvidhya.com/blog/2022/03/keyword-extraction-methods-from-documents-in-nlp/

#### Text classification

- https://towardsdatascience.com/text-classification-with-state-of-the-art-nlp-library-flair-b541d7add21f
- http://ethen8181.github.io/machine-learning/deep_learning/multi_label/fasttext.html

#### Document segmentation
- **PDF Document Segmentation Application**: browser-based tool for segmenting non-OCRed PDFs into individual, machine-readable text files
  https://github.com/lizfischer/document-segmentation
- https://towardsdatascience.com/nlp-splitting-text-into-sentences-7bbce222ef17
- https://spacy.io/usage/linguistic-features#sbd

#### Topic Modelling

- https://towardsdatascience.com/topic-modeling-with-lsa-plsa-lda-nmf-bertopic-top2vec-a-comparison-5e6ce4b1e4a5
- https://keyatm.github.io/keyATM/index.html
- https://github.com/koheiw/seededlda

#### Libraries

##### Python

- **Comparison**
  - https://medium.com/activewizards-machine-learning-company/comparison-of-top-6-python-nlp-libraries-c4ce160237eb

- **TM**
  https://tmtoolkit.readthedocs.io
- **NLTK**
  https://www.nltk.org
- **Gensim**
  https://radimrehurek.com/gensim
- **Flair**
  https://github.com/flairNLP/flair
- **SpaCy**
  https://spacy.io
- **Textacy**
  https://textacy.readthedocs.io
- **Stanza**
  https://stanfordnlp.github.io/stanza

##### R

- **Text Mining with R - an open access book**
  https://www.tidytextmining.com

- **Text mining in R for the social sciences and digital humanities**
  <https://tm4ss.github.io/docs>

- **IRaMuTeq**: R interface for Multidimensional Text and Questionnaire Analysis (French)
  http://www.iramuteq.org/

- **quanteda**
  https://quanteda.io/
  - Automatisierte Inhaltsanalyse mit R (German, using quanteda)
      http://inhaltsanalyse-mit-r.de
- **TM**
  https://cran.r-project.org/web/packages/tm/
  - Using the TM package
      https://rpubs.com/tsholliger/301914
  - A Tutorial of Text Mining in R Using TM Package
      https://medium.com/text-mining-in-data-science-a-tutorial-of-text/text-mining-in-data-science-51299e4e594

- **fulltext**: integration of rOpenSci R packages to create a single interface to many bibliographic data sources
  https://github.com/ropensci/fulltext

#### Javascript

- https://github.com/winkjs/wink-nlp


### Text annotation for machine learning
- TEI Publisher (with Docker image)
  https://github.com/eeditiones/tei-publisher-app

- TextAnnotator
  http://www.textannotator.texttechnologylab.org/

- Annotate them All: community annotation of scientific texts to Wikidata items
  - Info <https://sprint.elifesciences.org/annotate-them-all/>
  - GitHub: https://github.com/lubianat/ann

- inception: A semantic annotation platform offering intelligent assistance and knowledge management
  https://inception-project.github.io/
- doccano: Text Annotation for Humans (only text data)
  <https://doccano.github.io/doccano>

- LabelStudio: Open Source Data Labeling Tool
  <https://labelstud.io>

- CATMA
  <https://catma.de/>

- CitExt (citation annotation based on AnyStyle):
  https://github.com/cboulanger/citext

**Commercial:**

- Prodigy: an annotation tool powered by active learning (commmercial)
  <https://prodi.gy>

- tagtog: The Text Annotation Tool to Train AI (commercial)
  <https://tagtog.net>

- LightTag Text Annotation Tool (commercial)
  <https://www.lighttag.io/>
  - Free Academic Tier
      <https://www.lighttag.io/signup/academic/>

### Possibly relevant corpora

- F. Vogel, H. Hamann et al., JuReKo - Juristisches Referenzkorpus.
  https://www.cal2.eu/core-projects-and-associated-projects/jureko-juristisches-referenzkorpus

- GIANT: The 1-Billion Annotated Synthetic Bibliographic-Reference-String Dataset for Deep Citation Parsing
  https://isg.beel.org/blog/2019/12/10/giant-the-1-billion-annotated-synthetic-bibliographic-reference-string-dataset-for-deep-citation-parsing-pre-print/


## 5. Bibliometrics / Citation Analysis

### Initiatives

- **WikiCite**
  https://meta.wikimedia.org/wiki/WikiCite

- **OpenCitations**
  https://opencitations.net/

- **Kompetenzzentrum Bibliometrie**: A German initiative to boost bilbliometric research
  https://www.bibliometrie.info/


### Research graphs web services

- **Scholia**: knowledge graph based on WikiData
  https://scholia.toolforge.org/

- **OpenAIRE Research Graph**
  https://graph.openaire.eu/

- **Inciteful**: provides a Paper Discovery and a Literature Connector tool
  https://help.inciteful.xyz/

- **Connected Papers**: relies on semanticscholar.org to visualize a citation graph
  <http://connectedpapers.com>

- **LitMaps**: research discovery
  https://www.litmaps.com/

- **ResearchRabbit**
  https://researchrabbitapp.com/

### Scholarship

- [Bibliography (Zotero)](https://www.zotero.org/groups/4370759/computational_sociolegal_and_historical_legal_studies/collections/JTUVEEAP)


### Automatic article corpus aggregation

- Open Access PDF harvester and ingester
  https://github.com/kermitt2/article-dataset-builder

### Metadata extraction/annotation software and services

- Evaluation of Open-Source Bibliographic Reference and Citation Parsers
  https://arxiv.org/ftp/arxiv/papers/1802/1802.01168.pdf

- Scholarcy Reference Extraction API
  <https://ref.scholarcy.com/api/>

#### PDF citation extraction

- GROBID, a machine learning library for extracting, parsing and re-structuring raw documents such as PDF into structured XML/TEI encoded documents
  <https://github.com/kermitt2/grobid>
  - NodeJS client (there are also Python & Java clients)
      https://github.com/kermitt2/grobid-client-node

- Anystyle (Ruby)
  <https://anystyle.io>
  <https://github.com/inukshuk/anystyle>

- refext: extract reference strings from research papers in the PDF format (Java, based on CERMINE)
  <https://github.com/mkrnr/refext>

- refcat: large-scale citation graph generation tools
  <https://gitlab.com/internetarchive/refcat>

- Content ExtRactor and MINEr (extracts metadata and content from PDF files containing academic publications)
  <https://github.com/CeON/CERMINE>

- EXparser: a tool for extracting and segmenting reference strings from PDF documents
  https://exparser.readthedocs.io/en/latest/

- Science Parse parses scientific papers (in PDF form) and returns them in structured form (Java)
  https://github.com/allenai/science-parse


### Data exchange formats

- CSL-JSON
  https://citeproc-js.readthedocs.io/en/latest/csl-json/markup.html
  https://aurimasv.github.io/z2csl/typeMap.xml

- RIS
  https://en.wikipedia.org/wiki/RIS_(file_format)

- BibTeX
  https://www.bibtex.com/g/bibtex-format/

- Web of Science Export Format (the only format that has explicit support for citation data)
  https://images.webofknowledge.com/images/help/WOS/hs_wos_fieldtags.html

- Zotero Data Schema
  https://github.com/zotero/zotero-schema

### Matching/normalization of citations

- fuzzycat: bibliographic fuzzy matching for fatcat.wiki
  <https://gitlab.com/internetarchive/fuzzycat/>

- biblio-glutton: Framework dedicated to bibliographic information
  <https://github.com/kermitt2/biblio-glutton>

- List of Title Word Abbreviations based on the ISO 4 system for the abbreviation of serial titles
  https://www.issn.org/services/online-services/access-to-the-ltwa/

### Applications for data analysis

- SciMAT (Science Mapping Anaylsis Tool): tool for performing science mapping analyses under a longitudinal framework
  https://sci2s.ugr.es/scimat/

- CiteSpace: software for visualizing and analyzing trends and patterns in scientific literature
  http://cluster.cis.drexel.edu/~cchen/citespace/

- CitNetExplorer
  <https://www.citnetexplorer.nl/>

- VOSViewer
  <https://www.vosviewer.com/> ([Keynote presentation](https://www.youtube.com/watch?v=3aSKhFeXIU4), [Tutorial Slides](https://de.slideshare.net/NeesJanvanEck/issi2015-tutorial-vosviewerandcitnetexplorer))

- BiblioTools/BiblioMaps: create maps of science based on bibliographic data
  http://www.sebastian-grauwin.com/bibliomaps/

- Headstart: web-based knowledge mapping software proividing visualization and connectors to a number of academic search engines through rOpenSci, including BASE, PubMed, PLOS and DOAJ
  https://github.com/OpenKnowledgeMaps/Headstart

- Cited Reference Explorer
  <https://andreas-thor.github.io/cre/>

- BibExplorer: Process curricula, extract article meta-data, and calculate bibliometric indicators
  https://github.com/alandefreitas/bibexplorer

- PubTrends: a scientific literature exploratory tool for analyzing topics of a research field and similar papers analysis (uses PubMed, Semantic Scholar)
  https://github.com/JetBrains-Research/pubtrends

- VIVO: member-supported, open source software and an ontology for representing scholarship <https://duraspace.org/vivo/about/>

- Publish or Perish. A free software program that retrieves and analyzes academic citations from a variety of data sources (incl. Google Scholar and Microsoft Academic Search)
  https://harzing.com/resources/publish-or-perish

- Sci2: The Science of Science (Sci2) Tool is a modular toolset specifically designed for the study of science
  https://github.com/CIShell/sci2

### Multi-purpose libraries

#### Python

- metaknowledge: for computational research in bibliometrics, scientometrics, and network analysis
  https://metaknowledge.readthedocs.io

- Tethne: integrated bibliographic and corpus analysis (Python **2.7**)
  http://diging.github.io/tethne/
  https://pythonhosted.org/tethne/index.html

- étudier: drive a non-headless browser to collect a citation graph from google scholar around a particular citation or set of search results.
  <https://github.com/edsu/etudier>

- Deep Reference Parsing: A deep learning architecture for reference mining from literature in the arts and humanities -> parses individual references into components
  - <https://github.com/dhlab-epfl/LinkedBooksDeepReferenceParsing>
  - [article (2018)](https://doi.org/10.3389/frma.2018.00021)

- BiblioPy: co-citation analysis (Python 2)
  https://github.com/Greenwicher/BiblioPy

#### Working with Web of Science data
- https://github.com/rafguns/wosfile
- https://pypi.org/project/WOSplus/
- https://pypi.org/project/wostools/

#### R

- bibliometrix: R library for comprehensive science mapping analysis (works with data extracted from the four main bibliographic databases: *SCOPUS*, *Web of Science*, *Digital Science Dimensions*, *The Lens*, *Cochrane Database of Systematic Reviews (CDSR)*, and *RISmed PubMed/MedLine*)
  - <https://bibliometrix.org/>
  - See papers where this has been used: <https://bibliometrix.org/Papers.html>
  - biblioshiny: The shiny interface for bibliometrix
      https://www.bibliometrix.org/home/index.php/layout/biblioshiny

- biblionetwork: creates bibliographic coupling and cocitation networks
  https://agoutsmedt.github.io/biblionetwork/

- scimeetr: Analyse data from WoS/Scopus
  https://github.com/MaximeRivest/scimeetr

- Connect RStudio to Zotero
  https://github.com/paleolimbot/rbbt
  https://rstudio.github.io/visual-markdown-editing/#/citations

- Querying CrossRef Data with R
  https://poldham.github.io/abs/crossref.html
