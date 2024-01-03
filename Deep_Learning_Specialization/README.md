# Deep Learning Specialization
[![GitHub Repo](https://img.shields.io/badge/Deep%20Learning%20Sepcialization%20Repository-blueviolet?logo=github&style=flat-square)](https://github.com/hgnzheng/CS230_Stanford/tree/main/Deep_Learning_Specialization)

![](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/coursera_page.png)

---
[<img src="https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/deep_learning_ai_logo.png" width="200"/>](https://www.deeplearning.ai)

**Instructor: [Andrew Ng](https://www.andrewng.org/)**

[Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)

[DeepLearning.AI Discussion Board](https://community.deeplearning.ai/c/deep-learning-specialization/6)

My complete notes for the specialization can be found [here](https://github.com/hgnzheng/CS230_Stanford/tree/main/Deep_Learning_Specialization/Deep_Learning_Notes.pdf)

*Note: As per Coursera **Deep Learning Honor Code**, students are not allowed to post code publicly on GitHub. In adherence to the Honor Code, I will not be posting my code solutions.*

## Course Certificates

![](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/specialization.png)

* [Course 1: Neural Networks and Deep Learning](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/course_1.pdf)
* [Course 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/course_2.pdf)
* [Course 3: Structuring Machine Learning Projects](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/course_3.pdf)
* [Course 4: Convolutional Neural Networks](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/course_4.pdf)
* [Course 5: Sequence Models](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/certificates/course_5.pdf)


## Programming Assignments

### Course 1: Neural Networks and Deep Learning

  * Week 1 - First week doesn't have any Programming Assignment
  * Week 2 - Programming Assignment(1) - Logistic Regression with a Neural Network mindset
  * Week 3 - Programming Assignment(1) - Planar data classification with one hidden layer
  * Week 4 - Programming Assignment(1) - Building your Deep Neural Network: Step by Step
  * Week 4 - Programming Assignment(2) - Deep Neural Network for Image Classification: Application

### Course 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization

  * Week 1 - Programming Assignment(1) - Initialization
  * Week 1 - Programming Assignment(2) - Regularization
  * Week 1 - Programming Assignment(3) - Gradient Checking
  * Week 2 - Programming Assignment(1) - Optimization Methods
  * Week 3 - Programming Assignment(1) - TensorFlow Tutorial

*Note: For Week 3 PA, we would need to use TensorFlow version 2.3.0. Using 2.15.0 would fail some tests, as it calculates sigmoid differently.*

### Course 3: Structuring Machine Learning Projects

  * This course doesn't have any programming assignments.
  
### Course 4: Convolutional Neural Networks

  * Week 1 - Programming Assignment(1) - Convolutional Model, Step by Step
  * Week 1 - Programming Assignment(2) - Convolution Model Application
  * Week 2 - Programming Assignment(1) - Residual Networks
  * Week 2 - Programming Assignment(2) - Transfer Learning with MobileNet
  * Week 3 - Programming Assignment(1) - Car detection with YOLO
  * Week 3 - Programming Assignment(2) - Image Segmentation with U-Net
  * Week 4 - Programming Assignment(1) - Face Recognition
  * Week 4 - Programming Assignment(2) - Art Generation with Neural Style Transfer

### Course 5: Sequence Models

  * Week 1 - Programming Assignment(1) - Building a Recurrent Neural Network - Step by Step
  * Week 1 - Programming Assignment(2) - Dinosaur Island-Character-Level Language Modeling
  * Week 1 - Programming Assignment(3) - Jazz improvisation with LSTM
  * Week 2 - Programming Assignment(1) - Operations on Word Vectors - Debiasing
  * Week 3 - Programming Assignment(1) - Neural Machine Translation
  * Week 3 - Programming Assignment(2) - Trigger Word Detection
  * Week 4 - Programming Assignment(1) -  Transformers Architecture with TensorFlow

*Note: For Week 3 PA2, make sure to run `pip install --upgrade emoji==1.6.3` to avoid error messages due to updates of `emoji` package. Also, although section 1.4 writeup says the training process will take about 5 minutes, it took me about 5 minutes to run each 100 epochs -- 20 minutes for a total of 400 default iterations. It's possible to speed up the process with GPU. 96.2% training accuracy is obtained after 100th epoch. 100% training accuracy is obtained after 200 epochs. In section 2.4, the model type should be `<class 'keras.src.engine.functional.Functional'>`, so the assert will fail.*

## Weekly Quizzes

### Course 1: Neural Networks and Deep Learning

  * Week 1 Quiz - [Introduction to deep learning](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C1_W1.pdf)
  * Week 2 Quiz - [Neural Network Basics](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C1_W2.pdf)
  * Week 3 Quiz - [Shallow Neural Networks](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C1_W3.pdf)
  * Week 4 Quiz - [Key concepts on Deep Neural Networks](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C1_W4.pdf)

### Course 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization

  * Week 1 Quiz - [Practical aspects of deep learning](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C2_W1.pdf)
  * Week 2 Quiz - [Optimization algorithms](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C2_W2.pdf)
  * Week 3 Quiz - [Hyperparameter tuning, Batch Normalization, Programming Frameworks](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C2_W3.pdf)
  
### Course 3: Structuring Machine Learning Projects

  * Week 1 Quiz - [Bird recognition in the city of Peacetopia (case study)](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C3_W1.pdf)
  * Week 2 Quiz - [Autonomous driving (case study)](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C3_W2.pdf)

### Course 4: Convolutional Neural Networks

  * Week 1 Quiz - [The basics of ConvNets](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C4_W1.pdf)
  * Week 2 Quiz - [Deep convolutional models](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C4_W2.pdf)
  * Week 3 Quiz - [Detection algorithms](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C4_W3.pdf)
  * Week 4 Quiz - [Special applications: Face recognition & Neural style transfer](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C4_W4.pdf)

### Course 5: Sequence Models

  * Week 1 Quiz - [Recurrent Neural Networks](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C5_W1.pdf)
  * Week 2 Quiz - [Natural Language Processing & Word Embeddings](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C5_W2.pdf)
  * Week 3 Quiz - [Sequence models & Attention mechanism]
  * Week 4 Quiz - [Transformers](https://github.com/hgnzheng/CS230_Stanford/blob/main/Deep_Learning_Specialization/Quiz/C5_W4.pdf)

*Note: Quizzes serve as checkpoints of your own understanding of the course materials. Please do not rely on the solutions in this repository to pass the weekly quizzes! Solutions are posted here for record and reference learning resources.*