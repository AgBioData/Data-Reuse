# Data-Reuse
## Community-curated guidlines to increase dataset reuse potential

**The following guidelines, checks and protocol documenting from the side of the data producer can add significant value to datasets for data reuse:**

### 1. ACCESSING THE DATASET
* Include and double-check all links to data repositories in submitted manuscript and proofread before publication
* Avoid “Contact corresponding author for data” statements. 
* Make sure the raw and processed datasets are saved in an accessible location (preferably with redundancy) for the corresponding author to share if needed
* When possible, include sample names and identifier information to data file names for ease of access (in addition to GEO names) 
* Clearly state any applicable ownership rights

### 2. ASSESSING REUSE SUITABILITY
* Clearly state how the data was generated
* Document in detail the sample type and collection methods:
      * Developmental stage, 
      * Organ/tissue/cell types (can include illustrations), 
      * Time of sampling, 
      * Sample storage,
      * Sample preparation,
      * Other pertinent details. 
* Specify whether the sequence was generated from single-end or paired-end sequencing. 
* Make sure to differentiate which sample sequences are biological replicates and which are technical replicates within different sequencing lanes.
* Indicate the type of sequencing chemistry employed, such as Illumina or ONT, and include all relevant technology information.
* Provide comprehensive information about the bioinformatics software used, including specific steps involved in the analysis. 
* If possible, provide a link to the used code on GitHub or other platform, avoid “Contact corresponding author for used custom code” statements.
* Include a data key indicating the relationship between the sample metadata and the data location in the public repository.

### 3. FORMATING 
* Do not upload large amounts of raw or processed data only in the supplementary files, make sure it is deposited to the appropriate repository (i.e., avoid .csv, .tsv, .pdf for sequencing data). 
* Use the most common format for the data type and make different formats available when possible (e.g., FASTAQ and .GFF3)
* Think about what formats the dataset would most likely need to be interconverted in order to be (re)used and provide that format.
* Utilize published metadata format standards for that file format, if available. 

### 4. SKILLS AND RESOURCES (for data producer and reuser)
* Do you have the storage capacity to store the dataset(s)?
* Do you have the computational power to reuse/analyze the datasets?
* Do you have the computational skills to reuse/analyze the datasets?
If the answer to any of the questions above is no, seek assistance from your institution and colleagues. Universities often have cluster cloud computing capabilities. Seek education in the form of computational biology and bioinformatics courses, many can be found online. 


