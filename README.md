# Research Project 
This repository contains the code used in the application generated for Maya Gurkaran Dhaliwal's dissertation on "Producing an R Shiny Application to visualise the results of Genome-Wide Association Studies using Hierarchical Clustering."  

The "HC_functions.R" file contains the functions required for the application to perform hierarchical clustering. 

The "app.R" file is the annotated code for the application. It contains the packages required for the application to run and the user interface and server code. 

Note: In order to run the application, you will have to:
      (1) Install all of the packages using "install.packages()" before running the library() statements.
      (2) Produce a csv file named "Dataset_Paths" with 2 columns: "Dataset_Names" and "Path". In this file, you will have each phenotype dataset you could compare and 
      its corresponding file path in your computer. 
      (3) Ensure that all of your datasets are aligned and follow this order of variables: SNP; EA; NEA; Beta; Standard Deviation; P-Value; Dataset; Gene
   
      
