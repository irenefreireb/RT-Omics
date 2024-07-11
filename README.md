**About**

***RT-Omics*** is designed to extract Radiomic and Dosiomic features, both at the same time or either separately, from DICOM images. Radiomic features are extracted from diagnostic images and Dosiomic features are extracted from 3D dose distribution (dosimetry) images, generated during radiotherapy treatment planning.

It is built to handle the necessary corrections to enable extraction, including transformation of DICOM images to Nifti (.nii) format; creation of the Region of Interest (ROI) Binary Mask with option to be selected from the available segmented regions; discretisation of intensity levels in the case of diagnostic images and of dose level in Grays (Gy) in 3D Dose distributions; and the option to apply EQD2 (Equivalent Dose in fractions of 2-Gy) to address differences in dose fractionation.

**Running**

To proceed with the extraction it is necessary to run the ***RT-Omics*** archive. 

It is necessary to organize the source folder where the files from which the characteristics will be extracted are located in the following way:
- General folder.
- Subfolders: each subfolder containing the CT series, RT Structure Set and RT-Dose images of each patient. 
