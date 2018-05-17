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

<hr />

### License
APPAGATO is distributed under the MIT license. This means that it is free for both academic and commercial use. 
Note however that some third party components in APPAGATO require that you reference certain works in scientific publications. 
You are free to link or use APPAGATO inside source code of your own program. If do so, please reference (cite) APPAGATO and this website. We appreciate bug fixes and would be happy to collaborate for improvements.

[MIT License](https://raw.githubusercontent.com/GiugnoLab/Dataset-APPAGATO/master/LICENSE)

<hr />

### Citation
    "Bonnici, V., Busato, F., Micale, G., Bombieri, N., Pulvirenti, A., & Giugno, R. (2016).
     APPAGATO: an APproximate PArallel and stochastic GrAph queryingTOol for biological networks.
     Bioinformatics, 32(14), 2159-2166."
[Cited by](https://scholar.google.it/scholar?hl=it&as_sdt=0%2C5&q=appagato+bonnici&btnG=) <br>

<hr />

### References 
If you have used any of the APPAGATO project software or dataset, please cite the following article:
  
    "@article{,
    title={APPAGATO: an APproximate PArallel and stochastic GrAph querying TOol for biological networks},
    author={Bonnici, Vincenzo; Busato, Federico; Micale, Giovanni; Bombieri, Nicola; Pulvirenti, Alfredo; Giugno, Rosalba},
    journal={Bioinformatics},
    volume={32},
    number={14},
    pages={2159--2166},
    year={2016},
    publisher={Oxford Univ Press}
    }"

