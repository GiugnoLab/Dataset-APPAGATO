# Dataset-APPAGATO
Dataset fot APPAGATO project


### CORUM

Functional interaction networks extracted from the STRING dataset nd related to the species Mus musculus (7227), Homo sapiens (9606), Danio rerio (4932) and Saccharomyces cerevisiae (10090).

As queries, 10 human protein complexes were taken from [CORUM](http://mips.helmholtz-muenchen.de/corum/).
Since CORUM only reports the set of proteins belonging to a given complex, and not their interactions, we reconstructed the topology of the complex by taking into account the interactions reported in the full STRING database with respect to the Homo sapiens species.

Similarity matrices between nodes of reference and query networks were computed by making use of [CUDASW](http://cudasw.sourceforge.net).

<hr />

### PPI-GO

Physyical interaction networks taken from STRING 10.0 for species Danio rerio, Homo sapiens and Mus musculus.
Networks were labelled with (43) gene ontologies downloaded from [BioDbNet](http://biodbnet.abcc.ncifcrf.gov).
Sets of 100 queries were randomly extracted, from each one of the 3 networks, by varying the numer or query nodes in 4, 8, 16, 32, 64, and 128.

<hr />

### PPI-udistr

Physyical interaction networks taken from STRING 10.0 for species Danio rerio, Homo sapiens and Mus musculus.
We used 32, 64 and 250 distint labels to randomly annotated the networks. This yielded 9 reference networks.
Sets of 100 queries were randomly extracted, from each one of the 9 networks, by varying the numer or query nodes in 4, 8, 16, 32, 64, and 128.

