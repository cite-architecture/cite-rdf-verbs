
# CTS Verbs. The Concise, Categorized List

This list includes verbs required to express the OHCO2 model in RDF, and some additional, implementation-specific verbs used by the `hocuspocus` and `sparqlcts` libraries.

# Verbs required for full expression of OHCO2 model

These verbs apply to RDF representation of any OHCO2-compliant text.

- cts:belongsTo
- cts:citationDepth
- cts:containedBy
- cts:contains
- cts:fullUri
- cts:hasPassage
- cts:hasSequence
- cts:hasTextContent
- cts:isPassageOf
- cts:lang
- cts:next
- cts:possesses
- cts:prev
- dcterms:title
- rdf:label
- rdf:type

# Context-dependent

Applies only to content citing subreferences.  Should only be used to equate subreferenced passage with a canonically citable URN in another exemplar or version:

- cts:hasSubref
- cts:isSubrefOf

Applies only to content in translation:

- cts:translationLang

Applies only to text content expressed in well-formed XML fragments:

- cts:xmlns
- cts:xmlnsabbr
- hmt:xmlOpen
- hmt:xpTemplate

Optionally allows identification of node format as "xml", "markdown" or (plain) "text": 

- hmt:nodeFormat
