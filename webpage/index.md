CS583: Deep Learning
============


> Instructor: Shusen Wang

> TA: Yao Xiao


Description
---------

**Meeting Time:**

- Thursday, 6:30 - 9:00 PM, Peirce Complex 116

- **The classes on these dates are canceled: Jan 31**



**Office Hours:**

- Thursday, 3:00 - 5:00 PM, North Building 205

- **The office hours on these dates are canceled: Jan 31, Feb 28**

**Contact the Instructor:**

- For questions regarding grading, talk to the instructor during office hours or send him emails.

- For any other questions, come during the office hours; the instructor will NOT reply such emails.


**Prerequisite:**

- Elementary linear algebra, e.g., matrix multiplication, eigenvalue decomposition, and matrix norms.

- Elementary calculus, e.g., convex function, differentiation of scalar functions, first derivative, and second derivative.

- Python programming (especially the Numpy library) and Jupyter Notebook.


**Goal:** This is a practical course; the students will be able to use DL methods for solving real-world ML, CV, and NLP problems.


Schedule
---------

- Jan 24, Lecture 1

    * Fundamental ML problems
    
    * Regression
    
    * Classification 
    
- Jan 24, **Homework 0** is assigned.

    * [Click here for the assignment](https://github.com/wangshusen/CS583A-2019Spring/blob/master/homework/HM0/HM.pdf)
    
    * Submission is not required. 
    
    * Deadline: finish it before the 1st Quiz. (Otherwise, you will probably fail.)
    
- Jan 24, **Homework 1** is assigned (available on Canvas).
    
    * Submission: submit to Canvas.

- Jan 31, **CANCELED** due to the instructor's conference traveling

- Feb 7, Lecture 2
    
    * Classification (cont.)
    
    * Regularization
    
- Feb 14, Lecture 3
    
    * Dimensionality reduction
    
    * Matrix computations
    
    * Neural network basics
        
- Feb 14, **Homework 2** is assigned (available on Canvas).
    
    * Submission: submit to Canvas.

- Feb 21, Lecture 4

	* Clustering
	
	* Keras
	
	* Preparation for Quiz
	
	* Convolutional neural networks

- Feb 24, **Deadline for Homework 1**

- Feb 28, **Quiz** (No lecture).

	* Coverage: linear algebra, optimization, and ML basics.
	
	* Policy: No electronic device. Printed material is allowed. 
	
	* Sample questions: [[click here](https://github.com/wangshusen/CS583A-2019Spring/blob/master/homework/Quiz1-Sample/Quiz.pdf)]

- Mar 7, Lecture 5
	
	* Convolutional neural networks (cont.)
	
- Mar 7, **Homework 3** is assigned
	
	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583A-2019Spring.git)]
	
    * Submission: submit to Canvas.
    
    
- Extended to Mar 8 (originally Mar 7), **Deadline for project proposal**

	* Submission: Everyone must submit a proposal to Canvas, even if it is teamwork.
	
	* The finally participated competition is supposed be the same as in the proposal. If otherwise, convincing explanation and evidence must be provided in the project document to avoid penalty.
	
    
- Mar 14, Lecture 6

	* Convolutional neural networks (cont.)
	
	* Autoencoders
	
- Mar 14, **Deadline for Homework 2**

- Mar 15, **Homework 4 and Homework 5** are assigned
	
	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583A-2019Spring.git)]
	
    * Submission: submit to Canvas.

- Mar 21, Spring Break, no class

- Mar 28, Lecture 7
	
	* Autoencoders (cont.)
	
	* Recurrent neural networks

- Apr 4, Lecture 8

	* Recurrent neural networks (cont.)

	* Optimization [[read this](https://github.com/wangshusen/CS583A-2019Spring/raw/master/reading/Logistic/Logistic.pdf)]
    
- Apr 7, **Deadline for Homework 3**

- Apr 11, Lecture 9

	* Recurrent neural networks (cont.)
	
	* Recommender system
	
- Apr 18, Lecture 10

	* Adversarial robustness
	
	* GANs
	

- Apr 21, **Deadline for signing up for project presentation**

	* Voluntary. Up to 5 bonus scores to the total.
	
    * Submission: submit to Canvas.
    
    * Selected at most 7 teams.
    
    * Selection criteria: Is the problem challenging? Does your method have novelty? Do you have good preliminary results? Can the audience learn anything from your presentation?


- Apr 25, Lecture 11

	* Deep dream
	
	* Preparations for the final exam.
	
- May 2, **Final Exam**

	* Coverage: linear algebra, optimization, ML basics, neural network basics, CNN, RNN, Python programming, Keras, and content in the textbook. [[Click here](https://github.com/wangshusen/CS583A-2019Spring/blob/master/homework/Coverage/coverage.pdf)] for the list.
	
	* Policy: No electronic device. Printed material is allowed. 
	
- May 4, **Deadline for Homework 4**

- May 5, **Deadline for Homework 5**

- May 9, **Project Presentation**

	* Time and location: the same as the class.
	
	* The selected groups are required to attend.
	
	* If you are confident that you will get A without the bonus, you can email the instructor to cancel your presentation. But the cancelation request must be made 48 hours prior to the presentation to avoid penalty.

- May 19, **Deadline for Course Project**

    * Submission: submit to Canvas.




Syllabus and Slides
---------

1. **Machine learning basics.**
This part briefly introduces the fundamental ML problems-- regression, classification, dimensionality reduction, and clustering-- and the traditional ML models and numerical algorithms for solving the problems.

    * ML basics. [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/1_ML_Basics.pdf)]
    
    * Regression. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/2_Regression_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/2_Regression_2.pdf)]
    
    * Classification. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_1.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_2.pdf)] 
    [[slides-3](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_3.pdf)] 
    [[slides-4](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_4.pdf)]
    
    * Regularizations. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Optimization.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Regularizations.pdf)]
    
    * Clustering. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/4_Clustering.pdf)] 
    
    * Dimensionality reduction. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_DR_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_DR_2.pdf)] 
    
    * Scientific computing libraries.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_DR_3.pdf)]
    
