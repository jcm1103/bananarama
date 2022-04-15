# bananarama

##add channels to look for programs
conda config --add channels bioconda
conda config --add channels conda-forge

###create my environment 
conda create -n bananarama python bwa fastqc

###activate environment
conda activate bananarama

##found fasta files for all the banana species we are looking at 
## Musa acuminata, Musa schizocarpa, Musa itinerans 

