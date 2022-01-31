# WebSeq: A Genomic Data Analytics Platform for Monogenic Disease Discovery

If you find WebSeq useful for your research, please cite the following [paper](https://www.biorxiv.org/content/10.1101/2021.11.16.460500v1 ): <br>
```
  WebSeq: A Genomic Data Analytics Platform for Monogenic Disease Discovery 
  Milind Agarwal, Kshitiz Ghimire, Joy D. Cogan, Undiagnosed Disease Network, Janet Markle 
  bioRxiv 2021.11.16.460500; doi: https://doi.org/10.1101/2021.11.16.460500 
  URL: https://www.biorxiv.org/content/10.1101/2021.11.16.460500v1 
```

Whole exome sequencing (WES) is commonly used to study monogenic diseases. The application of this sequencing technology has gained in popularity amongst clinicians and researchers as WES pricing has declined. The accumulation of WES data creates a need for a robust, flexible, scalable and easy-to-use analytics platform to allow researchers to gain biological insight from this genomic data. <br>

We present WebSeq, a self-contained server and web interface to facilitate intuitive analysis of WES data. WebSeq provides access to sophisticated tools and pipelines through a user-friendly and modern web interface. <br>

WebSeq has modules that support:<br>
  1. FASTQ to VCF conversion, <br>
  2. VCF to ANNOVAR CSV conversion, <br>
  3. family-based analyses for Mendelian disease gene discovery, <br>
  4. cohort-wide gene enrichment analyses, <br>
  5. an automated IGV browser, and <br>
  6. a ‘virtual gene panel’ analysis module. <br>
  
WebSeq Pro, our expanded pipeline, also supports SNP genotype analyses such as:<br>
  1. ancestry inference <br>
  2. kinship testing <br>
  
WebSeq Lite, our minimal pipeline, supports family-based analyses, cohort-wide gene enrichment analyses, and a virtual gene panel along with the IGV browser module. <br>

We anticipate that the rigorous use of our web application will allow researchers to expedite discoveries from human genomic data. WebSeq Lite, WebSeq, and WebSeq Pro are fully containerized using Docker, run on all major operating systems, and are freely available for personal, academic, and non-profit use at http://bitly.ws/g6cn <br>

