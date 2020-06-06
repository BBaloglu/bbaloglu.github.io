---
title: Projects
layout: page
sect: home
image: midge.png
display_img: False
---

Below is a list of my research projects. Links to my code repository and papers are included below. If you have trouble accessing data from our past studies, please let me know.

<hr style="margin-left: auto; margin-right: auto; width: 60%; color: #f2f2f2">

## Density based clustering and consensus error correction for Nanopore Sequencing 
[GitHub](https://github.com/bbaloglu/ashure) | [Preprint](https://www.biorxiv.org/content/10.1101/2020.05.21.108852v1.full.pdf)

Metabarcoding is a technique used to identify the species composition of a mixed sample using genes such as cytochrome oxidase I - CO1 or ribosomal RNA as taxonomic identifiers. Most metabarcoding studies have establish short read sequencing technologies. Oxford Nanopore MinION, a portable and low-cost sequencing device, is a promising alternative which can allow researchers to generate sequencing data in the field. These technologies have promising applications in ecological monitoring, outbreak tracking, and remote diagnostics. However, a major drawback is the high raw read error rate that can range from 10% to 22%.

Our study aimed to show nanopore sequencing can be a viable alternative to MiSeq in metabarcoding studies. We used rolling circle amplification (RCA) to generate concatemeric full-length DNA barcodes (658bp of cytochrome oxidase I - COI) from a bulk mock sample of 50 aquatic invertebrate species. Our analysis pipeline used density based clustering and consensus error correction to generate consensus reads which enabled identification of all 50 species in our mock community. Consensus read accuracy exhibited comparable sensitivity and accuracy to MiSeq. The use of RCA was integral for increasing consensus accuracy, but was the most time-consuming step in our molecular workflow and was inefficient at generating long concatemeric reads. Most RCA reads were skewed towards a shorter read length range with a median RCA fragment length of up to 1262bp. Nevertheless, our study demonstrates that Nanopore sequencing can be used for metabarcoding.

<img src="{{site.github_url}}/assets/img/ashure.jpg" style="width: 70%">

<hr style="margin-left: auto; margin-right: auto; width: 60%; color: #f2f2f2">


