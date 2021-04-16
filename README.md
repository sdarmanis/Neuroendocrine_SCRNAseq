# Import of adult mouse Neuroendocrine cell SMARTSeq2 data and Scrublet analysis for doublet removal

## Instructions

**1.** Clone this repo. On your terminal, navigate to a directory of your choosing *<dir>*
  
 ```
 cd <dir>
 git clone https://github.com/sdarmanis/Neuroendocrine_SCRNAseq.git
 ```

**2.** Download Input files from [here](https://drive.google.com/file/d/1OFf7VZ4FF3TCvygHHjXJsY3S1p22qW3i/view?usp=sharing) and move the .zip file inside the repo directory (which should be called *Neuroendocrine_SCRNAseq*). Unzip and remove .zip file. Now you should have a folder structure that looks like *<dir>/Neuroendocrine_SCRNAseq/*. In Neuroendocrine_SCRNAseq you should have: *input/* *scripts/* 

 ```
 cd <dir>/Neuroendocrine_SCRNAseq
 unzip input.zip
 rm input.zip
 ```

**3.** From within Rstudio open */scripts/NE01.Rmd* and start from importing data tables and metadata. You can generate the files needed for Scrublet analysis and then switch to the python notebook for running Scrublet. Once finished, switch back to R for importing Scrublet output and filtering doublets. 

**Note** Scrublet doublet analysis for the NE adult data is performed in *NE02_Scrublet_raw.Rmd* and *NE_scrublet_basics.ipynb*
