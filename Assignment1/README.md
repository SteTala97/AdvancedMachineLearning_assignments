The assignment consists of the "default payments" prediction using a neural network.

The provided dataset contains information on default payments (y_train), demographic factors, credit data, history of payment, and bill statements of credit card clients (X_train, X_test) in Taiwan from April 2005 to September 2005.

Please find a description of the featured dataset in the "Data Dictionary" attached pdf.
The provided data comprises the training set that can be used for the training (and for the validation) and the unlabelled test set.

In order to be evaluated, each student should submit a zip file named FirstName_LastName_assignment1.zip containing all and only:

- the source code (we advise to use Keras, but you can use any other framework of your choice);
- a brief report, in the form of a separate PDF document (1 or 2 pages) or a jupyter notebook (the same containing the source code), describing the resolution of the problem of supervised classification with a traditional neural network  (Fully-connected Neural Network). 
 
Please include in the report:
- some basic data exploration and motivations about the choices on data processing, 
- some comments regarding the selected hyperparameters and optimization choices (e.g. number and dimension of the layers, optimization algorithms) 
- some performance metric evaluations (on a validation set) and some comments about the results and the generalization capability of the model. 

(OPTIONAL) The investigation on the effect of the use of any regularization technique of your choice.
(optional) a txt file named FirstName_LastName_score2.txt, where each line corresponds to the prediction (0/1 class) of the instances of the test set. The file should contain only one 0/1 column and no header.
