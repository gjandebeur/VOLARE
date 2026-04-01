# VOLARE
This repository serves as an updated workflow making VOLARE available through GitHub for assistance producing multi-omic network-based predictive models using the "VOLARE" software (Siebert, 2019). 
Refer to the citation at the bottom of the repository for author and publication information.



Citation
This analysis used a modified version of the "VOLARE" software (Siebert, 2019), which is available through the publication and on SourceForge at https://sourceforge.net/projects/cytomelodics/.

Publication: Siebert JC, Neff CP, Schneider JM, Regner EH, Ohri N, Kuhn KA, Palmer BE, Lozupone CA, Görg C. VOLARE: visual analysis of disease-associated microbiome-immune system interplay. BMC Bioinformatics. 2019 Aug 20;20(1):432. doi: 10.1186/s12859-019-3021-0. PMID: 31429723; PMCID: PMC6701114.

## Quick Start
To use this pipeline, fork the repository or download the pipeline.qmd file into a usable location. Edit this file's input paths at the top and run the script.
Script will produce a JSON file for the visual model, which can easily be viewed on VOLARE's web application [http://aasix.cytoanalytics.com/volare/](url)
Script is also set up to produce an mPlot using ggplot, looping over each nominal p<0.05 significant association, and also providing the effect size.

The pipeline.qmd script is currently using age and sex as covariates, but can be adjusted easily by search/replace using Ctrl + F. Check the lm() command used before running to ensure 
it works for your question of interest.
