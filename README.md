# Miconia-BioEcon--Model

### R and Rstudio are required to run this model. All package dependencies are annotated in the markdown file.

The R0_data.csv is an example of generated dispersal distances for miconia based on its dispersal kernal (probability density function of dipsersal distance from maternal source).

The model is setup to knit together and produce markdown files on each run and export plots and .xlsx files for model outputs.

## Running the Model

1. Downloand 0_data.csv or have a .csv file with a single column of distances to be used.
2. Download Invasion_Model_Edit.Rmd and open in Rstudio
3. Run `r setup` and download or update any required packages
4. Update `r dataset` to import your .csv dataset from your working directory (default is R0_data.csv)
5. Update `PDF` section with imported dataset to generate model disperal function
6. Edit `Model parameters` to change biological information in the stage matrix
7. Edit `Management` sections to change management actions at each time step.
- EDIT `AP` and `C1` variables to assign different distances for management. 
8. Update `r outputs` section with desired filenames for .xlsx and plot outputs.
