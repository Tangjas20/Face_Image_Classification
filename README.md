# Face_Image_Classification on UMIST dataset
Data:
The Sheffield (previously UMIST) Face Database consists of 564 images of 20 individuals (mixed
race/gender/appearance). 
Each individual is shown in a range of poses from profile to frontal views –
each in a separate directory labelled 1a, 1b, … 1t and images are numbered consecutively as they were
taken. 

The files are all in PGM format, approximately 220 x 220 pixels with 256-bit grey-scale. 

To simplify the implementation, the images had been cropped to focus the informative regions 

on facial information.

Each cropped image has a resolution of 112 x 92 pixels.


Main Task:

• Represent each facial image by vectorising image pixels;

• Classify facial images using logistic regression and non-linear SVM

• Compare their performance;

• Reduce feature dimensions using PCA and LDA, and compare Eigen-face and Fisher-face.

• Verify if the reduced features help improve classification performance.


The storage structure of the file is as follows.

This task requires programming to convert the data from images to vectors to organize datasets that can
be used for training and validation.

The number of pictures of each character is not exactly the same.

It is necessary to divide the data samples for training and the data samples for testing and 

verification according to a certain method and proportion.

When testing, it is necessary to be able to apply various metrics flexibly to comprehensively test and

evaluate each method and to be able to interpret the meaning of different evaluation results.
