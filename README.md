# handwritten_notes_classifier_using_Tensorflow_Keras_Deep_Learning

## Dataset
- This dataset is from [tensorflow](https://www.tensorflow.org/datasets/catalog/mnist)
- it is a dataset of handwritten digits
- it has 10 classses 0-9

## Analysis
- there are 60,000 data points, each data point is  a image with 28X28 px units .
- I have split the data into train,test ,valid 

- I have normalized the data , between 0 to 255 . 

## Layers

- I Flattened the datapoints into one array of 784 units  which is inputLayer
- 300 units is the hiddenLayer1, 100 units is the hiddenLayer2 , 10 units is the final output array 
- then i have compiled the model and fitted the model with X_train,y_train,epochs, and validation_Set

## Evaluation
- I have evaluated the model with X_test,y_test
- Observed the history of the model 
- plotted  the histroy with accuracy, loss

## Thankyou

- Thanks for reading till the end, if you have any opportunities in AI , ML , DL ,NLP, feel free to reach me out on [Linkedin](https://www.linkedin.com/in/rohandevaki/) or [Email Id](mailto:jagandevaki1@gmail.com) , 
