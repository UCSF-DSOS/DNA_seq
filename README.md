# UCSF DSI Workshop: DNA Variant Analysis with R Bioconductor

Welcome to the UCSF Data Science Initiative's DNA-sequencing workshop. These materials rely on R Bioconductor packages and vignettes, with some customizations and added commentary. There are alternate ways to accomplish the same goals. This workshop provides a few examples and is intended to help attendees feel comfortable adapting these or other Bioconductor packages and examples in order to perform their own analysis.   

### Workshop details

Overview

In this workshop, we will use R to analyze DNA variants from Variant Call Format files to identify those likely to have a functional impact. It is intended for those with intermediate R programming skills. This is a 2-part hands-on workshop series that will take place virtually in two Zoom sessions.

Objectives

- Examine the header and metadata of a Variant Call Format (VCF) file  
- Select variants in genes of interest  
- Get transcripts and genotypes for selected variants  
- Locate regions of genes where variants fall (exons, introns, etc.)  
- Get the predicted impact of variants  
- Export variants to a Browser Extensible Data (BED) file and view in UCSC browser
- Perform pathway analysis on variants of interest

Prerequisites

You must have some R programming experience and a basic understanding of the purpose of DNA-Seq analysis to benefit from this course. Feel free to contact the instructor (see below) if you have questions about these requirements.

Software

Please have the latest versions of R and R Bioconductor installed if you plan to run the R notebooks locally. RStudio (the free version) is highly recommended as well, since we will be teaching in this environment.

    [Install R](https://cran.r-project.org/)
    [Install R Bioconductor](https://bioconductor.org/install/)
    [Install RStudio](https://www.rstudio.com/products/rstudio/download/#download)


### Official UCSF DSI Course Materials

Ready-to-use materials will always be hosted on our official UCSF Collaborative Learning Environment (CLE): [Official DSI DNA-seq workshop webpage](http://tiny.ucsf.edu/dsidnaseq).  

_This GitHub repository is for development purposes and therefore may stray from the materials used in class._ CLE will remain as it was at the time of our most recently offered workshop and will only be updated if major changes are introduced to the course.

Branch "master" should function as intended if cloned, but for verified materials please download all documents and data from CLE unless otherwise instructed.

Please contact the instructor if you have trouble installing packages locally:  
- Karla Lindquist: [karla.lindquist@ucsf.edu](mailto:karla.lindquist@ucsf.edu)



# GitHub and UCSF data security protocols:

Please be aware that **GitHub is not certified for use with personal health information (PHI).** Do not store or share any sensitive information via GitHub, even if kept in private repositories.

For more information regarding UCSF's security guidelines, [please see the UCSF IRB guidelines for electronic data security.](https://irb.ucsf.edu/electronic-data-security).
