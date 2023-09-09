Project Description: Part 1 Data Annotation : The data annotation includes one batch of approximately 200 frames (images). You will be assigned one (or two) objects with a google drive link which contains a directory of frames (images). You have to annotate all frames containing the objects assigned to you. To annotate you need to create a bounding box around the object (e.g. potato) in the frame and also specify the state (e.g. sliced) of that object. You should do this for every frame that contains the assigned object. After annotation you should dump the results into PASCAL VOC format. For annotation you need to create an account in the cvat.ai website. A video has been uploaded to canvas that explains how to create an account in cvat.org, how to create a task, how to annotate and finally how to dump the results. You need to create a zip file from the dumped annotations files and upload it on canvas. After annotations are done, each student will be given a random set of videos from other students to check for annotation errors. Students could lose points for poor annotation. The dataset assigned to you will be email to you by the TA. Part 1 submission - You should submit all labels of the frames  - You will evaluate other student’s labels and provide corrections  Part 2 Neural network design and training : A sample Python code for training a neural network for state classification will be given to you. You should build upon the code and create your own convolutional neural network. A data set will be provided to you for training and validation. You should split the data given to you into train and validation data and use train data for training your model. You should validate your model during and after training with your validation data. You should add convolutional layers, pooling layers and test various deep learning techniques to improve your results as much as possible. Failure to add various layers will result in a deduction of your points. The code should be implemented in Python. You can Tensorflow but no other programming language or platform is acceptable. We will test your code on unpublished test data and report the results to you 2 days after your submission. If you substantially change the code or have your own implementation of the model, you have to provide instructions on how to run your code and also help files (readme.txt and requirements.txt if needed) and a test script to run on the test portion of the dataset. If your program is not easily test-able on the test set, Part 2 Submission: - Training code  - Testing script of the train model. It should include loading a dataset and provide outputs.  - Training and validation results Part 3 Improvement and comparison To improve your neural network’s performance, you should perform at least the follow techniques: - data augmentation  - different drop rates  - batch normalization - use Inception module  - use residual connections The remain is based on your model’s classification accuracy of on unpublished test data. Your submission should include - Source code for training the best model - Your best trained model and a architecture drawing of the model - Test script load your best trained model so that we can test it on the test data - Figures showing the performance differences using the required techniques


**Recurrent Neural Network**

ou will use the same type of data as provided for homework 2. You will design recurrent 
neural networks to learn models that can predict based on a sequence of inputs (first three 
columns) and output one output. You should learn and validate your model with the 
provided data.
Part 1 GRU (50 pts)
You can start with building 4 layers of 16 GRU cells and train the model with the provided 
data. You should try different number of layers and cells and find the best GRU 
architecture. You should also perform data preprocessing and drop out to improve your 
training performance. 
Your submission should include
- Training code (40 pts)
- With at least four different data preprocessing and training techniques
- Testing script of the train model. It should include loading a dataset and provide output. 
(5 pts)
- Training and validation results in figures (5 pts)
Part 2 LSTM (50 pts)
You can start with building 4 layers of 16 LSTM cells and train the model with the provided 
data. You should try different number of layers and cells and find the best LSTM 
architecture. You should also try the peephole LSTM. You should also perform data 
preprocessing and drop out to improve your training performance. 
Your submission should include
- Training code (30 pts)
- With at least four different data preprocessing and training techniques
- Compare results of using LSTM and peephole LSTM for the dataset (10 pts)
- Testing script of the train model. It should include loading a dataset and provide outputs. 
(5 pts)
- Training and validation results in figures (5 pts)

