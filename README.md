## AI vs Neural Networks vs Deep Learning 
### Artificial Intelligence 
A boarder goal to generate intelligence artificially. AI helps automate tasks that are typically performed by humans. 
### Machine Learning  
Is a set Artificial Intelligence methods that keeps learning from new data and helps predict the future. 
### Neural Networks 
Modelled from Human Brain, it is a way to achieve Machine Learning 
## Deep Learning 
Is a sub class of Machine Learning to study deep neural networks. Deep Learning networks learn by themselves and imporves over time. AlphaGo is first application that is built on Deep Learning to learn the game Go. One of most complex games from Chinese origin and has a lot of combinations. The app defeated the world champion. 
- Computer Vision 
	- Uses Convolutional Neural Networks to identity objects 
- Chatbots 
- Banking Applications 

## Computer Vision 
Focus on learning from images and video streams. 
- Identify objects as per training 
- Provide an accuracy estimate on identified objects 
- AWS Panoroma & AWS Rekognition and developed for this purpose
- Typically Uses CNN's (Convolutional Neural Networks)

## Different Types of Neural Networks 
Modelled after human brain. Neural Networks are a way to generate Aritificial Intelligence. 
- Artificial Neural Networks 
Another name of basic Neural Network. Used in
	- Loan Prediction 
	- Fraud Prediction 
	- Pattern Recognition

- Convolutional Neural Networks
Neural Network that deals with image and video analysis also referred as Computer Vision. 
	- Image Classification 
	- Object Detection 
	- Image Segmentation 
	- Facial Recognition
- Recurrent Neural Network 
The core idea is output depends on a series on inputs 
	- Natural Language Processing 
	- Speech Recognition


## AWS CV Modules
- AWS Sagemaker - Used to create Models 
- AWS Panoroma - Just a linux machine to deploy CV models (no model is provided by default) 
- Lambda Function - Used in generating bounding box around the objects recognized by the model (Code implemented here can be consumed and used in other apps) 
- AWS Grasshopper - Used to deploy models (used by panorama as well)
- AWS Rekognition - Better model that runs in the cloud, less deployment needed as it is cloud deployed. No Machine Learning expertise needed. Models be re-trained via custom labels which removes the learning curve involved with Machine Learning. Less infrastructure costs. 
