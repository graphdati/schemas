# Schemas

The schemas used by GraphDati for important data objects are managed here. The schemas are in JSONSchema format, but the original and editable versions are stored in YAML format to allow for additional comments and easier reading of the data objects.

The data object schemas are for:

* nanopubs


## Descriptions

Many of the following schemas will support JSONLines (jsonlines.org) format to allow streaming of the dataset so one doesn't have to load all of the JSON file before processing.  One can then load each sub-object, e.g. a nanopub at at time in the nanopub schema.

### Nanopubs

The nanopub schema is for capturing curated knowledge or assertions as a triple (subject, relation, object or SRO). The triple (or array of triples) have a citation indicating from where the triple was sourced, context such as for BEL Nanopubs what tissue, disease context, cell line, species, etc the triples are associated with. Miscellaneous metadata is also captured for the triple.
