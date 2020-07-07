# lulc_bhiwani
LULC mapping of Bhiwani district in 4 land cover classes(Agricultural land, water, trees, Urban areas)
The SAR sentinel-1 data downloaded from copernicus website is loaded into SNAP software by the open option.
The diffrent operators are available in SNAP 6.0 tool for
1) Apply Orbit file
2)Calibration
3)Speckle filtering
4)Terrain Correction
5) Creation of ROI from the container tool
6) Classification of the image using ROI

The classified output are loaded into ARCGGIS 10.4 for accuract assessment.
The random test points are selected by the random accuracy points option and the confusion matrix is caculated for each image and each class.
