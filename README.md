# Aquilegia formosa Distribution Projection Final Project
Final Project for IP: Application Development Course at PLUS

The main objective of this project was to perform a distribution analysis and Species Distribution Model (SDM) for Aquilegia formosa, or Western Columbine. The project is broken into 4 main parts: the initial distribution analysis, generating pseudo-absence data, generating the spatial block tiles, and then the entire SDM analysis. 

The initial distribution analysis is found in the rendered .html file "AquilegiaFormosaInitialDistributionAnalysisQuarto.html", the quarto document is "AquilegiaFormosaInitialDistributionAnalysisQuarto.qmd", and then additional files that were generated upon rendering the quarto file are found in "AquilegiaFormosaInitialDistributionAnalysisQuarto_files". The data to perform this analysis is found in "Aquilegia_Data_x_World_Clim_Data.txt". This analysis serves as an initial understanding of the Aquilegia formosa data, specifically the species' range and distribution. By looking at the distribution area as well as knowing a little background on the species, I was able to determine which bioclimatic variables would be most relevant and important during the SDM analysis. 

To perform the generalized linear model to analyze future species distribution, I needed to generate absence data as it was not included in the Aquilegia formosa distribution data that was used. This workflow can be found in the .html file "Generating_Pseudo-Absence_Data.html", quarto document "Generating_Pseudo-Absence_Data.qmd", and any generated figures in "Generating_Pseudo-Absence_Data_files". The data used in this workflow is found in the "pseudo_absence_data.txt" file. 

Spatial block tiles also needed to be generated to perform the generalized linear model analysis. This workflow can be found in the "Generating_Spatial_Block_Tiles.html" file, "Generating_Spatial_Block_Tiles.qmd" file, and the figures in "Generating_Spatial_Block_Tiles_files". The data used in this analysis is found in the "Use_This_Data_For_Block_Generation.txt" file. 

The final SDM analysis was performed after all of the prior workflows. The SDM analysis can be found in the "Final_Complete_SDM_Analysis.html" file, "Final_Complete_SDM_Analysis.qmd" file, and any additional files that were generated in the "Final_Complete_SDM_Analysis_files" file. The data used in this analysis was the data found in "Final_SDM_Data_Complete.txt". 

All of these use climate data from WorldClim that was too large to upload to github. This data can be found in the OneDrive folder.

I was the only person running this analysis for this project. There were no other group members.

AI USE DISCLAIMER! ChatGPT was used throughout this project to help me understand different lines of code (especially in Damaris Zurrell's 2020 SDM workflow), help me find which package to use to perform a function (such as generating an interactive map with point data), and to help troubleshoot error messages that came up in my code. ChatGPT was mainly used as a means to understand what the code meant, so I could understand how to best perform the analysis for the Aquilegia formosa species.
