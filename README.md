# Final Project

## Instructions

This repository is a stub for your final project. Fork it as a template for your project, and develop your code in the forked repository. After you fork the repository, please enable the issue tracker in the repository settings so that others in the class (including the professor) can provide feedback. To submit the project, send a pull request to the original repository.

Expand on the readme questions below to provide an overview of the goals, background, and challenges for the final project. You can delete the questions as you write text that answers them, or leave the prompts in place. You can also delete this instruction section of you like.

Add all code to your project repository, including shell scripts, R analyses, python, etc.

Do not commit large data files to the repository. Provide paths to where they can be downloaded if they
are from public sources, or track them with [git-lfs](https://git-lfs.github.com).

## Introduction

This is a final project for the [Comparative Genomics](https://github.com/Yale-EEB723/syllabus) seminar in the spring of 2019. This project will explore the genetic differences between the Papionins.

## The goal

The specific problem I sought to explore was the amount of molecular divergence between Papionins. I want to quantify to rate of molecular change between these genera.

## The data

The data are mitochondrial whole genome sequences for the 6 genera in the tribe Papionina. The *Rungwecebus* genome is not whole, but includes two genes that were used in the initial study that recognized it as a genetically distinct genus (Davenport et al., 2006).

- The data will be drawn from published genomic data on GenBank.
- Data structure: Nucleotide sequences from mitochondrial DNA

*Papio*: https://www.ncbi.nlm.nih.gov/nuccore/MG787545.1

*Theropithecus*: https://www.ncbi.nlm.nih.gov/nuccore/FJ785426.1

*Lophocebus*: https://www.ncbi.nlm.nih.gov/nuccore/KC757401.1

*Mandrillus*: https://www.ncbi.nlm.nih.gov/nuccore/KT696596

*Cercocebus*: https://www.ncbi.nlm.nih.gov/nuccore/KT159932

*Rungwecebus*: https://www.ncbi.nlm.nih.gov/nuccore/DQ381471  
https://www.ncbi.nlm.nih.gov/nuccore/DQ381473.1

## Background
What the reader needs to know to understand the project
The subtribe Papionina within the Old World Monkeys includes the mangabeys and the “baboons,” which includes baboons proper, mandrills and drills, and geladas. The phylogenetic relationships of these taxa are relatively unresolved, especially with the recent discovery of the kipunji, a newly described mangabey that was designated a new genus, *Rugwecebus* (Davenport et al., 2006). The current combined molecular and morphological phylogenies agree with the placement of *Cercocebus* (the semi-terrestrial mangabey) as the sister taxon to *Mandrillus*, but are uncertain about the relationships of *Lophocebus* (the arboral mangabey), *Papio*, *Theropithecus*, and *Rungwecebus*. Some molecular studies support a close phylogenetic relationship between *Papio* and *Rungwecebus* (Olsen et al., 2008). Generalized phylogenies combining molecular and morphological results depict a polytomy (Gilbert et al., 2011). Other phylogenetic studies have used nuclear DNA (Perelman et al., 2011) and mitochondrial DNA (Finstermeier et al., 2013) to show Cercopithecine relationships, but without including the kipunji. More recent mitogenomic studies have included *Rungwecebus* in their phylogeny (Liedigk et al, 2014).


Motivation for the project....
It seems unusual for there to be so much uncertainty in phylogenetic relationships, especially in such a familiar mammalian order such as Primates and with all of the advances in molecular phylogenies in the recent decades. It would be interesting to explore the genetic difference between these taxa, which might help reveal their evolutionary relationships.
How it fits in with other work...


## Methods
Compare frequency of nucleotide changes
Compare rates of nucleotide changes using divergence times from Perelman et al. (2011) Finstermeier et al. (2013).
Use BLAST and MITOS (http://mitos2.bioinf.uni-leipzig.de/index.py) to analyze the mtDNA.



## Results


## Assessment

Was it successful in achieving the initial goal?

What are the main obstacles encountered?

What would you have done differently?

What are future directions this could go in?

## References
Davenport, T. R., Stanley, W. T., Sargis, E. J., De Luca, D. W., Mpunga, N. E., Machaga, S. J., & Olson, L. E. (2006). A new genus of African monkey, Rungwecebus: morphology, ecology, and molecular phylogenetics. Science, 312(5778), 1378-1381.

Finstermeier, K., Zinner, D., Brameier, M., Meyer, M., Kreuz, E., Hofreiter, M., & Roos, C. (2013). A mitogenomic phylogeny of living primates. PLoS One, 8(7), e69504.

Gilbert, C. C., Stanley, W. T., Olson, L. E., Davenport, T. R., & Sargis, E. J. (2011). Morphological systematics of the kipunji (Rungwecebus kipunji) and the ontogenetic development of phylogenetically informative characters in the Papionini. Journal of human evolution, 60(6), 731-745.

Liedigk, R., Roos, C., Brameier, M., & Zinner, D. (2014). Mitogenomics of the Old World monkey tribe Papionini. BMC evolutionary biology, 14(1), 176.

Olson, L. E., Sargis, E. J., Stanley, W. T., Hildebrandt, K. B., & Davenport, T. R. (2008). Additional molecular evidence strongly supports the distinction between the recently described African primate Rungwecebus kipunji (Cercopithecidae, Papionini) and Lophocebus. Molecular phylogenetics and evolution, 48(2), 789-794.

Perelman, P., Johnson, W. E., Roos, C., Seuánez, H. N., Horvath, J. E., Moreira, M. A., ... & Schneider, M. P. C. (2011). A molecular phylogeny of living primates. PLoS genetics, 7(3), e1001342.

Zinner, D., Wertheimer, J., Liedigk, R., Groeneveld, L. F., & Roos, C. (2013). Baboon phylogeny as inferred from complete mitochondrial genomes. American journal of physical anthropology, 150(1), 133-140.
