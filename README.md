# Design-validation-and-implementation-of-a-MS-MS-based-search-and-an-in-source-fragments-detector-in MS based searches
This is my final degree project in Biomedical Engineering. 
Score = 10 (Merits with Honors)

## Abstract

Metabolomics is a sub-field of molecular biology that involves the analysis of small molecules (> 1000 Da), known as metabolites. 
The metabolites are the substrates, intermediates and products of metabolism. This field has been used for studying several diseases such as cystic 
fibrosis, cancer, central nervous system diseases, diabetes and cardiac disease. 

Metabolomics may lead to more accurate biomarkers discovery, which will help in diagnosis, prevention and monitorisation of the risk of disease, among other purposes. 
Within the metabolomics work-flow, the identification of metabolites is the main bottleneck in metabolomic studies, which consists in the recognition of the metabolites 
analysed in the metabolomics instrumentation.


Mass spectrometry (MS) is the principal spectrometric method employed for metabolite detection due to its high sensitivity. 
Tandem mass spectrometry (MSn) is the application of two or more stages of MS analysis. 
The identification of metabolites from their MS2 (MS/MS) data is a key task in metabolomics. 
This is not a trivial task since the metabolites have different chemical and physical properties that makes them difficult to identify using only MS1 data. 
These diversities cause the formation of different alterations over the metabolites, like adducts, fragments, multimers and/or multiple charged ions. 
Some alterations can be produced in the ion source of the MS, where the molecules can be affected before entering the mass spectrometer. 
These alterations difficult the identification of the compounds, and can lead to the misidentifications of them.


In this project we want to create an automatic search for in-source fragments based on the complete spectrum data of the experiment, 
as well as an algorithm to perform MS/MS based searches.
