# MSc-Bioinformatics-Project

# Title:- Unlocking triadic nexus of interrelationship between tau,amyloid beta and alpha-synuclein in Neurodegenerative Disorders to Identify Novel Drug Targets through structure based drug design

# Methodology:-

•	1.Gathering the data set of proteins from BioGRID 

•	2.Construction of protein-protein interactions using cytoscape

•	3.Integration of ppi network with known data in Genemania and string databases to get a network of interactors of proteins

•	4.Analyzing protein-protein interaction (PPI) networks for identifying direct and indirect interactions between tau (MAPT), alpha-synuclein (SNCA), and amyloid-beta (APP) for finding common protein involved with the interactions.

•	5.The protein sequences were retrieved from the UniProt database for predicting protein structures using alphafold3.

•	6.The common protein involved interactions with Tau, alpha-synuclein, and amyloid-beta are docked with Cluspro webserver.

•	7.The constructed PPI network of proteins can be given as input in Reactome database to get common molecular pathways

•	8.The ligands were designed and modified functional groups using Biovia Draw 2025

•	9.Docking of proteins with designed specific ligands using PyRx software.


# RESULTS:-
![image](https://github.com/user-attachments/assets/b762b3ba-8500-406d-a27d-9949c0302450)

Fig1:-Constructed protein-protein interactions of alpha-synuclein in cytoscape

![image](https://github.com/user-attachments/assets/8b1f5c22-4c3e-4e28-a65e-0088fae19771)

Fig2:-Constructed protein-protein interactions of tau in cytoscape

![image](https://github.com/user-attachments/assets/4717dae9-996e-495d-8120-c31fab33a2c4)
 
 Fig3:-Constructed protein-protein interactions of amyloid beta in cytoscape
 
![image](https://github.com/user-attachments/assets/e3328467-6383-4cf4-8c0f-03b2b7e7aa8d)

Fig4:-Integrated network of alpha-synuclein with genemania

![image](https://github.com/user-attachments/assets/fa522200-5caf-47f2-b069-fbaedeef63a4)

Fig 5:-Integrated network of tau with genemania

![image](https://github.com/user-attachments/assets/fcb9d8b1-ab2d-42c3-8be4-bb47a538bcd9)

Fig 6 :-Integrated network of amyloid beta with genemania

![image](https://github.com/user-attachments/assets/ad4953d6-a58b-4fd4-8e3f-a59b7d10091b)

Fig 7:-Common protein involved with interactions of tau(MAPT),alpha-synuclein(SNCA) and Amyloid beta(APP), identified with string database by inputing interactors of proteins


CDK5 protein identified as common protein involved with MAPT,APP,SNCA protein interactions.In next step with CDK5 Protein is docked with all 3 proteins using Cluspro.

![tau](https://github.com/user-attachments/assets/3841ccd1-10a4-4bda-8649-66266e8c7b64)

Fig 8:- 


Future work:-The constructed network of proteins involved in interactions can be utilized to identify common molecular pathways using Reactome.The common protein interacted with tau (MAPT), alpha-synuclein (SNCA), and amyloid-beta (APP) can be utilized for designing drug targets using Biovia Draw 2025 software and Docked with ligands using PyRx Software.
