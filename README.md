# Final project "Identification of unknown plant" for NGS course

The project was done by the team of three MSc Skoltech students: <a href='https://github.com/Alisa411'>Alisa Fedorenko</a>, <a href='https://github.com/katikoshak'>Ekaterina Kashuk</a>, and <a href='https://github.com/lesidon'>Leonid Sidorov</a>.</i>

## Introduction

Some researches sequenced a genome of a plant specie which they were not able to identify be the morphological traits. The main goal of this project was to identify this specie using the NGS data. In order to complete this task, the following steps were done:

![image](https://github.com/lesidon/NGS_final_project/assets/122889154/e620fc9a-6583-4180-9a8f-485400e5d452)

The amount of data was not sufficient for the assembly of the complete nuclear genome but it was enough for high-copy genomic segments (plastid genomes, ribosomal RNA genes, mobile elements). These were used for the DNA-based identification.

<a href='https://github.com/lesidon/NGS_final_project/blob/main/NGS%20final%20project%20(2).pdf'>The final presentation</a> with the results of the analysis. We have successfully accomplished our goal: the unknown plant was <i>Epipogium aphyllum</i>, also known as Ghost orchid.

## Tools 
- Quality control: FastQC v. 0.11.9
- De Novo genome assembly: SPAdes genome assembler v3.15.5
- Homology search: makeblastdb v. 2.13.0+, blastn v. 2.13.0+
