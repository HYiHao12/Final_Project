# Final_Project

## Project Background
This project aims to analyze the relationship between topography and vegetation health using Digital Elevation Model (DEM) and Normalized Difference Vegetation Index (NDVI) data.

## Repository Contents
- Final_Project.ipynb - Jupyter Notebook file containing all analysis steps and code.
- input_data/ - Input data folder containing DEM.tif and NDVI.tif files.
- output_images/ - Folder for storing the generated clipped images (currently empty, will be populated after running the code).
- scripts/ - Any auxiliary script files.

## Purpose of the Code
The code is designed to preprocess topography and vegetation data, perform correlation analysis, and generate visualizations to illustrate the impact of topography on vegetation health.

## Requirements
Before running the code, please ensure the following Python libraries are installed:

- arcpy
- numpy
- matplotlib
- geopandas

## Folder Structure
- input_data/: Stores the input data files.
- output_images/: Stores the generated image files after running the code. Note that this folder is currently empty; the images will be created when the code is executed.
- outputshow/: Stores the final analysis result files.

## Running the Code
1.Clone or download this repository to your local machine.
2.Install the required Python libraries.
3.Open the Final_Project.ipynb file and run the code cells in sequence to generate the necessary images and analysis results.
4.All generated image files will be saved in the output_images/ folder.
