---
title: Research
layout: misc
sect: home
image: seg.png
---

Below is a list of my research projects. Links to my code repository and papers are included below. If you have trouble accessing data from our past studies, please let me know.

<hr style="margin-left: auto; margin-right: auto; width: 60%; color: #f2f2f2">

## Density based clustering and consensus error correction for Nanopore Sequencing 
[GitHub](https://github.com/bbaloglu/ashure)
[Preprint](https://www.biorxiv.org/content/10.1101/2020.05.21.108852v1.full.pdf)

Metabarcoding has become a common approach to the rapid identification of the species composition in a mixed sample. The majority of studies use established short-read high-throughput sequencing platforms. The Oxford Nanopore MinION, a portable sequencing platform, represents a low-cost alternative allowing researchers to generate sequence data in the field. However, a major drawback is the high raw read error rate that can range from 10% to 22%.

To test if the MinION™ represents a viable alternative to other sequencing platforms, we used rolling circle amplification (RCA) to generate full-length consensus DNA barcodes (658bp of cytochrome oxidase I - COI) for a bulk mock sample of 50 aquatic invertebrate species.
. We were able to show that it is possible to reduce error rates to a median accuracy of up to 99.3% for long RCA fragments (>45 barcodes). Our pipeline successfully identified all 50 species in the mock community and exhibited comparable sensitivity and accuracy to MiSeq. The use of RCA was integral for increasing consensus accuracy, but it was also the most time-consuming step during the laboratory workflow and most RCA reads were skewed towards a shorter read length range with a median RCA fragment length of up to 1262bp. Our study demonstrates that Nanopore sequencing can be used for metabarcoding but we recommend the exploration of other isothermal amplification procedures to improve consensus length.

<img src="{{site.github_url}}/assets/img/ashure.jpg" style="width: 70%">

<hr style="margin-left: auto; margin-right: auto; width: 60%; color: #f2f2f2">

