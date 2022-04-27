# Directives for this assignment

The task of the assignment #4 is Transfer Learning using a CNN pretrained on IMAGENET.

The suggested architecture is the VGG16.

The CNN should be used as fixed feature extractor on a new task of your choice containing a number of classes in the range from 2 to 10. 

The report must contain:
- a description of the new task and on the dataset used
- the use of the pretrained CNN as feature extractor considering different layers (at least 3 different choices)
- the chosen "classical" classifier
- for each transfer learning experiment:
  1. the details about the chosen layer
  2. the plot of the classification performance on train/val/test for the different layers considered
  3. the hyper-parameters used for training the "classical" classifier
