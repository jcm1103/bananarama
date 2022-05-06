# Gen711 Final Project- Prairie Warbler Populations
## Background
We chose to examine the population structure of 195 Prairies Warblers at 10 different sites. This project was of interest, as two members of the group, Alexa Aubrey and Brighid Lamprey, work as undergraduate researchers in Adrienne Kovach's lab, examining Prairie Warbler populations. This is a study of importance as Prairie Wrabler populations are declining due to habitat destruction, so there is a need for conservation. A key aspect of conservation efforts is to identify whether different populations can be managed as one or if they should be managed separately, which can be determined by examining genetic diversity amongst populations at different sites. In this abbreviated study, the sites we chose to examine were six local New Hampshire sites (Bow Bog, Destiny Way Gravel pit, Old Mill Lee Power Line, Peter's Gravel pit, Severino, and Woodhill), and one site from Maine (Bills Lane/Perry Oliver), Massachusetts, New York, and Arkansas. The sites were selectively chosen as they represent the location of Prairie Warbler populations within our home states, with Arkansas as an outlier to examine if there was increased genetic diversity based on geographical distance. The samples used were collected from collaborators and from Kovach's lab where they underwent DNA extraction and PCR amplification with 11 different microsatellites. From the data collected, a Discriminate Analysis of Principal Components (DAPC) and an Isolation By Distance with Mantel test were run. The DAPC was performed to explore the structure of Prarie Warbler populations without making assumptions of Panmixia (random mating) and the Isolation by Distance was performed to determine correlation between genetic distance and geographic distance, which was represented by a slope value.

## Methods
Blood samples were taken from Prairie Warblers at multiple sampling sites. PCR products of microsatellite loci were analyzed using fragment analysis. Alleles were scored using PeakScanner​ and entered into Google Sheets. Calls were binned using analysis completed independently by Melissa Bauer, Alexa Aubrey, and Brighid Lamprey. R Console/RStudio and the ‘adegenet’ package were installed. A structure file was created to determine the number of PCAs and DAs to keep. A DAPC was run. The structure file was used to create a genetic distance matrix. A Mantel Test was run and an IBD plot was created.

do we need to put script here?? errors??


## Findings
![plot](figures/PRAW_DAPC_Final.png) 

Figure 1. DAPC (Discriminate Analysis of Principal Components) visualizing genetic variation among sampled locations. Symbols correspond to unique sample sites. The plot indicates little spatial patterns.


![plot](figures/DAPC_Cross_Validation.png)

Figure 2. 

![plot](figures/DAPC_Cross_Validation_2.png)

Figure 3.


![plot](figures/IBD_Plot_PRAW.png)

Figure 4. Isolation by Distance test against genetic distance and geographic distance for 9 out of the 10 Prairie Warbler Sites. Arkansas (AR) was dropped from this test since it was the geographic outlier.

## Conclusion
Due to the clustering pattern of shown on the DAPC we see that there is a high genetic diversity between populations. As seen in the Isolation by Distance, we can tell that the genetic variation is not due to geographic distance since the P-value is high and the Correlation Coefficient is negative, supporting that the populations can be treated and managed as one.

## Presentation 
A google slides was made.
