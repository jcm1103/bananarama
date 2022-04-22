# bananarama

##add channels to look for programs
conda config --add channels bioconda
conda config --add channels conda-forge

###create my environment 
conda create -n bananarama python bwa fastqc

###activate environment
conda activate bananarama

##found fasta files for all the banana species we are looking at 
##Musa acuminata, Musa schizocarpa, Musa itinerans 

##possible conda application to use to analyze genome 
conda config --add channels bioconda     (to add the bioconda channel)
conda config --add channels conda-forge  (to add the conda-forge channel)
conda install artemis

##what is ACT? 
"The Artemis Comparison Tool (ACT) allows an interactive visualisation of comparisons between complete genome sequences and associated annotations.  It is possible to identify regions of similarity, insertions and rearrangements at any level from the whole genome to base-pair differences." https://academic.oup.com/bioinformatics/article/21/16/3422/216339?login=true

##We are switching to Prairie Warblers because the banana DNA didn't have enough information for what we wanted to do.

Download R
 conda install r-base--> did not open R so different commands were used
 
 Try new installation of R within conda 
  1) conda create -n r_env r-essentials r-base --> create new conda environment 
 
  2) conda activate r_env --> activate environment 
 
  3) R --> to open r 

##Next steps are to run a DAPC and Isolation by Distance for Prairie Warblers in New England
 
