# CBIS-DDSM
This is done for Thesis project for LJMU university

1- Preprocessing - This contains the steps involved for preprocessing the images. They are processed in the below order
   a) 1-FileReorganize.py - The input files downloaded from NVDlib are reorganised for preprocessing
   b) 2-PreprocessImage.py - The images are preprocessed in this pipeline
   c) 3-MergeTumour.py - The tumors of same ID are merged into singlefile
   d) -SplitFiles.py - The files are split into Full and mask for Train and Test data
   
 2- Model
  This is for the experiments with the model
    a) VGG16 - All experiments used with VGG16 for Transfer learning. Model 1-11 are the experiments
    b) ResNet - All experiments used with ResNet for Transfer learning. Model 1-12 are the experiments
