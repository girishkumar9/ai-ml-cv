## AWS Modules
- AWS Sagemaker - Used to create Models 
- AWS Panoroma - Just a linux machine to deploy CV models (no model is provided by default) 
- Lambda Function - Used in generating bounding box around the objects recognized by the model (Code implemented here can be consumed and used in other apps) 
- AWS Grasshopper - Used to deploy models (used by panorama as well)
- AWS Rekognition - Better model that runs in the cloud, less deployment needed as it is cloud deployed. No Machine Learning expertise needed. Models be re-trained via custom labels with removes the learning curve involved with Machine Learning. Less infrastructure costs. 

## AI vs Neural Networks vs Deep Learning 
- Artificial Intelligence :- A boarded goal to generate intelligence artificially 
- Machine Learning :- A subfield in Artificial Intelligence concerning to learn from machines 
- Neural Networks :- Modelled from Human Brain, it is a way to achieve Machine Learning 
- Deep Learning :- A sub-field of Neural Networks to learn from a specific scenario like :- 
	- Computer Vision - Uses Convolutional Neural Networks to identity objects 
	- Chatbots 
	- Banking Applications 

## Computer Vision 
Focus on learning from images and video streams. 
	-> Identify objects as per training 
	-> Provide an accuracy estimate on identified objects 
AWS Panoroma & AWS Rekognition and developed for this purpose. 
