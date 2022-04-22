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

###Finding FASTA sequences of the different species
###Using GenBank Features in the Artemis Software
