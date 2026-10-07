We provide JSON-LD contexts to be compatible with other JSON-based formats which provide coordinate reference system data.

## Compatibility with PROJJSON

[PROJJSON](https://proj.org/en/stable/specifications/projjson.html) is an established format to share geospatial data which has emerged from the PROJ library and encodes the WKT encoding of coordinate reference systems. By adding a JSON-LD context to the PROJJSON standard we achieve an immediate compatibility with an established standard simply by extending it by one simple statement.

```json
{
    "@context": "https://opengeospatial.github.io/ontology-crs/context/geosrs-context.json",
    "$schema": "https://proj.org/schemas/v0.7/projjson.schema.json",
    ...
}
```

We provide examples of application of this JSON-LD context with the distribution of this standard.

## Compatibility with OGCJSON

The OGC CRS working group is aiming towards the creation of their own JSON format for CRS. The JSON-LD context we provide aims to be compatible with both PROJJSON and OGCJSON.
