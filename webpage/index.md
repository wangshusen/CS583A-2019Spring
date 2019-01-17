CS583: Deep Learning
============


> Instructor: Shusen Wang


Description
---------

**Meeting Time:**

- Thursday, 6:30 - 9:00 PM, Babbio Center 221

- The classes on these dates are canceled: Jan 31


**Office Hours:**

- Thursday, 3:00 - 5:00 PM, North Building 205

- The office hours on these dates are canceled: Jan 31, Feb 28


**Prerequisite:**

- Elementary linear algebra, e.g., matrix multiplication, eigenvalue decomposition, and matrix norms.

- Elementary calculus, e.g., convex function, differentiation of scalar functions, first derivative, and second derivative.

- Python programming (especially the Numpy library) and Jupyter Notebook.


**Goal:** This is a practical course; the students will be able to use DL methods for solving real-world ML, CV, and NLP problems.


Schedule
---------

- Jan 24, Lecture 1

    -- Fundamental ML problems
    
    -- Regression
    
- Jan 24, **Homework 0** is assigned.

    -- [Click here for the assignment](https://github.com/wangshusen/CS583A-2019Spring/blob/master/homework/HM0/HM.pdf)
    
    -- Submission is not required. 
    
    -- Deadline: finish it before the 1st Quiz. (Otherwise, you will probably fail.)
    
- Jan 24, **Homework 1** is assigned (available on Canvas).
    
    -- Submission: submit to Canvas.
    
    -- Deadline: Feb 24.

- Jan 31, **CANCELED** due to the instructor's conference traveling

- Feb 7, Lecture 2

    -- Regression (cont.)
    
    -- Classification
    
- Feb 14, Lecture 3

    -- Classification (cont.)
    
    -- Dimensionality reduction
        
- Feb 14, **Homework 2** is assigned (available on Canvas).
    
    -- Submission: submit to Canvas.
    
    -- Deadline: Mar 14.

- Feb 21, Lecture 4

- Feb 28, **Quiz 1** (coverage: linear algebra, optimization, and ML basics).

- Mar 7, **Project proposal deadline**

- Mar 7, Lecture 5
	
	-- Neural network basics
	
	-- Keras
	
- Mar 14, Lecture 6

	-- Neural network basics (cont.)

	-- Convolutional neural networks

- Mar 21, Spring Break, no class

- Mar 28, Lecture 7

	-- Convolutional neural networks (cont.)

- Apr 4, Lecture 8

	-- Convolutional neural networks (cont.)
	
- Apr 11, Lecture 9

	-- Autoencoders
	
- Apr 18, Lecture 10

	-- Recurrent neural networks
	
- Apr 25, Lecture 11

	-- Recurrent neural networks (cont.)
	
- May 2, Lecture 12

	-- Recurrent neural networks (cont.)
	




Syllabus and Slides
---------

1. **Machine learning basics.**
This part briefly introduces the fundamental ML problems-- regression, classification, dimensionality reduction, and clustering-- and the traditional ML models and numerical algorithms for solving the problems.

    -- ML basics. [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/1_ML_Basics.pdf)]
    
    -- Regression. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/2_Regression_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/2_Regression_2.pdf)]
    
    -- Classification. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_1.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_2.pdf)] 
    [[slides-3](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_3.pdf)] 
    [[slides-4](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/3_Classification_4.pdf)]
    
    -- Regularizations. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/4_Optimization.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/4_Regularizations.pdf)]
    
    -- Dimensionality reduction. 
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_SVD.pdf)] 
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_PCA.pdf)] 
    [[slides-3](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/5_MatrixComputations.pdf)]
    
2. **Neural network basics.**
This part covers the multilayer perceptron, backpropagation, and deep learning libraries, with focus on Keras.

    -- Multilayer perceptron and backpropagation. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/6_NeuralNet_1.pdf)]
    
    -- Keras. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/6_NeuralNet_2.pdf)]
    
    -- Further reading:
    [[activation functions](https://adl1995.github.io/an-overview-of-activation-functions-used-in-neural-networks.html)]
    [[loss functions](https://isaacchanghau.github.io/post/loss_functions/)]
    [[parameter initialization](https://isaacchanghau.github.io/post/weight_initialization/)]
    [[optimization algorithms](https://isaacchanghau.github.io/post/parameters_update/)]
    
3. **Convolutional neural networks (CNNs).**
This part is focused on CNNs and its application to computer vision problems.

    -- CNN basics.
    [[slides-1](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_1.pdf)]
    [[slides-2](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_2.pdf)]
    [[slides-3](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_3.pdf)]
    
    -- Advanced topics on CNNs. 
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_4.pdf)]
    
    -- Popular CNN architectures.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/7_CNN_5.pdf)]
    
    -- Further reading: 
    [style transfer (Section 8.1, Chollet's book)]
    [visualize CNN (Section 5.4, Chollet's book)]


4. **Autoencoders.**
This part introduces autoencoders for dimensionality reduction and image generation.

    -- Autoencoder for dimensionality reduction.[[slides]() to appear]
    
    -- Variational Autoencoders (VAEs) for image generation. [[slides]() to appear]

5. **More image generation methods.** **(Optional, depending on the progress.)**
This part covers two image generation approaches in addition to VAE.
The training of neural networks takes fixed images (X) as inputs and optimize w.r.t. the weights (W). Conversely, one can fix the network's weights (W) and optimize w.r.t. the input X. In this way, new images are generated to maximize (or minimize) some function; the application includes attacking neural networks and deep dream.
Another very different approach is the generative adversarial network (GAN).

    -- Attack neural networks. [[slides]() to appear]
    
    -- Deep dream. [[slides]() to appear]
    
    -- Generative adversarial network (GAN). [[slides]() to appear]


6. **Recurrent neural networks (RNNs).**
This part introduces RNNs and its applications in natural language processing (NLP).

    -- Text processing.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/10_RNN_1.pdf)]
    
    -- RNN basics and LSTM.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/10_RNN_2.pdf)]
        
    -- Text generation.
    [[slides](https://github.com/wangshusen/CS583A-2019Spring/blob/master/slides/10_RNN_3.pdf)]
    
    -- Machine translation. [[slides]() to appear]
    
    -- Attention. 
    [[slides]() to appear]
    
    
    -- Further reading: 
    [[attention](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)]
    [[GloVe: Global Vectors for Word Representation](http://www.aclweb.org/anthology/D14-1162)]
    [[Neural Word Embedding as Implicit Matrix Factorization](https://papers.nips.cc/paper/5477-neural-word-embedding-as-implicit-matrix-factorization.pdf)]

7. **Recommender system.** **(Optional, depending on the progress.)**
This part is focused on the collaborative filtering approach to recommendation based on the user-item rating data.
This part covers matrix completion methods and neural network approaches. 

    -- Recommender system. [[slides]() to appear]



Project
---------
Every student must participate in one [Kaggle competition](https://www.kaggle.com/competitions). 

- **Details**: [click here](https://github.com/wangshusen/CS583A-2019Spring/blob/master/project/Project/proj.pdf)

- **Deadlines**

    -- (Not required.) Submit a preliminary version to Canvas before April 21th if you want to compete for the presentation and bonus.     
    -- Submit the final version to Canvas before June 1st. 

- **Submissions**: Put your source code and report to a Github repository and submit the links to Canvas.
    
- **Teamwork policy**: You had better work on your own project. Teamwork (up to 3 students) is allowed if the competition has a heavy workload; the workload and team size will be considered in the grading.
    



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

- June 1 is the firm deadline of all the homework. Submissions later than June 1 will not be accepted.


