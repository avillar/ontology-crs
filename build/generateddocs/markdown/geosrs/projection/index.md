
# SRS Ontology - Projection module (Model)

`ogc.geosrs.projection` *v0.1*

A building block defining SRS Ontology Projection Module

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## SRS Ontology Projection Module

This module describes how to model a projection system using the SRS ontology vocabulary.

Projection classes and properties are described under the namespace https://w3id.org/geosrs/projection/

![SRS Ontology Projection Module](assets/projection.svg)

A map projection is a specific set of transformations which are used to represent the two-dimensional surface of a globe on a map plane. All map projections are therefore specific coordinate transformations in the sense of the coordinate operation module.

This module does not describe the specific parameters of a map projection because many variants of a map projection with different parameter usage might exist. Rather we describe the classes to specify the type of projection. Parameter values of the projection type will have to be initialized when instances of the projection class are created.

## Examples

### SRS Ontology Projection Module Example
#### ttl
```ttl
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix geosrs_proj:<https://w3id.org/geosrs/projection#> .
@prefix geosrs:<https://w3id.org/geosrs/> .
@prefix exsrs: <https://w3id.org/example-data-srs#> .

exsrs:mysrs rdf:type geosrs:GeodeticCRS ;
            geosrs:conversion exsrs:myproj .
exsrs:myproj rdf:type geosrs_proj:Projection .
```

## Sources

* [Spec Section](https://opengeospatial.github.io/ontology-crs/spec/documents/spec/document.html#projection)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/avillar/ontology-crs](https://github.com/avillar/ontology-crs)
* Path: `_sources/projection`

