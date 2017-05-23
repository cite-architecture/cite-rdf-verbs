# CITE verbs

This repository defines terms describing citable relations between two citable objects.  We also refer to these terms as "verbs" since the relationship may be expressed as S-V-O statement, where subject and object are the pair of citable objects, and verb is the relation between them.

The authoritative definition of terms is maintained as a CITE Collection in the `cite-collection` directory.  The collection's structure is defined in a file named `cite-verbs-catalog-VERSION.cex`, and its data are in a file named `cite-verbs-data-VERSION.csv`, where `VERSION` identifies a specific release of the collection.  The catalog file is in the plain-text CITE Exchange format (CEX).  The data file is simply a comma-separated table.  It can be used without change in a CEX data source by prepending the single line `#!citedata`.

In addition, the `rdf-notes` directory has notes on how these terms could be used in RDF.


## Version and status

**DRAFT** status: no releases yet.
