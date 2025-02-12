# BostonGene_bioinformatics_hackathon_2024
In December 2024, together with my groupmates ([Anna Andreeva](https://github.com/annushkndrv), [Arina Filimonova](https://github.com/arinafil), [Olga Piskunova](https://github.com/celluwee)), we won the BioCode bioinformatics hackathon from [BostonGene](https://bostongene.com/). Here is a solution to the problem of testing the response to a pathogen according to the immune repertoire.

It was proposed to test a pair of immune repertoires for a response to a pathogen by comparing the sequences of the CDR3 region of the T-cell receptor to known sequences in the database, given that the presence of a sequence in the repertoire does not in itself mean that a response is observed.

We applied clustering using the Levenshtein distance and estimated the degree of confidence in a non-random result. This solution can be developed with the prediction of cases with absence of diseases.
