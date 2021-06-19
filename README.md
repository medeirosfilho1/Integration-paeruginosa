# Integrated Model of *Pseudomonas aeruginosa*

This repository provides supplementary material of the manuscript: **A systematic strategy to find potential therapeutic targets for *Pseudomonas aeruginosa* using integrated computational models.** 
##### Authos: Fernando Medeiros Filho\*, Ana Paula Barbosa do Nascimento, Maiana de Oliveira Cerqueira e Costa, Thiago Castanheira Merigueti, Marcio Argollo de Menezes, Marisa Fabiana Nicolás, Marcelo Trindade dos Santos, Ana Paula D’Alincourt Carvalho-Assef, Fabricio Alves Barbosa da Silva\*

# Abstract 

*Pseudomonas aeruginosa* is an opportunistic human pathogen that has been a constant global health problem due to its ability to cause infection at different body sites and its resistance to a broad spectrum of clinically available antibiotics. The World Health Organization classified multidrug-resistant *Pseudomonas aeruginosa* among the top-ranked organisms that require urgent research and development of effective therapeutic options. Several approaches have been taken to achieve these goals, but they all depend on discovering potential drug targets. The large amount of data obtained from sequencing technologies has been used to create computational models of organisms, which provide a powerful tool for better understanding their biological behavior. In the present work, we applied a method to integrate transcriptome data with genome-scale metabolic networks of *Pseudomonas aeruginosa*. We submitted both metabolic and integrated models to dynamic simulations and compared their performance with published in vitro growth curves. In addition, we used these models to identify potential therapeutic targets and compared the results to analyze the assumption that computational models enriched with biological measurements can provide more selective and(or) specific predictions. Our results demonstrate that dynamic simulations from integrated models result in more accurate growth curves and flux distribution more coherent with biological observations. Moreover, identifying  drug targets from integrated models is more selective as the predicted genes were a subset of those found in the metabolic models. Our analysis resulted in the identification of 26 non-host homologous targets. Among them, we highlighted five top-ranked genes based on lesser conservation with the human microbiome. Overall, some of the genes identified in this work have already been proposed by different approaches and(or) are already investigated as targets to antimicrobial compounds, reinforcing the benefit of using  integrated models as a starting point to selecting  biologically relevant therapeutic targets. 
 

Keywords: *Pseudomonas aeruginosa*, Metabolic  Network, Transcriptome  Data, Integrated Model, Therapeutic Target

Correspondence: fernando.filho@ioc.fiocruz.br, fabricio.silva@fiocruz.br 

# Description of the Supplementary Material

[Models](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/models): Here you can find the models used in the simulations performed in this manuscript. They are divided into matlab and sbml files. The .mat files were used in the **Integration of metabolic network and transcriptome data** and **Dynamics simulations** subsections of Materials and Methods section. The sbmls files were exported from matlab in order to simulate them in FindTargetsWeb in the **Identification of Potential Therapeutic Targets** methods section

[Simulations](https://github.com/medeirosfilho1/Integration-paeruginosa/tree/main/Simulations): In this folder you will find the results of growth simulations using the ACBM framework described in the **Dynamics simulations** subsection and found in the ACBM results folder. Simulations from the **Identification of Potential Therapeutic Targets** subsection will be found in the FTW results folder.

[Supplementary Table 1](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_table_1.xlsx): Parameters given as input for ACBM framework in the **Dynamics simulations** section.

[Supplementary Table 2](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_table_2.xlsx): List containing the the 454 gastrointestinal tract organisms from the NIH Human Microbiome Project mentioned in the **Identification of Potential Therapeutic Targets** subsection of Materials and Methos section.

[Supplementary Table 3](https://github.com/medeirosfilho1/Integration-paeruginosa/blob/main/Supplementary_table_3.xlsx): List of acetate and glycerol central metabolism reactions in P. aeruginosa PAO1 and their flux distribution mentioned in the **Flux Balance and Variability Analysis** subsection of Materials and Methods section.

