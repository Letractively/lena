The SPARQL selector can be used in the following way:

Instances can be selected by a SELECT query, whereas it is important to only use one variable in the SELECT clause.

`'SELECT ?person WHERE { ?person rdf:type foaf:Person }'^^fresnel:sparqlSelector ;`

Properties can be selected by a CONSTRUCT query. As properties are selected for a resource available in the lens domain, this resource is accessable by a variable called `?instance` conventionally.

`'CONSTRUCT {	?instance foaf:knows ?friend } WHERE { ?instance foaf:knows ?friend }'^^fresnel:sparqlSelector ) ;`

For not adding prefixes to every SPARQL selector, prefixes are added once by a namespace vocabulary:

`@prefix fslns: <http://simile.mit.edu/2006/01/ontologies/fsl-ns#> .`

`<http://example.org/> a fslns:Namespace ;`

`fslns:abbreviated 'ex' .`