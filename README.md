# State-Farm-Distracted-Driver-Detection
Computer Vision Competition - Kaggle

A distracted driver is responsible for one out of every five car accidents, according to the CDC’s motor vehicle safety section. Distracted driving results in 425,000 people being wounded and 3,000 people being killed each year.

State Farm is researching whether dashboard cameras can automatically detect distracted drivers in order to improve these alarming figures and better insure their customers. The purpose of this project, which was the final project of the INF473V computer vision course taken at École Polytechnique, is to identify each driver’s behavior using a dataset of 2D dashboard camera photos. The present study used the State Farm distraction-detection image dataset. 

The dataset is divided into ten categories, and each image is assigned to one of them. Multiple drivers are represented in these images. The categories include the following driver actions: Safe driving, texting with the right hand, talking on the phone with the right hand, texting with the left hand, talking on the phone with the left hand, operating the radio, drinking, reaching behind, hair and makeup, and talking to passengers. 

By introducing vast volumes of labeled data and increasing processing capacity, a standard CNN is now changed and advanced. Some architectures, including AlexNet, ZFNet, VGGNet, GoogleNet, and ResNet, were designed for computer vision problems and have been used to modify CNNs. The VGG-16 and ResNet-50 designs were considered in this work, and they were adjusted accordingly to best meet our problem. Pre-processed data was therefore used with pre-trained and fine-tuned neural networks in order to get the best possible model performance. The notebook contains code describing the use of the ResNet-50 model, but the same methodology was used for VGG-16.

You can download the database on Kaggle's website. The competition is called "State Farm Distracted Driver Detection". At the end of the project, we obtained a Kaggle score that put us in the top 24% of all participants. If you do not want to run the code, you can see the confusion matrix of our model by clicking on the PNG file in the repository.
