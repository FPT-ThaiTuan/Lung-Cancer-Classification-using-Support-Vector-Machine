# **Lung Cancer Classification using Support Vector Machine**
## 1. Introduction
- Lung cancer is one of the most common and deadly types of cancer worldwide. Early detection and accurate classification of lung cancer can significantly improve patient outcomes by enabling timely intervention and treatment. In this project, we aim to develop a lung cancer classification model using Support Vector Machine (SVM), a powerful machine learning algorithm known for its effectiveness in binary classification tasks.
## 2. Objective
- The primary objective of this project is to develop a robust classification model capable of accurately distinguishing between lung cancer and non-cancerous lung conditions based on medical imaging data. Specifically, we aim to achieve a classification accuracy of 100% to ensure reliable and trustworthy predictions for clinical use.
## 3. Project implementation
### 3.1. Read Data From Csv File
### 3.2. Visualizing the Data

- Displays the results of patients with and without cancer

![屏幕截图 2024-04-01 002356](https://github.com/FPT-ThaiTuan/Lung-Cancer-Classification-using-Support-Vector-Machine/assets/105273233/903c1b3b-d9b2-40c9-a078-3696fa6da085)

- Display data distribution in csv file

![download](https://github.com/FPT-ThaiTuan/Lung-Cancer-Classification-using-Support-Vector-Machine/assets/105273233/35055a75-4494-4774-9c85-a56556a1638f)

### 3.3. Data for Training and Testing
- Split the dataset into 2 sets of train and test with train = 80% and test = 20%, random_state = 42
### 3.4. Build model
- Support Vector Machine (SVM) with the following configured parameters: C=10, probability=True and random_state=9. 
- SVM is a powerful machine learning method commonly used for classification tasks, especially in problems with two layers of data.
### 3.5. Results and reviews
- Result confusion matrix

![download (1)](https://github.com/FPT-ThaiTuan/Lung-Cancer-Classification-using-Support-Vector-Machine/assets/105273233/cf28f4c4-edb4-4d91-b8bf-cef25983b563)

- Classification report

![屏幕截图 2024-04-01 003237](https://github.com/FPT-ThaiTuan/Lung-Cancer-Classification-using-Support-Vector-Machine/assets/105273233/7f371cdb-4062-4cc8-bee0-a22d99ae23b6)


- Calculate the accuracy score on the test set
  - Test accuracy result: 1.0


**Hope this article can help you.**

**If you have any questions please contact me for help!**

**Gmail: tuanddt.ai.work@gmail.com**

***Thanks everyone!***
