# Machine Learning - Face Pose Classification 
## Introduction
Stroke is a cerebrovascular disease caused by disruption of blood supply to the brain. According to the Indonesian Ministry of Health's Center Data and Information, stroke became the world’s second leading cause of death and third leading cause of disability in 2019. Limb weakness or hemiparesis are common clinical problems following a stroke. Rehabilitation therapy is required to restore decreased limb function.

There is various therapy to recover from stroke such as physical therapy, memory therapy and also speaking therapy. Physical therapy is to improve  body ability or movement, relieve pain, and so on. On some cases stroke cause facial paralysis. Facial Paralysis is a loss of facial movement due to nerve damage. Facial paralysis known as Bell's palsy is not considered permanent, but in rare cases, it become permanent.  So far there is no drug to recover from this syndrome.  One of some ways to cure this disease is to do facial therapy. There is some poses used for bell’s palsy therapy :
1.	Smile
2.	Sneer on one side
3.	Puff cheek
4.	Show teeth
5.	Open Mouth

## Used Technologies
To develop this machine learning model we use CNN (Convolutional Neural Network) algoritm and Mobilenet as transfer learning. We also used some python library in this project, including:
- Python 3.7.13 version
- TensorFlow 2.8.2 version
- Matplotlib 3.2.2 Version
- Numpy 1.21.6 version

## Dataset
We collected our dataset from various image source from the internet (pinterest, freepik, kaggle). We got 900 face images data in total and there is the distribution :
1.	Smile Pose= 180 
2.	Sneer on One Side Pose = 180
3.	Puff Cheek Pose = 180
4.	Show Teeth Pose = 180
5.	Open Mouth Pose = 180

## Launch 
To find best model we try some algorithm as shown below :
- [CNN and InceptionV3 transfer learning](https://github.com/C22-PS185/ML-Model/blob/main/Manual_Model_Inception_V3%20(1).ipynb)
- [Model with inception resnetV2 transfer learning](https://github.com/C22-PS185/ML-Model/blob/main/Model_inceptionresnetv2.ipynb)
- [Model with Xception transfer learning](https://github.com/C22-PS185/ML-Model/blob/main/model_Xception.ipynb)
and our best model :
- [Model with Mobilenet transfer learning](https://github.com/C22-PS185/ML-Model/blob/main/final_model(MobileNet).ipynb)

after we found our best model we saved our model to [TF-Lite & .H5 format](https://drive.google.com/drive/folders/1nKQbFGayOEvkx2l0Q0B3KIUS1CsQSDDs?usp=sharing)
