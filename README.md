# Single-Cell-Protein
Source Code and Data Set for 'SPATIAL ANALYSES AND VISUALISATION FOR NEW PROTEIN SOURCES'
/* what every files for*/

1. Code File (run in jupyter notebook)
1.1.  spatial_analysis_Maize.ipynb:   data pre-processing, spatial analysis, model-building, future projection for maize residue, protein projection
1.2.  spatial_analysis_rice.ipynb:   data pre-processing, spatial analysis, model-building, future projection for rice residue, protein projection
1.3.  spatial_analysis_sorghum.ipynb:   data pre-processing, spatial analysis, model-building, future projection for sorghum residue, protein projection
1.4.  spatial_analysis_wheat.ipynb:   data pre-processing, spatial analysis, model-building, future projection for wheat residue, protein projection
1.5.  spatial_analysis barley.ipynb:   data pre-processing, spatial analysis, model-building, future projection for barley residue, protein projection
1.6.  temperature_data_process.ipynb:    temperature data aggregation
1.7.  rainfall_data_process.ipynb:  rainfall data aggregation
1.8. temperature_projection.ipynb:   prediction of temperature change data
1.9. Lignocellulose_Projection.ipynb:   map visualization for lignocellulose value for crop residues and SCP in 2030 and 2040



2. Data Set (/dataset)
2.1.  /climate:                                                      aggerageted temperature and rainfall data in country level
2.2.  /cropland:                                                   original collected cropland data and country area data (*with missing values) 
2.3.  /fertilizer:                                                    original collected fertilizer data (*with missing values)
2.4.  /WB_countries_Admin0_10m/WB_countries_Admin0_10m.shp:      worldwide shapefile data
2.5.  /temperature_change:                                temperature change data (1960 to 2020)
2.6.  /production:                                                crop production and residue quantity in 2018
2.7.  /protein:                                                      Lignocellulose and SCP projection from residue projection
2.8.  /crop_residue_and _indicators:                   pre-processed and linked data (including residue and independent variables) for each kind of crop
2.9.  /data_for_diff_visualize/diff-2040.xls:         data for histogram visualizations in Tableau
2.10. /temp_point_18.csv , rainfall_point_18.csv :        temperature and rainfall value of geometry points worldwide (2018)
2.11  /country_data.csv :                                               country code data
