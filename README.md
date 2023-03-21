# Heart-Arrhythimia-Detection
## Detecting Heart Arrthymia using Deep Learning and identifying the type of abnormality.
### Link to the Dataset : https://physionet.org/content/mitdb/1.0.0/
Abstract : This project takes the input data in the format of ECG (ElectroCardioGraph) readings           
          and then processes it using the LSTM(Sequential Model, epoch = 10, accuracy >= 99.50)    
          for deriving the arrhythmic response of the heart and then predicting the type of abnormality.
### This Project uses only LSTM model and some basic concepts of Deep Learning.
The runtime of this particular model is high so if using a GPU with memory higher than 6 gigs, remember changing the usage to GPU from CPU (default).Only do this if the system GPU is powerful enough.

## Update
The previous model was found to be a good one but there was some room for improvement in the form of special codeset for the dataset if it is somehow available in csv format, if the dataset is already in the format of csv, it won't be necessary to perform all the data preprocessing also the previous model lacked the bidirectional feature, thus the development of bidirectional model made the model show more accuracy. As the project is a medical situation related, the more accuracy the better.
