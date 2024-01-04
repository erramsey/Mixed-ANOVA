This code is for a mixed ANOVA performed using the COMET dataset in the SASHELP library. The dataset was modefied to resemble an experiment where a subject received multiple dosages, and a 
single measurement was taken after each dosage.
The dataset includes information for an experiment where twenty-four rats were divided into four groups, each of which received one dosage of 1,2-dimethylhydrazine dihydrochloride 
(control, low, medium, high). Three additional rats received a positive control. Cell suspensions of these rats were scored for DNA damage using a Comet assay (Ghebretinsae et al. 2013).
The dataset was altered in these ways:
The original dataset consisted of multiple 'length' measurements for each sample for each rat. These were averaged to create a new variable 'length_mean'.
A variable 'subject' was created that counted the number of observations for each dosage. This variable replaced the 'rat' variable in analysis, so that the data could be analyzed
as if the same rat received multiple dosages.

Coding was performed in SAS Studio.
