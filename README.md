# Satellite_Detection

This is the repository for the analysis of satellite trails in Hubble images in the ESA summer project "The impact of megaconstellations on space astronomy". 

1) Zooniverse_Data.ipynb: Transforms the results from Zooniverse into training data for the machine learning algorithms.
2) Hubble_Image_Download.ipynb: Downloads all the raw Hubble Archive Images that make up the composite images for the three instruments ACS/WFC, WFC3/UVIS and WFC3/IR and saves them in the format 600x600px.
3) Image_Classifier.ipynb (Machine Learning algorithm 1): Makes binary predictions "satellite"/"no_satellite" on a given Hubble image.
4) Mask_R-CNN_Satellites.ipynb (Machine Learning algorithm 2): Detects start/end point and the angle of a satellite trail on a given Hubble image with a satellite trail.
5) Processing_and_Analysis.ipynb: Postprocesses the data and creates analysis plots.
