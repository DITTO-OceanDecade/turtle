# turtle
Interoperability Architecture for a Digital Ocean (TURTLE)

## Plans

Initial plan is to develop a set of transformation tests between existing data standards, including metadata standards.

The approach will use the ILIAD project's [Ocean Information Model](https://github.com/ILIAD-ocean-twin/OIM), which is a modular standards based framework based on semantic technologies.

The first step will be to map metadata records from the STAC format to the DCAT ontology. 

The next step will be to refactor out a prototype GeoDCAT profile of DCAT, and a STAC sub-profile of GeoDCAT - and submit these the to [new OGC GeoDCAT Standards Working Group](https://www.ogc.org/press-release/ogc-forms-new-geodcat-standards-working-group/)

After this, mapping to the OGC API Records JSON schema will be undertaken, using the [OGC BuildingBlocks design](https://github.com/opengeospatial/bblock-template)

