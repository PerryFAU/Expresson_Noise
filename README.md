The code packages are identified below and organized in four (4) categories that support the processing order in R.  The data files must be loaded into the R environment first followed by running the file to generate the environment.  Afterward, the files that create the base or supplemental figures can be run in either order.  I've included notes below to provide additional information about each file and also provide specific technical details for successful execution.  Please see the "Methods" section of our paper for additional details on referenced materials and applications of statistical methods.

Data files
1. 511145.protein.physical.links.detailed.v12.0.txt -
   This is a legacy data set that provides detailed information about protein-protein interactions for particular genes.  It is
   available for further studies but is not used in the below base figures and supplemental information.
2. Ecoli_noisedata_full - The data set from the Urchuegu ́ıa et al. (2021) study.  This provides comprehensive information for the
   measures in expression level, noise, regulatory inputs, essentiality, etc.
3. mbo001183726st2 DataSet.csv - This data set was sourced from Dasmeh et al. (2017) and Goodall et al. (2018) studies and provides
   information about gene essentiality.

Environment
1. Code_Plots_Final_Combined_Environment,v1.txt - builds out the environment necessary to build both the base figures and
   supplemental figures.  It begins by installation and loading of the the R packages necessary for the functionality needed by
   follow-on code packages.  It loads the data files as data frames, processes the files to establish necessary attributes and builds
   functions available for later use.

Base Figures
1. Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot1_EN_EL.txt - Generates the Spearman correlation coefficients and White test statistics for the conditions in plot 1 (figure 1.)  The model is based upon
   the relationship of expression noise to expression level.
3. Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot2_RI_EL.txt - Generates the Spearman correlation coefficients and White test statistics for the conditions in plot 2 (figure 2.)  The model is based upon
   the relationship of regulatory inputs to expression level.
4. Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot2_RI_EN.txt - Generates the Spearman correlation coefficients and White test statistics for the conditions in plot 2 (figure 2.)  The model is based upon
   the relationship of regulatory inputs to expression noise.
5. Code_Plots_Final_Combined,v1,Wilcox Tests, Plot3_Essential.txt - Generates the Wilcox test statistics to compare the essential and nonessential boxplots.
6. Code_Plots_Final_Combined,v1.txt - This files contains the three (3) scripts to generate figures 1, 2, and 3. Each of the individual plots should be run separately with the resulting image available in the
   "Plots" region of the R console.
8. Code_Plots_Permutation_Tests,spearman,v1.txt - 
9. Code_Plots_Permutation_Tests,white_tests,v1.txt

Supplemental Figures
1. Code_Plots_Final_Combined,v1,EL,Shapiro_Wilks_Test, Plot3.txt
2. Code_Plots_Supplemental,v1,Shapiro_Wilks_Test, Plot2.txt
3. Code_Plots_Supplemental,v1,Wilcox_Test,Reg_Inputs_Essential Plot1.txt
4. Code_Plots_Supplemental.txt
