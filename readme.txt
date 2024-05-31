Here is all you need to reconstruct the flooded shelf area data in Auderset et al., 2024, Paleoceanography.

Model_etopo_ice_15.txt
ETOPO-2 Two-minute gridded global relief for both ocean and land areas. This  includes ice elevation as topography. 

Model_environment.yml
A Conda environment used to run the Jupyter notebook.

Model_lat_GL256.txt / Model_lon_GL256.txt
Degree 256 Gauss Legendre grid coordinates used to interpolate topography onto the resolution of the ice and sea-level models

Model_ice.nc
Gridded global ice model used as inputs for the glacial isostatic adjustment modeling.  The model includes the Eurasian ice sheet by Lambeck et al. (1995) with remaining ice sheets from Peltier et al. (2015).

To run Jupyter Notebook download the file from Pangaea (link).

This model is identical to the lambeck_400k_3k_rcp2p6_ch21ctrl_gr21ctrl.nc file used in Creel et al. 2024.  See https://www.nature.com/articles/s41467-024-45906-8 for more information.

Model_rsl.nc
Glacial isostatic adjustment model outputs created using the Model_ice.nc file and a three-tiered radially symmetric viscosity structure with a lithospheric thickness of 90 km and mantle parameterized following the VM5a viscosity structure of Peltier et al. 2015.

To run Jupyter Notebook download the file from Pangaea (link).

This model is identical to the output_400k_3k_rcp2p6_ch21ctrl_gr21ctrl_l90C.umVM5.lmVM5.nc file used in Creel et al. 2024.  See https://www.nature.com/articles/s41467-024-45906-8 for more information. 

Works Cited
1. Auderset, A., Fripiat, F., Creel, R. C., …, Martínez-García, A. Sea level modulation of Atlantic nitrogen fixation over glacial cycles. Paleoceanography. Paleoceanography & Paleoclimatology (2024)
3. Creel, R. C., Miesner, F., Wilkenskjeld, S., Austermann, J. & Overduin, P. P. Glacial isostatic adjustment reduces past and future Arctic subsea permafrost. Nature Communications 15, 3232 (2024).
2. Peltier, W. R., Argus, D. F. & Drummond, R. Space geodesy constrains ice age terminal deglaciation: The global ICE‐6G_C (VM5a) model. Journal of Geophysical Research: Solid Earth 120, 450–487 (2015).