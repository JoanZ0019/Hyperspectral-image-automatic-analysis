# Hyperspectral-image-automatic-analysis
It took a few second to get the results from testing 4 images in 2 folders. 

This script would allow you to process multiple hyperspectral images with only one click  and get VIs listed from the Resonon software for each image and each collection day.
It automatically outputs one Excel file that includes 21 VIs (you can add any VI you want) of multiple samples from each day. And it outputs an **ROI_RGB folder** for regions of interest (ROI) from each raw image saved as RGB images to check.

The "double check" sheet in the Excel file **(VI_summary test run.xlsx)** was to compare the results from Resonon software for all VIs of each image by tediously manipulating the software GUI and running the Python code. The accuracy of the results was very promising in the "double check sheet " in the Excel file (VI_summary test run.xlsx). 

Running this script, it took < 2h to run by itself automatically for 805 hyperspectral images from one experiment. In the Resonon software, each hyperspectral image would easily take 3-5 min to get VIs data and type into an Excel. Therefore, it would take 50h+ work of constant operation for hyperspectral data from one experiment.  


# 1. Input file format:

<img width="616" height="170" alt="image" src="https://github.com/user-attachments/assets/c5bcbfa4-0c41-44ad-b06d-f3011fc052d8" />
<img width="719" height="193" alt="image" src="https://github.com/user-attachments/assets/2e343354-ae45-4a81-b001-1125a7fb520c" />
<img width="672" height="169" alt="image" src="https://github.com/user-attachments/assets/e74f5ed6-3894-41a2-bed5-1a46cc31cdec" />


        experiment1 folder: 
                  day1 folder: sample1.bil and sample1.bil.hdr, sample2.bil and sample2.bil.hdr,....
                  day2 folder: sample11.bil and sample11.bil.hdr, sample12.bil and sample12.bil.hdr,....
                  .
                  .
                  .

# 2. Modify your imgage folder and output location, then click Run<img width="27" height="25" alt="image" src="https://github.com/user-attachments/assets/192d7c8d-11ae-427d-9c21-631cd90d5df0" />

<img width="484" height="50" alt="image" src="https://github.com/user-attachments/assets/7c3e22bd-dffc-486a-8eda-06805c88cf67" />


# 3. Output file: 


             One Excel file including multiple sheets (each sheet for each day collection).
             One folder for ROI_RGB to check regions of interest were correct.
