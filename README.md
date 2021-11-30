
# Detecting Rubik's Cube Orientation with CNN Regression

This is a project built while participating in the AIcrowd KIIT(AI) Mini Blitz Challenge and is the final one out of the three challenges given. We are given a train and test set and the objective is to detect the angle of orientation of the rubik's cube, based on the image given, on a continuous scale between 0 to 360. what food item is presen in the given image. We used CNN for Regression here due to our target variable being a continuous integer and worked with about 5000 images to train our model. 


  
## 🚀 The Result

I was able to get a **MSE score of 78.103** on the test set and secured the second place for this specific puzzle as of now.
 

## ✏ Tech Stack for Project Development

- Python
- Numpy
- Pandas
- Scikit-learn
- Tensorflow

  
## 🧠 The Approach

 We used a Convolutional Neural Network for Regression to achieve this task. First, we built the model with two Conv2D layers to extract the features which gives the useful information in the image. Then we passed it through a GlobalAveragePooling2D to flatten its dimension after which the regular Keras dense layers were used with 64 neurons twice to give our final linear output. For training, we trained for about 120 epochs to get the above score and this could be further improved by training for an even greater number of epochs. At the end, the predictions on the given 5000 unlabelled images were submitted to get the score written above. 

  

## 🔗 Connect with me:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.polywork.com/kunal_bhadra)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunal-bhadra-cs/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kunal_kaun)

  