# Integrated Model of *Pseudomonas aeruginosa*

This repository provides supplementary material of the manuscript: **A systematic strategy to find potential therapeutic targets for *Pseudomonas aeruginosa* using integrated computational models.*** 
##### Authos: Medeiros Filho1†\*, Nascimento1†, Costa3, Merigueti1, Menezes4, Nicolás3, Santos3, Carvalho-Assef2, Silva1\*

######  1 Fundação Oswaldo Cruz, Programa de Computação Científica, Rio de Janeiro, RJ, Brazil; 2 Fundação Oswaldo Cruz, Instituto Oswaldo Cruz, Laboratório de Pesquisa em Infecção Hospitalar, Rio de Janeiro, RJ, Brasil; 3 Laboratório Nacional de Computação Científica, Petrópolis, RJ, Brazil; 4 Instituto de Física, Universidade Federal Fluminense, Niterói, RJ, Brazil; † These authors have contributed equally to this work and share first authorship; \* Correspondence authors

# Abstract 

*Pseudomonas aeruginosa* is an opportunistic human pathogen that has been a constant global health problem due to its ability to cause infection at different body sites and its resistance to a broad spectrum of clinically available antibiotics. The World Health Organization classified *Pseudomonas aeruginosa* among the top-ranked organisms that require urgent research and development of effective therapeutic options. Several approaches have been taken to achieve these goals, but they are all dependent on discovering  potential drug targets. The large amount of data obtained from sequencing technologies has been used to create computational models of organisms, which provide a powerful tool for better understanding their biological behavior. In the present work, we applied a method to integrate transcriptome data with genome-scale metabolic networks of *Pseudomonas aeruginosa*. We submitted both metabolic and integrated models to dynamic simulations and compared their performance with in vitro growth curves. In addition, we used these models to identify potential therapeutic targets and compared the results to analyze the assumption that computational models enriched with biological measurements can provide  more selective and(or) specific predictions. Our results demonstrate that dynamic simulations from integrated models result in more accurate growth curves and flux distribution more coherent with biological observations. Moreover, identifying  drug targets from integrated models is more selective as the predicted genes were a subset of those found in the metabolic models. Our analysis resulted in the identification of 26 non-host homologous targets. Among them, we highlighted five top-ranked genes based on lesser conservation with the human microbiome. Overall, some of the genes identified in this work have already been proposed by different approaches and(or) are already investigated as targets to antimicrobial compounds, reinforcing the benefit of using  integrated models as a starting point to selecting  biologically relevant therapeutic targets. 

Keywords: *Pseudomonas aeruginosa*, Metabolic  Network, Transcriptome  Data, Integrated Model, Therapeutic Target

Correspondence: fernando.filho@ioc.fiocruz.br, fabricio.silva@fiocruz.br 

# Description of supplementary material

[Models](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/models): Here you can find the models used in the simulations performed in this manuscript. They are divided into files with matlab and sbml extensions. The .mat files were used in the session **Integration of metabolic network and transcriptome data** and **Dynamics simulations** of the methods. The sbmls files were exported from matlab in order to simulate them in FindTargetsWeb in the **Identification of Potential Therapeutic Targets** methods section

[Simulations](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/Simulations): In this folder you will find the results of simulations referring to growth curves using the TRFBA algorithm described in the **Dynamics simulations** section and found in the ACBM results folder. Simulations from the **Identification of Potential Therapeutic Targets** session will be found in the FTW results folder.

[Supplementary 1](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_1.pdf): Parameters of the MOPS simulation with glycerol and acetate used in the **Dynamics simulations section**.

[Supplementary 2](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_2.csv): List containing the proteomes of the 457 gastrointestinal tract organisms from the NIH Human Microbiome Project (Human Microbiome Project Consortium 2012a; 2012b) that were compared with the remaining proteins after applying the coverage and identity filter mentioned in the **Identification of Potential Therapeutic Targets" section. of the methods**.

