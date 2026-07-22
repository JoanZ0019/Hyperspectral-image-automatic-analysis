# Hyperspectral-image-automatic-analysis
It took one second to get the results from testing 4 images in 2 folders. 

This script would allow you to process multiple hyperspectral images with only one click  and get VIs listed from the Resonon software for each image and each collection day.
It automatically outputs one Excel file that includes 21 VIs (you can add any VI you want) of multiple samples from each day (attached). And it outputs an ROI folder for regions of interest (ROI) from each raw image saved as RGB images to check.

The "double check" sheet in the Excel file (VI_summary test run.xlsx) was to compare the results from Resonon software for all VIs of each image by tediously manipulating the software GUI and runing the Python code. The accuracy of the results was very promising in the "double check sheet " in the Excel file (VI_summary test run.xlsx). 

Running this script, it took < 2h to run by itself automatically for 805 hyperspectral images from one experiment. In the Resonon software, each hyperspectral image would easily take 3-5 min to get VIs data and type into an Excel. Therefore, it would take 50h+ work of constant operation for hyperspectral data from one experiment.  
