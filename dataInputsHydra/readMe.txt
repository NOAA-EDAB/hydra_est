We split up input data into manageable files.

All files will then be read into R and the .dat and .pin files will be created.

The user will be able to specify how the data file should be set up and the R code will create it and name the file accordingly.


eg. user wants mean temperature, no effort, other food = 50000, etc
R will use this, create .dat and name it

for example: hydra_MT_NE_OF50000.dat

All files will then be copied into their own directory, a simulation will run, plots created, and a summary of input file output, with plots using R markdown to display summary in an html file

This will help in organization of runs and future reference.