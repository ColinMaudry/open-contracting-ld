## Open Contracting Data Standard - Linked Data Edition

This project aims at enabling any JSON data that complies with the [OCDS JSON Schema](http://standard.open-contracting.org/latest/en/schema/) to be published as [Linked Data](https://www.w3.org/standards/semanticweb/data).

#### What??

**[Linked Data](https://www.w3.org/standards/semanticweb/data)** is a way of publishing data that relies on few principles:

- a resource is identified with an HTTP URI (not a plain string)
- dereferencing (HTTP GET) this URI returns data about the resource
- the description of the resource contains relations to other resources, also identified with URIs.

The result: a meshed network of resources than can easily be traversed by a machine.

**[RDF](https://www.w3.org/TR/2014/NOTE-rdf11-primer-20140225/#section-Introduction)** is the framework that powers Linked Data.

The **[OCDS](http://standard.open-contracting.org/latest/en/)** is a data model that aims at structuring and publishing contracting data (tenders, procurements, awards, transactions, etc.). It got international adoption and is one of the leading models in this domain.


#### An RDF/Linked Data variant of the Open Contracting Data Standard (OCDS) JSON Schema.

The first deliverable of this project is an ontology (~ schema) that translates the structure and semantics expressed in the OCDS JSON Schema into RDF.

- [Turtle file](ontology/ocds.ttl)
- [Visualization](http://vowl.visualdataweb.org/webvowl/index.html#iri=https://raw.githubusercontent.com/ColinMaudry/open-contracting-ld/master/ocds.ttl)
- [SPARQL endpoint](dydra.com/colin-maudry/ocds/sparql)

#### A JSON-LD context to turn any data compliant with OCDS JSON Schema into RDF

Soon (c)

### License

This project is licensed under the terms of the [CC-BY license](https://creativecommons.org/licenses/by/2.0/).

Credit can be given this way:

"Original version by Colin Maudry (http://colin.maudry.com), published at https://github.com/ColinMaudry/open-contracting-ld."
