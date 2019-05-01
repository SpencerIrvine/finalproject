# Final Project
## Introduction

This is a final project for the [Comparative Genomics](https://github.com/Yale-EEB723/syllabus) seminar in the spring of 2019. This project will explore the genetic differences between the Papionins.

## The goal

The specific problem I sought to explore was the amount of molecular divergence between Papionins. I want to quantify the number of base pair differences within mitochondrial genomes and estimate rate of molecular change between these genera.

## The data

The data are mitochondrial DNA sequences for the 7 genera in the tribe Papionini. 6 of the genera have complete mtDNA sequences of around 16,500 bp. There is not yet a complete mitochondrial genome of *Rungwecebus*, as it was only named in 2005 and not sequenced until 2006. Instead, the data include four genes that were used in the initial study that recognized it as a genetically distinct genus (Davenport et al., 2006; Olson et al., 2008).

- The data will be drawn from published genomic data on GenBank.
- Data structure: Nucleotide sequences from mitochondrial DNA

*Papio*: https://www.ncbi.nlm.nih.gov/nuccore/MG787545.1 (whole genome)

*Theropithecus*: https://www.ncbi.nlm.nih.gov/nuccore/FJ785426.1 (whole genome)

*Lophocebus*: https://www.ncbi.nlm.nih.gov/nuccore/KC757401.1 (whole genome)

*Mandrillus*: https://www.ncbi.nlm.nih.gov/nuccore/KT696596 (whole genome)

*Cercocebus*: https://www.ncbi.nlm.nih.gov/nuccore/KT159932 (whole genome)

*Rungwecebus*: https://www.ncbi.nlm.nih.gov/nuccore/DQ381473.1 (COX1 gene)
https://www.ncbi.nlm.nih.gov/nuccore/DQ381471 (COX2 gene)
https://www.ncbi.nlm.nih.gov/nuccore/GU068086.1 (ND4-ND5 genes, partial sequence)
https://www.ncbi.nlm.nih.gov/nuccore/GU068061.1 (12S ribosomal RNA gene, partial sequence)

The sequence data were downloaded as FASTA files.

## Background

The subtribe Papionina within the Old World Monkeys includes the mangabeys and the “baboons,” which includes baboons proper, mandrills and drills, and geladas. The phylogenetic relationships of these taxa are relatively unresolved, especially with the recent discovery of the kipunji, a newly described mangabey that was designated a new genus, *Rugwecebus* (Davenport et al., 2006). The current combined molecular and morphological phylogenies agree with the placement of *Cercocebus* (the semi-terrestrial mangabey) as the sister taxon to *Mandrillus*, but are uncertain about the relationships of *Lophocebus* (the arboral mangabey), *Papio*, *Theropithecus*, and *Rungwecebus*. Some molecular studies support a close phylogenetic relationship between *Papio* and *Rungwecebus* (Olson et al., 2008). Generalized phylogenies combining molecular and morphological results depict a polytomy (Gilbert et al., 2011). Other phylogenetic studies have used nuclear DNA (Perelman et al., 2011) and mitochondrial DNA (Finstermeier et al., 2013) to show Cercopithecine relationships, but without including the kipunji. More recent mitogenomic studies have included *Rungwecebus* in their phylogeny (Liedigk et al, 2014).


I was motivated to do this project because it seems unusual for there to be so much uncertainty in phylogenetic relationships, especially in such a familiar mammalian order such as Primates and with all of the advances in sequencing and phylogeneomics in the recent years. As such, it would be interesting to explore genetic-level differences between these taxa, which might help reveal their evolutionary relationships or explain why it has been difficult to resolve.


## Methods

Sequence data was downloaded as FASTA files from NCBI and imported into Geneious 2019 1.1, which was then used to analyze the data. I aligned the sequences and built phylogenetic trees using Geneious software. This data also gave me the number of basepair differences between the sequences.

I compared rates of nucleotide changes using divergence times from Finstermeier et al. (2013).



## Results
The number of differences in the mtgenomes follow the papionins' proposed evolutionary relationships. There is about 10% difference between the closely related sub-clades and 15% difference between the split within Papionina.

Based on the COX1 gene, *Rungwecebus* is most closely related to *Papio*, as other molecular studies have found (Olson et al. 2008).

The rate of accumulated basepair differences between the taxa, assuming *Papio* is the most nested within the clade, is greater at the base of the clade than at the tips.

## Assessment

Was it successful in achieving the initial goal?
I successfully compared the mitochondrial genomes of the 7 Papionin genera to determine the number of basepair differences between them and the rate of basepair changes. It was not the most in-depth analysis, but for my level of background, I got a lot out of this project. Getting experience working with genomic data (FASTA files) and using genomic analysis software (Geneious) was also a successful goal of mine for this course.


What are the main obstacles encountered?
Learning how to find and use the analysis software. I often didn't really know how to begin, so it took lots of troubleshooting. An issue I has with Geneious was that while I was able to align all of the *Rungwecebus* mitochondrial genes to the *Macaca* mtgenome, I was unable to concatenate the individual genes into one file for downstream analysis. Because of this, I was unable to use all of the *Rungwecebus* genomic data in my comparisons and to create the phylogenetic tree.


What would you have done differently?
Take more time to learn the software, and even try to learn how to do the analysis in R. For the analysis itself, I would have liked to get better estimates of the rates, as I'm not sure the values are biologically meaningful.


What are future directions this could go in?
This project could be expanded to include more Cercopithecines to better explain the patterns of divergence within the clade. It could also be expanded to nuclear genomes, as there would be have been more chances for differences to accumulate. This might make it easier to differentiate the Papio-Rungwecebus-Theropithecus-Lophocebus clade.



## References
Davenport, T. R., Stanley, W. T., Sargis, E. J., De Luca, D. W., Mpunga, N. E., Machaga, S. J., & Olson, L. E. (2006). A new genus of African monkey, *Rungwecebus*: morphology, ecology, and molecular phylogenetics. Science, 312(5778), 1378-1381.

Finstermeier, K., Zinner, D., Brameier, M., Meyer, M., Kreuz, E., Hofreiter, M., & Roos, C. (2013). A mitogenomic phylogeny of living primates. PLoS One, 8(7), e69504.

Gilbert, C. C., Stanley, W. T., Olson, L. E., Davenport, T. R., & Sargis, E. J. (2011). Morphological systematics of the kipunji (*Rungwecebus kipunji*) and the ontogenetic development of phylogenetically informative characters in the Papionini. Journal of human evolution, 60(6), 731-745.

Liedigk, R., Roos, C., Brameier, M., & Zinner, D. (2014). Mitogenomics of the Old World monkey tribe Papionini. BMC evolutionary biology, 14(1), 176.

Olson, L. E., Sargis, E. J., Stanley, W. T., Hildebrandt, K. B., & Davenport, T. R. (2008). Additional molecular evidence strongly supports the distinction between the recently described African primate *Rungwecebus kipunji* (Cercopithecidae, Papionini) and *Lophocebus*. Molecular phylogenetics and evolution, 48(2), 789-794.

Perelman, P., Johnson, W. E., Roos, C., Seuánez, H. N., Horvath, J. E., Moreira, M. A., ... & Schneider, M. P. C. (2011). A molecular phylogeny of living primates. PLoS genetics, 7(3), e1001342.

Pozzi, L., Hodgson, J. A., Burrell, A. S., Sterner, K. N., Raaum, R. L., & Disotell, T. R. (2014). Primate phylogenetic relationships and divergence dates inferred from complete mitochondrial genomes. Molecular phylogenetics and evolution, 75, 165-183.
