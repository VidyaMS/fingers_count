## fingers_count. 

Data source: https://www.kaggle.com/koryakinp/fingers   

Data type: images 
There are 18K images of palm - left and right , showing the number of fingers. Closed fists stands for zero fingers and 5 fingers outstretched stands for 5 fingers.  

Task :  Build an AI model to identify the count of fingers and the left/right palm . 

### Model building .  

Pure NN model :  
After going through many iterations of model building , a single layer Neural Network with 100 Neurons gives and accuracy of 100% . The model was run through three different slices of train and validation images , and the test set accuracy , F1 scores was checked. 

CNN model :  
Its seen in this repo that we do not need to build a complex model with convolution for achieving the said accuracy of 100%.  
Can attribute this to simplicity of the images and quality of the images.  
