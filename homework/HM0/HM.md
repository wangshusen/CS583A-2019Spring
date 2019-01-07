Homework and Further Reading
============


Submission and Deadline
---------

Submission is not required. Finish the reading before the first quiz. (You may fail the quiz if you do not read the matrix calculus.)


Homework
---------

Setup Python, Jupyter, TensorFlow and Keras.

1. Install Python 3.3 or greater. Do not use Python 2.X
    
2. Install Jupyter notebook: [[guide](http://jupyter.org/install)]
    
3. Install TensorFlow: [[guide](https://www.tensorflow.org/install/)]
    
4. Install Keras: [[guide](https://keras.io/#installation)]
    
5. Make sure Keras has been properly installed: [[run the code](https://keras.io/#getting-started-30-seconds-to-keras)]


Further Reading
---------

Self-study matrix algebra by reading the following articles:

1. [Matrix Calculus](https://github.com/wangshusen/CS583A-2019Spring/blob/master/reading/MatrixCalculus.pdf). (Required. Print and bring it to the quiz.)
    
2. Appendix A of [Convex Optimization]() (Optional. It is available online; Google it.)
    
3. Chapters 1 and 2 of [The Matrix Cookbook](). (Optional. It is available online; Google it.)


Sample Questions
---------

Basic matrix algebra and vector/matrix differentiation are parts of the first quiz and the final. Here are some sample questions.

1. $\mathbf{a} = [3, -5, 0, 0, -1]$ is a vector. Calculate the values of the following vector norms:

    -- the squared $\ell_2$-norm: $|| \mathbf{a} ||_2^2$, 
    
    -- the $\ell_2$-norm: $|| \mathbf{a} ||_1$,
    
    -- the $\ell_\infty$-norm: $|| \mathbf{a} ||_\infty$.

2. Let $\mathbf{I}_{5}$ be the $5\times 5$ identity matrix. Calculate the following values:

    -- the largest eigenvalue: $\lambda_{\max} ( \mathbf{I}_{5} )$,
    
    -- the smallest eigenvalue: $\lambda_{\min} ( \mathbf{I}_{5} )$,
    
    -- the trace: $tr ( \mathbf{I}_{5} )$,
    
    -- the squared Frobenius norm: $|| \mathbf{I}_{5} ||_F^2$.

3. What is the derivative of $f (\mathbf{x}) = || \mathbf{A} \mathbf{x} + \mathbf{b} ||_2^2 + || \mathbf{x} ||_2^2 + \mathbf{c}^T \mathbf{x} + d$ with respect to the vector $\mathbf{x}$? Here, $\mathbf{A}$ is a matrix, $\mathbf{b}$ and $\mathbf{c}$ are vectors, and $d$ is a scalar.

4. $\mathbf{x} = [x_1, x_2 , x_3]$ is a 3-dimensional vector. What is the derivative of $f (\mathbf{x}) = e^{x_1} + x_2^4 + x_2 x_3 + 5 \cdot \cos (x_3)$ with respect to the vector $\mathbf{x}$?
