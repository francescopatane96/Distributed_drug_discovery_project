# Distributed_drug_discovery_project
The scope of the project is the creation of a public and easy to access repository containing a vast coort of drug discovery models.  

Following principles like the distributed computing and the wisdom of crowds, the hope of this rep is make science and bioinformatics, in particular drug discovery field, more democratic and accessible to all. The repository allows you to create your own and personal data science/bioinformatics/computational drug discovery portfolio and to scan a little part of the so called 'chemical space', in order to discover new candidate drugs. 

0. fork the project,
1. choose the target protein of interest and name correctly the notebook sheet (e.g.: target_name.ipnyb),
2. make the pipeline reproducible for all the utents (e.g.: seed=42),
3. save models and plots in the rep. models must be named as type_of_model_R1score.h5

ML_1 : set uniprot_id of interest (target protein). retrieve data of every annotated and tested compound on the target from ChEMBL database and calculate lipinki's and fingerprint descriptors with PADEL. 



