# clinical_diagnosis_of_pneumocystis
This repository is used for depositing scripts and explainations supplimentary to Irinyi and Hu et al. 'Clinical metagenomics for fungal pathogen recovery from bronchoalveolar lavage using MinION nanopore sequencing' paper. 

Here are brief descriptions for each script, detailed explainations are commented within the code:

generatng_final_df.ipynb: A Python3 Jupyter Notebook re-organizing all the output files from Albacore, BLAST or WIMP, generating one single dataframe that include all the information for each sample.

Plotting_figure_1_2.ipynb: A Python3 Jupyter Notebook using the information from the final_df of each sample, first combining the information from all samples, second plotting the figure 1 and figure 2 using the combined information

Plotting_subfigure_for_figure_3_supplementary_figure_1_2.ipynb: A Python3 Jupyter Notebook using the information from the final_df of each sample to plot the subfigure for figure 3 and supplementary figure S1 and supplementary figure S2.
