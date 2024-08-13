The code packages consist of a set of scripts (Code_Plots_Final_Combined_Environment.txt) that build out the environment, 
process the datasets, and builds necessary objects for use by the scripts (Code_Plots_Final_Combined.txt, Code_Plots_Supplemental.txt) to process the datasets and build the plots.

The data sets consist of the following three (3) files:  

The code packages are identified below and organized in four (4) categories defining the processing order in R.  The data files must be loaded into the R environment first followed by running the file to generate the environment.  Afterward, the files that create the base or supplemental figures can be run in either order.  I've included notes below to explain each file and also provide specific technical details for successful execution.

1.	Data files
1.1.	511145.protein.physical.links.detailed.v12.0.txt
1.2.	Ecoli_noisedata_full
1.3.	mbo001183726st2 DataSet.csv

2.	Environment
2.1.	Code_Plots_Final_Combined_Environment,v1.txt

3.	Base Figures
3.1.	Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot1_EN_EL.txt
3.2.	Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot2_RI_EL.txt
3.3.	Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot2_RI_EN.txt
3.4.	Code_Plots_Final_Combined,v1,Spearman,White Tests, Plot3_Essential.txt
3.5.	Code_Plots_Final_Combined,v1.txt
3.6.	Code_Plots_Permutation_Tests,spearman,v1.txt
3.7.	Code_Plots_Permutation_Tests,white_tests,v1.txt

4.	Supplemental Figures
4.1.	Code_Plots_Final_Combined,v1,EL,Shapiro_Wilks_Test, Plot3.txt
4.2.	Code_Plots_Supplemental,v1,Shapiro_Wilks_Test, Plot2.txt
4.3.	Code_Plots_Supplemental,v1,Wilcox_Test,Reg_Inputs_Essential Plot1.txt
4.4.	Code_Plots_Supplemental.txt
