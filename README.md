# Suet-Wah-CHU_Portfolio
Welcome to my Github Portfolio! I am Suet Wah CHU (Sarah), a graduate student at Toulouse Business School, France, studying Artificial Intelligence and Business Analytics with some amazing and pratical projects. Any comments or guidance would be much appreciated!  

## Classification
### [Project 1 : NLP - Hate Speech Detection](https://github.com/Sarah-chu/AI-and-Big-Data-Project-Hate-Speech--1)
- ~34k posts/tweets with 3 categories(hate speech, offensive language, neither) were classified
- Achieved recall score of **92%** for hate speech and **89%** for offensive language using **SVM** with *Python*
- **Unbalanced dataset** problem was handled by adding 2 extra datasets (more content and more topics of hate speech)
- A [Web App](https://hate-speech-detection-tbs.herokuapp.com/) was built for users to test if they are posting hate speech or offensive language

### [Project 2 : CNN & Image Recognition - Metallic Surface Anomaly Detection](https://github.com/Sarah-chu/CNN-Metallic-Surface-Anomaly-Detection)
- 1,800 grayscale images of **6 different types** of typical surface defects of the hot-rolled steel strip
- Achived **95% accuracy** of detection by using a convolutional neural network with **PyTorch**
- The convolutional neural network consists of 3 convolutional layers and 3 dense layers, and applies rectified linear on each convolutional layers with max pooling over 3x3 pixels
- Can further develop into an application to detect defects on the surface of a metal part during the quality control process in the production lin

### [Project 3 : Human Resources - IBM HR Analytics Employee Attrition Performance](https://github.com/Sarah-chu/Classification-IBM-HR-Analytics-Employee-Attrition-Performance-)
- Predicted if an employee is likely to quit the company based on the dataset consisited of 1233 employees with 16.1% attrition rate 
- Gaussian Naive Bayes was selected as the best model from Logistic Regression, KNN, Decision Tree and Random Forest, based on sensitivity(recall)
- Achieved **68% recall** without any sampling method, will update the model using some sampling method in the future
- **8 influential factors of attrition** were identified and **6 recommendations** were made based on the key findings and data analysis
