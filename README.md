# Biodiversity Informatics Resources


**Michelle L. Gaynor**   


# Introduction  

Here I provide a round-up of biodiversity informatic resources I have created or contributed to.  


## Contributions
Contributions are indicated on each script/repository, but to summarize, contributions to these script or presentations have been made by many, including but not limited to: [Natalie Patten](https://github.com/nataliepatten), [Mike Belitz](https://github.com/mbelitz), [Rhett Rautsaw](https://github.com/RhettRautsaw), Maria Cortez, [Andre Naranjo](https://github.com/aanaranjo), [Lauren Whitehurst](https://github.com/laurenwhitehurst21), [Anthony Melton](https://github.com/meltonae), [Johanna Jantzen](https://github.com/jjantzen), Blaine Marchant, Charlotte Germain-Aubrey, Grant Godden, Doug Soltis, and Pam Soltis. 

## Where to start:
If you are new to R-based coding, I suggest you start with [my Biodiversity Literacy in Undergraduate Education (BLUE) module here](http://mlgaynor.com/BLUE-Intro2RwithBiodiversityData/_book/general-information.html). My coding style is a mix of [Data Carpentry](https://datacarpentry.org/) and [tidyverse](https://www.tidyverse.org/learn/), both of which have additional tutorials that can be used to learn this material.  
    

# Resources   

**[soltislab/BotanyENMWorkshop](https://github.com/soltislab/BotanyENMWorkshops)**    
<img align="right" src="ENMCrashCourseHex.png" width=150>   

 

This repository contains workshop material for "Using Digitized Collections-Based Data in Research: Applications for Ecology, Phylogenetics, and Biogeography" which the Soltis lab presents at the annual Botany meetings. This contains the material used in the 2020, 2021, 2022, and 2023. This workshop was often done in conjuction with Biotaphy, so this repository contains material outside of the scope of my work. As an undergraduate in 2017, I learned all about ENMs with biodiversity occurrence data from Blaine Marchant. When I started as a graduate research assistant with iDigBio in Fall 2018, I started to modify this material to include new methods I was learning. With every additional workshop/course/office-hour I helped lead, I learned something new that I would incorporate into this material. In Spring 2020 and Summer 2021, I heavily revised this material so that it could be used by undergraduate researchers. In Summer 2022 and 2023, I modified this material to include our package gatoRs. This workshop will likely be updated every summer, as we present the "Using Digitized Collections-Based Data in Research: Applications for Ecology, Phylogenetics, and Biogeography" workshop at the annual Botany meeting each year. You can see the [latest workshop version here](https://github.com/soltislab/BotanyENMWorkshops). 

A version of the workshops can also be found in [mgaynor1/ENMCrashCourse](https://github.com/mgaynor1/ENMCrashCourse), however this repository is now outdated and likely will be archieved. 

![General Flowchart](Gaynorcrop.png)     

<img align="right" src="gators.png" width=150> 

**[nataliepatten/gatoRs](https://github.com/nataliepatten/gatoRs)**     

This repository contains the R package gatoRs: Geographic and Taxonomic Occurrence R-Based Scrubbing which  provides users with tools for downloading and processing biodiversity data. This package is also avaliable on CRAN.   

See publication: Patten NN, Gaynor ML, Soltis DE, and Soltis PS. 2024. Geographic and Taxonomic Occurrence R-Based Scrubbing (gatoRs): An R package and reproducible workflow for processing biodiversity data. 

         


**[mgaynor1/CURE-FL-Plants](https://github.com/mgaynor1/CURE-FL-Plants)**       
In Spring 2020, I helped teach a Course-based undergraduate research experience at the University of Florida titled 'CURE: Florida Plants and Climate Change'. This class was a 3 credit undergraduate course and it was co-taught with Pam and Doug Soltis. The goal of this research was to look at how climate change would impact the distribution of rare and endangered species currently residing at [Archbold Biological Station](https://www.archbold-station.org/html/lnkpgs/archlistedsp.html). This repository contains demo and project scripts, which are written in a way to loop through a long list of species. Much of these methods are still acceptable, however since this class, I improved this pipeline to defined accessible area with alpha hulls + buffers, rather than convex hulls. I also modified my methods for selecting climatic layers, ecological niche generation, and ecological niche model evaluation. Some of these scripts have also been shortened or simplified by an amazing undergraduate researcher NN Patten.

    
**[mgaynor1/R4NaturalHistoryCollections-BCEENET2021](https://github.com/mgaynor1/R4NaturalHistoryCollections-BCEENET2021)**       
In 2021, I taught a workshop with BCEENET on "Using R for dNHC (Digitized Natural History Collections) Research". This workshop reviews cleaning, mapping, and analyzing natural history collections data in R. It also reviewed point sampling and extracting elevation data from occurrence records, as well as how to run an ANOVA based on this data. 

    
**[mgaynor1/long-winded-scripts](https://github.com/mgaynor1/long-winded-scripts)**       
Over the last few years, I generated many scripts related to using Digitized Natural History Collections data in research. This repository is a collection of some of those scripts, specifically those that took me a large amount of time to put together in R and python. 
- Occurrence Data (R).
      -    This is the first draft of a function that will be part of Natalie's R package gatoRs - this script has since been completely rewritten. 
- SoilGridDownload (python3).
      -   Back when [Max Gebhart](https://github.com/maxg483) was an undergrad at the University of Central Florida, we wanted soil layers included in our ENMs. With the help of Mike Belitz, this code was generated. You can see some of [Max's work here](https://github.com/maxg483/ENM-of-Helianthus). 
- Convex Hulls (R).
      -    This code was generated for a post doc in the Soltis lab who had a question about convex hulls.
- iDigBio Search Bar (R).
      -   Using ridigbio, I wanted to match a simple search from the iDigBio web-portal. This sounds simple, right? Well, it took a long time, but this simple line of code is now avaliable.
       
      
**[mgaynor1/BLUE-Intro2RwithBiodiversityData](https://github.com/mgaynor1/BLUE-Intro2RwithBiodiversityData)**.     
In 2020, I participated in a BIOME Fall Working Group and generated this module. This is an open educational resource which can be cited as followed: Gaynor, M. (2020). Introduction to R with Biodiversity Data. Biodiversity Literacy in Undergraduate Education, QUBES Educational Resources. doi:10.25334/84FC-TE88  

With this material, students will learn R basics while downloading biodiversity data from multiple data repositories. This module will walk students through installing R, navigating R, reproducibility in R, and using R to download biodiversity data.


**[mgaynor1/BCEENET-DataCleaning](https://github.com/mgaynor1/BCEENET-DataCleaning)**              
In Summer 2020, I helped lead a Data Cleaning Workshop led with Pam Soltis for BCEENET. With the help of Molly Philips, this can be cited as an open educational resource: Gaynor, M. (2020). Cleaning Biodiversity Data: A Botanical Example Using Excel or RStudio. Biodiversity Literacy in Undergraduate Education, QUBES Educational Resources. doi:10.25334/DRGD-F069.
      
Upon completion of this module, each student should be able to: (1) Access biodiversity data from open sources. (2) Use descriptive, retrievable, and consistent file names to manage datasets. (3) Identify common problems with digital datasets. (4) Rectify common problems with digital datasets. (5) Apply disciplinary knowledge for smart data cleaning. (6) Explain the importance of reproducible data and cleaning steps. (7) Document data cleaning steps to provide reproducibility.     
     
**[iDigBio API Working Group](https://biodiversity-specimen-data.github.io/specimen-data-use-case/)**   
From 2019 - 2021, I helped host the API Office Hours with Erica Krimmel and Ron Canepa (iDigBio). There are a lot of resources avaliable on this repository, but some of my contributions include:     
- [Round-up of Biodiversity Aggregators](https://biodiversity-specimen-data.github.io/specimen-data-use-case/AggregatorsTable)     
- [Overview of iDigBio's Download API](https://biodiversity-specimen-data.github.io/specimen-data-use-case/Download_API_example)  
- [Demo: Downloading records within a Bounding Box](https://biodiversity-specimen-data.github.io/specimen-data-use-case/BoundingBox.html)  

Ron and Erica also created some great demos/resources. Here are just some of my favorite:     
- [Erica's Demo: Basic Overview of the ridigbio package](https://biodiversity-specimen-data.github.io/specimen-data-use-case/solution/demo_ridigbio_overview.html)
- [Erica's Demo: How to identify specimen records with suspicious coordinate data, using R and iDigBio](https://biodiversity-specimen-data.github.io/specimen-data-use-case/solution/identify-suspicious-coordinate-data.html)
- [David Jennings Demo: Report Metrics for Collections from an Institution](https://biodiversity-specimen-data.github.io/specimen-data-use-case/solution/report-institution-metrics_jsonlite.html)     
- [Erica's Demo: How to find tissue samples using R and iDigBio](https://biodiversity-specimen-data.github.io/specimen-data-use-case/solution/find-tissue-samples_ridigbio.html)     


**Gists**  
Short snibits of code I generated related to using Digitized Natural History Collections data in research.
- [Searching the ScientificName Field](https://gist.github.com/mgaynor1/8231646b6614c29d384a387ce6731e7b)
    - Compares three approaches for retrieving records from iDigBio based on the scientificname field.
- [Milton Tan](https://gist.github.com/mgaynor1/86cf5e5d741e3aa8a1a61c52bd667eb7)        
      - Milton wanted to know how to download records with the ridigbio API based on Institution ID and Catelog Number.   
- [spocc_combine loop](https://gist.github.com/mgaynor1/f51b6735afc442f1338f244e6e0f9a9a)     
      - One of my lab mates wanted to know how to use the spocc_combine function (which is an early edition of the gator_download() function) for a list of species. This gist shows how.     
- [SERNEC-R](https://gist.github.com/mgaynor1/fe89d841b8768f2c4556d9fe6433079a)        
      - We wanted to combined data downloaded via SERNEC with data download using early functions of the gators R package functions.        

# Folk and Gaynor et al. 2023  

I had the opportunity to work with Ryan Folk on this fun project which resulted in many repositories related to biodiversity informatics:

- [mgaynor1/Paleogenerate](https://github.com/mgaynor1/PaleoGenerate) - R scripts to generate Bioclim variables at time points between 0 and 3.3 million years ago (MYA).
- [ryanafolk/utremi](https://github.com/ryanafolk/utremi) - Manuscript repository which includes application of [predicted niche occupancy ancestral reconstruction using a maximum-likelihood-based approach](https://github.com/biotaphy/BiotaPhyPy/blob/main/biotaphy/tools/ancestral_distribution.py). 
- [ryanafolk/spatial_utilities](https://github.com/ryanafolk/spatial_utilities) - Utility scripts by Ryan Folk.
- [ryanafolk/pno_calc](https://github.com/ryanafolk/pno_calc) - Predicted niche occupancy calculation by Ryan Folk.
- [ryanafolk/tree_utilities/blob/master/simulate_gene_trees.py](https://github.com/ryanafolk/tree_utilities/blob/master/simulate_gene_trees.py) - Gene tree simulation by Ryan Folk.

Folk RA*, Gaynor ML*, Engle-Wrye NJ, O’Meara BC, Soltis PS, Soltis DS, Guralnick RP, Smith SA, Grady CJ, & Okuyama Y. 2023. Identifying climatic drivers of hybridization with a new ancestral niche reconstruction method. [Systematic Biology, syad018](https://doi.org/10.1093/sysbio/syad018)

# ridigbio documentation 

In January 2023, I updated the documentation for [ridigbio](https://cloud.r-project.org/web/packages/ridigbio/index.html) and added [a pkgdown site](https://idigbio.github.io/ridigbio/index.html). 

# Others Resources
- [QGIS Introduction - RhettRautsaw/GIS_Tutorial](https://github.com/RhettRautsaw/GIS_Tutorial)
- [SDM Best Practices](https://github.com/plantarum/sdm-best-practices/wiki)
- [mbelitz/Odo_SDM_Rproj](https://github.com/mbelitz/Odo_SDM_Rproj)
- [richiehodel/Amborella_ENM](https://github.com/richiehodel/Amborella_ENM)
- [jjantzen/CommPhylogeneticsOSBS](https://github.com/jjantzen/CommPhylogeneticsOSBS)
- [aemelton/EA_ENA_ENM](https://github.com/aemelton/EA_ENA_ENM)
- [ryanafolk/ambitus](https://github.com/ryanafolk/ambitus)
- [ryanafolk/eco-discretizer](https://github.com/ryanafolk/eco-discretizer)
- Check out Max Gebhart's Master research: Gebhart, M.G. and Wersal, R.M., 2023. Ecological niche modeling of diploid flowering rush (Butomus umbellatus L.) in the United States. [Journal of Freshwater Ecology, 39(1), p.2292232.](https://doi.org/10.1080/02705060.2023.2292232)



      
  