2. **Neural network basics.**
This part covers the multilayer perceptron, backpropagation, and deep learning libraries, with focus on Keras.

    * Multilayer perceptron and backpropagation. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/6_NeuralNet_1.pdf)]
    
    * Keras. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/6_NeuralNet_2.pdf)]
    
    * Further reading:
    [[activation functions](https://adl1995.github.io/an-overview-of-activation-functions-used-in-neural-networks.html)]
    [[loss functions](https://isaacchanghau.github.io/post/loss_functions/)]
    [[parameter initialization](https://isaacchanghau.github.io/post/weight_initialization/)]
    [[optimization algorithms](https://isaacchanghau.github.io/post/parameters_update/)]
    
3. **Convolutional neural networks (CNNs).**
This part is focused on CNNs and its application to computer vision problems.

    * CNN basics.
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_1.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_2.pdf)]
    [[slides-3](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_3.pdf)]
    
    * Advanced topics on CNNs. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_4.pdf)]
    
    * Popular CNN architectures.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_5.pdf)]
    
    * Face recognition.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_6.pdf)]
    
    * Further reading: 
    [style transfer (Section 8.1, Chollet's book)]
    [visualize CNN (Section 5.4, Chollet's book)]


4. **Autoencoders.**
This part introduces autoencoders for dimensionality reduction and image generation.

    * Autoencoder for dimensionality reduction.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/8_AE_1.pdf)]
    
    * Variational Autoencoders (VAEs) for image generation. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/8_AE_2.pdf)]


5. **Recurrent neural networks (RNNs).**
This part introduces RNNs and its applications in natural language processing (NLP).

    * Text processing.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_1.pdf)] 
       
    * RNN basics and LSTM.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_2.pdf)]
    [[reference](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)]
   
    * Text generation.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_3.pdf)]
    
    * Machine translation. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_4.pdf)]
    
    * Attention. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_5.pdf)]
    [[reference-1](https://distill.pub/2016/augmented-rnns/)]
    [[reference-2](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)]
    
    * Image caption generation. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/9_RNN_6.pdf)]
    [[reference](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)]
    
    * Further reading: 
    [[GloVe: Global Vectors for Word Representation](http://www.aclweb.org/anthology/D14-1162)]
    [[Neural Word Embedding as Implicit Matrix Factorization](https://papers.nips.cc/paper/5477-neural-word-embedding-as-implicit-matrix-factorization.pdf)]


6. **Recommender system.** 
This part is focused on the collaborative filtering approach to recommendation based on the user-item rating data.
This part covers matrix completion methods and neural network approaches. 

    * Collaborative filtering. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/10_Recommender.pdf)]


7. **Adversarial Robustness.**
This part introduces how to attack neural networks using adversarial examples and how to defend from the attack.

	* White box attack and defend.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/11_Adversarial.pdf)]
    
    * Further reading:
    [[Adversarial Robustness - Theory and Practice](https://adversarial-ml-tutorial.org/)]
    
8. **Generative Adversarial Networks (GANs).** **(Optional, depending on the progress.)**





Project
---------
Every student must participate in one [Kaggle competition](https://www.kaggle.com/competitions). 

- **Details**: [[click here](https://github.com/wangshusen/CS583A-2019Spring/blob/master/project/Project/proj.pdf)]
   
- **Teamwork policy**: You had better work on your own project. Teamwork (up to 3 students) is allowed if the competition has a heavy workload; the workload and team size will be considered in the grading.

- **Grading policy**: see the tentative evaluation form [[click here](https://github.com/wangshusen/CS583A-2019Spring/blob/master/project/Evaluation/Evaluation.pdf)]
    



Textbooks
---------

**Required**:

- Francois Chollet. Deep learning with Python. Manning Publications Co., 2017. (Available online.)

**Recommended**:

- Y. Nesterov. Introductory Lectures on Convex Optimization Book. Springer, 2013. (Available online.)

- D. S. Watkins. Fundamentals of Matrix Computations. John Wiley & Sons, 2004.

- I. Goodfellow, Y. Bengio, A. Courville, Y. Bengio. Deep learning. MIT press, 2016. (Available online.)
    
- M. Mohri, A. Rostamizadeh, and A. Talwalkar. Foundations of machine learning. MIT press, 2012.
    
- J. Friedman, T. Hastie, and R. Tibshirani. The elements of statistical learning. Springer series in statistics, 2001. (Available online.)



Grading Policy
---------

**Grading percentages**:

- Homework 50\%

- Final 15\%

- Project 20\%

- Quizzes 15\%

- Bonus (up to 10\%)

**Late penalty**:

- Late submissions of assignments or project document for whatever reason will be punished. 1\% of the score of an assignment/project will be deducted per day. For example, if an assignment is submitted 15 days and 1 minute later than the deadline (counted as 16 days) and it gets a grade of 95\%, then the score after the deduction will be: 95\% - 16\% = 79\%.

- June 1 is the firm deadline for all the homework and the course project. Submissions later than June 1 will not be graded.


