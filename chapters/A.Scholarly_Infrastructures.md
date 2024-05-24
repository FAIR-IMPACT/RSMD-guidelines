# Annex A: Scholarly Infrastructures - making it possible


Section 5 and and appendix f & G in report.


While analyzing the state of the art and creating the RSMD guidelines, we encountered actions, recommendations and requirements that are not in scope for the RSMD guidelines but are needed to make metadata curation a reality. 

Scholarly infrastructures, listed below,  should provide platforms that support the community practices and the RSMD guidelines. 


    “Policy describes what is required, desired, and incentivised;


    infrastructure determines what is possible;


    but the community determines how things are done in practice.”

<p style="text-align: right">
(Brinkman et al., 2020)</p>


In the list below we have collected actions and requirements that should be executed by scholarly infrastructures (e.g scholarly repositories, aggregators and publishers) using the RSMD thematics, note that this list isn’t exhaustive: 



* **General requirements**:
    * Ensure metadata records are licensed under CC0
    * Provide mechanisms to moderate and curate metadata to ensure curation quality of software records in the infrastructure collection
    * Provide specific guidance on how to use the infrastructure services to ensure metadata is collected and preserved
* **Accessibility & preservation**:
    * Follow scholarly best practices identified by the [scicodes consortium](https://scicodes.net/)[^1] to ensure quality service, this includes but is not limited to: Providing a public scope statement, disclosing infrastructure end-of-life policy and stipulating conditions of use


* **Reference and identification**: 
    * Provide tools to track the software in other scholarly outputs: aggregating information about entities and the relationships between them enables strategic analysis (Fenner, 2020)
    * Publish policies for research products including PIDs for software
    * Provide guidance to article authors to identify which PID should be used to identify software projects or artifacts: extrinsic and intrinsic identifiers
    * Implement platforms and services with better and consistent PID integrations and help grow the PID Graph to track connections.
    * Cross-link a plurality of academic outputs at the infrastructure level by providing adapted metadata properties
* **Description & classification**
    * Share the metadata schema, taxonomy, vocabulary or ontology used by the infrastructure to store the metadata
    * Provide import and export metadata features using the codemeta.json format
* **Attribution & credit**
    * Provide citation export formats to facilitate credit (e.g BibTeX export format)
    * Establish clear authorship policy acceptable by the infrastructure (most relevant to publishers)
    * Provide mechanisms to cite collective author
* **Reuse, licensing and legal aspects**: 
    * Provide standardized method for display copyright and licensing information between projects and people; e.g.: [SPDX licenses](https://spdx.org/licenses/) list
    * Require license information using a controlled list ([SPDX licenses](https://spdx.org/licenses/) list)
    * Support software authors by providing guidance on license use, etc.
* **Re-execute: dependencies and execution environment**
    * Provide metadata properties to store information about operating system, hardware and dependencies
    * Provide guidance, if possible, on how to ensure better sustainability of dull software stack (e.g GUIX)


##  Description of Infrastructures Types


### Scholarly Repositories

“An organisation called to archive and make available research artifacts, e.g. articles, datasets, software.”

(EOSC Executive Board & EOSC Secretariat, 2020)

#### A few examples
* [HAL](https://hal.science/#)
* [Zenodo](https://about.zenodo.org/)
* [Dryad](https://datadryad.org/stash/about)


### Registries (catalogs) & Aggregators

"Research software registries are typically indexes or catalogs of software metadata, without any code stored in them; while in research software repositories, software is both indexed and stored " 
([Garijo et al., 2022](https://doi.org/10.7717/peerj-cs.1023))

“Aggregators collect, curate, select, present, and aggregate information about research software from various sources to improve findability in diverse communities.”([EOSC Executive Board & EOSC Secretariat, 2020](https://data.europa.eu/doi/10.2777/28598))

“Any service that collects information about digital content from a variety of sources with the primary goal of increasing its discoverability, and possibly adding value to this information via processes like curation, abstraction, and classification, and linking.”([EOSC Executive Board & EOSC Secretariat, 2020](https://data.europa.eu/doi/10.2777/28598))

#### A few examples

* [swMATH.org](https://zbmath.org/software/)
* [ASCL](https://ascl.net/)
* [OpenAIRE](https://www.openaire.eu/about)
* [The DataCite](https://datacite.org/)


### Publishers

“Any organization that prepares submitted research texts, possibly with associated source code and data, to produce a publication and manage its dissemination, promotion, and archival process.” ([EOSC Executive Board & EOSC Secretariat, 2020](https://data.europa.eu/doi/10.2777/28598))


“[…] there is an opportunity for publishers to educate authors on the necessity of sharing software source code and encourage a standard workflow.” ([EOSC Executive Board & EOSC Secretariat, 2020](https://data.europa.eu/doi/10.2777/28598))


#### A few examples
* [Dagstuhl](https://www.dagstuhl.de/publikationen/darts/)
* [IPol](https://www.ipol.im/meta/policy/)


### Software development platform

An online service for developers to collaborate on software development activities

[https://en.wikipedia.org/wiki/Collaborative_development_environment](https://en.wikipedia.org/wiki/Collaborative_development_environment)

[https://en.wikipedia.org/wiki/Version_control](https://en.wikipedia.org/wiki/Version_control)

Note this infrastructure is usually outside the academic realm.

#### A few examples
* GitHub
* Bitbucket
* SourceForge


### Package managers

A repository of software tools and libraries that can be installed on a given base system or for a particular programming language; typically as intra-dependent packages with pre-compiled binaries or build recipes.

“The foundations of functional workflows are sources for readily usable software” [https://doi.org/10.1007/s41019-017-0050-4](https://doi.org/10.1007/s41019-017-0050-4) 


#### A few examples
* OS: [Debian](https://www.debian.org/distrib/packages),  [Ubuntu](https://packages.ubuntu.com/), [WinGet](https://github.com/microsoft/winget-cli)
* OS independent: [Conda](https://docs.conda.io/en/latest/), [Homebrew](https://brew.sh/)
* Python: [PIP](https://pypi.org/)
* R: [CRAN](https://cran.r-project.org/)
