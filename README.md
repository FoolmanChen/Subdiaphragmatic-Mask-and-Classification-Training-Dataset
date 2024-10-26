# Subdiaphragmatic-Mask-and-Classification-Training-Dataset

** The paper is "The Two-Stage Detection-After-Segmentation Model Improves the Accuracy of Identifying Subdiaphragmatic Lesions" in Scientific Report  
https://www.nature.com/articles/s41598-024-76450-6  
https://doi.org/10.1038/s41598-024-76450-6  
please cite:  
Chen, CH., Hsu, S.H., Hsieh, KY. et al. The two-stage detection-after-segmentation model improves the accuracy of identifying subdiaphragmatic lesions. Sci Rep 14, 25414 (2024). https://doi.org/10.1038/s41598-024-76450-6  


The Detection-After-Segmentation Model for Subdiaphragmatic Lesion 

Note: all these files are available at:   
Due to copyrights and storage of github issue, please download the original ds before you use them.  
Here are their filenames of the images. Use appropriate tool to set up the dataset  



STAGE 1, SEGMENTATION TRAINING  
  images: original images  
  masks.zip: upper abdominal masks  
  masks_rt.zip: right subphrenic masks  
  masks_lt.zip: left subphrenic masks  

STAGE 2, DECTECTION TRAINING  
  SUBPHRENIC_dataset: whole classification including BIL, RUQ, LUQ  
  LUQ_13_subset: 13 classification  
  LUQ_severity_subset: severity classification after combination  
  RUQ_subset: right upper quadrant lesions  
  BIL_subset: bilateal below-the-diaphragm lesions  
