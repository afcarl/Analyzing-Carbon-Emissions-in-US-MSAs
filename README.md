# Analyzing-Carbon-Emissions-in-US-MSAs
Determining the correlation between population/density and carbon emission per capita

In this project, I tried to determine the correlation between population/density and carbon emission per capita, using the "Vulcan Project" dataset provided by ASU.
Population by counties and land area are obtained from the ArcGIS book—GIS Tutorial 1: Basic Workbook. The extracted file is called `ArcGIS_Census.txt`.
The MSA to County lookup table is obtained from Spatial Insights: http://www.spatialinsights.com/catalog/downloads/products/32/MSAtoCounty.pdf

## Steps to run

Run the notebook `file_converter.ipynb` to convert the population by counties text file to csv.

Run the notebook `merger.ipynb` to merge the census data with the carbon emissions data and aggregate population and emission to MSA scale.

Run the notebook `analysis.ipynb` to see the code for generating linear regression models.

Run the notebook `plots.ipynb` to see the code for generating plots using plotly.

The generated graphs are in the `imgs` folder. Results and findings are discussed in `paper.pdf`.