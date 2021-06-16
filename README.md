# Integrated Model of *Pseudomonas aeruginosa*

This repository provides supplementary material of the manuscript: **Integration of transcriptomic data and metabolic network of *Pseudomonas aeruginosa.*** 
##### Authos: Medeiros Filho1†\*, Nascimento1†, Merigueti1, Costa3, Menezes4, Nicolás3, Santos3, Carvalho-Assef2, Silva1\*

######  1 Fundação Oswaldo Cruz, Programa de Computação Científica, Rio de Janeiro, RJ, Brazil; 2 Fundação Oswaldo Cruz, Instituto Oswaldo Cruz, Laboratório de Pesquisa em Infecção Hospitalar, Rio de Janeiro, RJ, Brasil; 3 Laboratório Nacional de Computação Científica, Petrópolis, RJ, Brazil; 4 Instituto de Física, Universidade Federal Fluminense, Niterói, RJ, Brazil; † These authors have contributed equally to this work and share first authorship; \* Correspondence authors



## Abstract 


*Pseudomonas aeruginosa* is an opportunistic human pathogen known to cause nosocomial infections in immunocompromised patients. A useful approach to assess this bacterium's complex behavior is to create a computational model integrating transcriptomic data into genome-scale metabolic networks. In this paper, we use an integrated model to dynamically simulate the growth of *Pseudomonas aeruginosa* in a minimal medium with glycerol or acetate as carbon source. Our simulation results show a quantitative correspondence to the available experimental data. One can expect the analysis of an integrated model can identify potential bacteriostatic targets more accurately than it is possible with a metabolic model which does not take into account data from other cellular processes. This paper investigates this assumption. In this manuscript, we use the integrated model of P. aeruginosa to list potential therapeutics targets using an automated method. We then compare these targets with the ones identified from the non-integrated model and discuss the accuracy of the potential targets found in both sets of models.

Keywords: *Pseudomonas aeruginosa*, Metabolic  Networks, Transcriptional  Data, Dynamic Integrated Model.

Correspondence: fernando.filho@ioc.fiocruz.br, fabricio.silva@fiocruz.br 

# Description of supplementary material

[Models](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/models): Here you can find the models used in the simulations performed in this manuscript. They are divided into files with matlab and sbml extensions. The .mat files were used in the session **Integration of metabolic network and transcriptome data** and **Dynamics simulations** of the methods. The sbmls files were exported from matlab in order to simulate them in FindTargetsWeb in the **Identification of Potential Therapeutic Targets** methods section

[Simulations](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/Simulations): In this folder you will find the results of simulations referring to growth curves using the TRFBA algorithm described in the **Dynamics simulations** section and found in the ACBM results folder. Simulations from the **Identification of Potential Therapeutic Targets** session will be found in the FTW results folder.

[Supplementary 1](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_1.pdf): Parameters of the MOPS simulation with glycerol and acetate used in the **Dynamics simulations section**.

[Supplementary 2](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_2.csv): List containing the proteomes of the 457 gastrointestinal tract organisms from the NIH Human Microbiome Project (Human Microbiome Project Consortium 2012a; 2012b) that were compared with the remaining proteins after applying the coverage and identity filter mentioned in the **Identification of Potential Therapeutic Targets" section. of the methods**.

