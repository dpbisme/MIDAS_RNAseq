# MIDAS

## MInimal Directory for Analysis of Sequencing data

This directory was created as part of the course curriculum for the [DIYtranscriptomics](http://diytranscriptomics.com/) at PennVet, and provides a simple way to quickly set-up a clear and concise project directory structure for organizing a single RNAseq project. 

Here's how to get started:

1. Begin by dowloading and unzipping the 'MIDAS_RNAseq' folder on your computer (since you're reading this file, we can assume you are ready for step 2)

2. Change folder name from 'MIDAS_RNAseq' to something appropriate for your project

3. Open RStudio and fire up a new RStudio project inside the ```ANALYSIS/code``` directory

4. Keep your scripts from class in the ```ANALYSIS/code``` directory

5. Add your raw fastq files to the ```DATA/raw``` folder, and/or add your processed fastq files to the ```DATA/processed``` folder.

6. Download reference transcriptome files from [Ensembl](https://useast.ensembl.org/info/data/ftp/index.html) and place in ```ANALYSIS/readMapping```

7. When naming files, remember these basic rules:

* keep them human readable
* keep them machine readable
* make sure names play nice with your computer's default ordering

8. Replace the text in this project readme.md file with a detailed description of your project directory.  It should be sufficiently detailed so as to serve as a roadmap for someone else (or your future self) to guide them through all the files in your directory.
