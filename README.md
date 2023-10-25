# turtle
Interoperability Architecture for a Digital Ocean (TURTLE)

This repository is aimed to develop a set of transformation tests between existing data standards using in Digital Twins of the Ocean (DTO), including metadata standards in order to establish a framework for best practices for semantic integration in DTOs.

Priorites will be determined by **system federation** opportunities and requirements. 

The approach will use the ILIAD project's [Ocean Information Model](https://github.com/ILIAD-ocean-twin/OIM), which is a modular standards based framework based on semantic technologies.

Three initial sets of activities have been identified.

## 1. Dataset Description Metadata

A profile of DCAT for spatio-temporal aspects is under development in [new OGC GeoDCAT Standards Working Group](https://www.ogc.org/press-release/ogc-forms-new-geodcat-standards-working-group/)

The repository for GeoDCAT is [here](https://github.com/opengeospatial/GeoDCAT-SWG):
The repository for an implementation of GeoDCAT using OGC-API-Records is [here](https://github.com/ogcincubator/geodcat-ogcapi-records)  using the [OGC BuildingBlocks design](https://github.com/opengeospatial/bblock-template). 

The first step for DITTO will be to map metadata records from the STAC format to the DCAT ontology and test with [examples](examples/STAC/)

The next step will be to create a  STAC sub-profile of GeoDCAT - and submit these the to the OGC GeoDCAT SWG.

## 2. Observation Data Semantics

This is being progressed in the ILIAD Oceans Information Model (WP 4.2) and APIs (WP 4.5).  A [testing framework using ILIAD pilot examples](https://github.com/ogcincubator/iliad-apis-features) will be extended as OIM emerges and system integration activities (such as integration with BioDT) establish requirements.

This component describes a general approach for mapping and validation APIs, schemas and semantic models using available standards (JSON, JSON-LD, SHACL) within a Best Practice CI/CT/CD context (Continuous Integration/Testing/Deployment) and automated documentation from machine-readable specifications.

## 3. OGC API Processes and PROV profiles for provenance and workflow graphs

This activity is being progressed in multiple related projects, with common requirements extracted as BPs (and potential future standards) for example:

- the [PROV Building Block](https://github.com/ogcincubator/bblock-prov-schema) - an OpenAPI compatible implementation of the [PROV vocabulary](https://www.w3.org/TR/prov-o/)
- [PROV-CWL Building Block](https://github.com/ogcincubator/prov-cwl/tree/master) an extension implementing the  Common Workflow Language (CWL) profile of PROV 

