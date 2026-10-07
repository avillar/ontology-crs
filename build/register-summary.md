# SRS Ontology

Building blocks for implementation of the OGC SRS ontology

Each building block defines a reusable JSON schema that is mapped to the equivalent SRS Ontology concept.

Each fragment allows for transparent and validatable use of JSON-LD contexts to map schema elements to equivalent terms from the GeoSPARQL ontology. 

 _These components are under review by the GeoSPARQL SWG as candidate canonical implementations._ 

 Each building block allows for examples transformed to RDF, which in turn allows for the use of SHACL rules to enforce the semantics of the GeoSPARQL specifications.


## Building Blocks

### `ogc.geosrs.app` — SRS Ontology - Application module

**Type:** model

A building block defining SRS Ontology Application Module

### `ogc.geosrs.co` — SRS Ontology - Coordinate Operation module

**Type:** model

A building block defining SRS Ontology Coordinate Operation Module

### `ogc.geosrs.cs` — SRS Ontology - Coordinate System module

**Type:** model

A building block defining SRS Ontology Coordinate System Module

### `ogc.geosrs.datum` — SRS Ontology - Datum module

**Type:** model

A building block defining SRS Ontology Datum Module

### `ogc.geosrs.planet` — SRS Ontology - Planet module

**Type:** model

A building block defining SRS Ontology Planet Module

### `ogc.geosrs.projection` — SRS Ontology - Projection module

**Type:** model

A building block defining SRS Ontology Projection Module

### `ogc.geosrs.requirements.alignments` — Alignments

**Type:** clause

Namespaces of the ontologies the CRS ontology is aligned to.

### `ogc.geosrs.requirements.conventions` — Conventions

**Type:** clause

Conventions used in the CRS ontology specification.

### `ogc.geosrs.requirements.instances` — Common Instances

**Type:** requirements-class

Requirements class for the common instances (axis directions, spheroids, prime meridians, literal types) needed in CRS specifications.

### `ogc.geosrs.requirements.jsonld-context` — JSON-LD Context

**Type:** clause

JSON-LD contexts for compatibility with JSON-based CRS formats.

### `ogc.geosrs.requirements.references` — Normative References

**Type:** references

Normative references of the CRS ontology specification.

### `ogc.geosrs.requirements.revision-history` — Revision History

**Type:** clause

Revision history of the CRS ontology specification.

### `ogc.geosrs.requirements.scope` — Scope

**Type:** clause

Scope of the CRS ontology specification.

### `ogc.geosrs.requirements.shacl-shapes` — SHACL Shapes

**Type:** clause

SHACL shapes to validate graphs that use the CRS ontology.

### `ogc.geosrs.requirements.terms` — Terms and Definitions

**Type:** terms

Terms and definitions used in the CRS ontology specification.

### `ogc.geosrs.srs` — SRS Core Ontology

**Type:** model

A building block defining the SRS Core Ontology

