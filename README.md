# Adaptive-deprivation-EU-SILC

## Aims
The aim of this project is to show how adaptive deprivation scales can be applied in the context of a measure which is being implemented across multiple countries with very contrasting levels of poverty and deprivation. Adaptive scales aim to collect data from survey respondents in much less time and with minimal loss of information. Specifically we examine how this approach would perform in relation to the EU's new child deprivation scale using data from the EU-SILC. 

## Outputs
The results from this stage of the work have been accepted for publication by the journal 'Child Indicators Research' (May 2022). A pre-print is available on SocArxiv (https://doi.org/10.31235/osf.io/mvqnf - open access)

## Previous work
This work builds on an earlier project which first showed how adaptive deprivation scales could be successfully deployed in the context of a single country, the UK. Code for that work is available here: https://github.com/nick-bailey/Adaptive-deprivation-measure. Results were published in the journal 'Social Indicators Research' (https://doi.org/10.1007/s11205-020-02283-1 - open access). 

## Data
Data for the EU-SILC were obtained under license from Eurostat by following their standard procedures. The license conditions prevent onward sharing of the data but other researchers can obtain the same data in the same way. 

The published version of the paper used the first release of the data: 
Eurostat (2020) EU-Statistics on Income and Living Conditions microdata 2004-2018, release 2020, version 1 [dataset]. Eurostat. https://doi.org/10.2907/EUSILC2004-2018V.1

In finalising the code and producing figures for this repository, the second release version was used, resulting in some very minor differences compared with the published figures: 
Eurostat (2021) EU-Statistics on Income and Living Conditions microdata 2004-2020, release 2021, version 1 [dataset]. Eurostat. https://doi.org/10.2907/EUSILC2004-2020V.1

## Code
Dataset preparation and analysis was done using R (R Core Team, 2013) with packages ‘dplyr’ (Wickham et al 2019), ‘tidyverse’ (Wickham 2017), and ‘ltm’ (Rizopoulos 2006). To produce the figures here, we used the versions current at May 2022. We include code to produce the results in the paper, covering the 27 countries of the EU. We also include code to run the analysis for the 31 countries providing data to the EU-SILC in 2014. 

## Figures
The figures contained within the final paper for the 27 EU countries are included here, along with the figures for all 31 countries participating in the EU-SILC in 2104. Note points above about the versions here being produced with an updated dataset and software.
