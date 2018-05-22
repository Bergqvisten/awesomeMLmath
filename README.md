# awesomeMLmath
Curated list to learn the math basics for machine learning. Note that this is a biased list from a Deep Learning researcher.

The main topics are Calculus, Linear Algebra, Statistics, Probability and Signal Processing. If you "combine" Probability with Signal Processing you have Stochastic Processes which is the theory behind RNN, Kalman Filters, etc.

### Calculus
[Khan Academy Calculus](https://www.khanacademy.org/math/calculus-home)

### Linear Algebra
[Khan Academy Linear Algebra](https://www.khanacademy.org/math/linear-algebra)  
[Linear Algebra MIT](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-21-eigenvalues-and-eigenvectors/)  
Note that it is good to learn about eigenvalue decomposition, etc (DO NOT stop with just solving system of equations). You will use that to understand Principal Compoenent Analysis and the idea of space transformation which is what feature learning is all about.

### Statistics and probability
[edx Introduction to Statistics](https://www.edx.org/course/introduction-statistics-descriptive-uc-berkeleyx-stat2-1x)  
[edx Probability](https://www.edx.org/course/introduction-statistics-probability-uc-berkeleyx-stat2-2x)  
[An exploration of Random Processes for Engineers](http://www.ifp.illinois.edu/~hajek/Papers/randomprocDec11.pdf) this is an advanced course but one of my favorites.  
[Information Theory](http://colah.github.io/posts/2015-09-Visual-Information/)  
Here is the deal, a probability density function (pdf) is as much as we can know about a radom variable. Machine Learning is about estimating "momements" (you should learn that) of a pdf. If your random variable is not Gaussian, you will need more than mean and variance to correctly describe it (mean and var are the 1st and 2nd order moments). Information Theory generalizes all that.

### Signal Processing
Signal processing will teach what are convolutions (for you convolutional neural nets). But no worries, signal processing is just linear algebra++. Ex. Fourier Transforms is an eigenvalue decomposition. All is one. If you trully learned linear algebra this part if mostly free.  
[edx Signals and Systems, part 1](https://www.edx.org/course/signals-systems-part-1-iitbombayx-ee210-1x-1)  
[edx Discrete Time Signal Processing](https://www.edx.org/course/discrete-time-signal-processing-mitx-6-341x-1)  
[adaptive signal processing](https://en.wikipedia.org/wiki/Adaptive_filter) this is the basis of neural nets, but I couldn't find modern video material...

### Other lists
[What are some beginner deep learning projects](https://www.quora.com/What-are-some-beginner-Deep-Learning-project-ideas)  
[What are the best ways to pick up Deep Learning skills as an engineer?](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer/answer/Greg-Brockman) answer by Greg Brockman

### How to study, the "degrees"
To get a practitioner badge, you should feel good if you can use [Keras](https://github.com/fchollet/keras.git) and [XGboost](https://github.com/dmlc/xgboost) for Kaggle competitions.    

A developer level asks for the ability to write your own multilayer perceptron from scratch and contribute new layers to Keras. This means implementing models from papers in Theano or Tensorflow. You should need calculus and linear algebra to understand what you are doing. Maybe some statistics and probability to understand the expectation operators and cost functions.  

To get your researcher degree you should be exploring new fields and writing new types of models. I can't tell you what to study to do that. Maybe nothing, maybe everything, if I knew it wouldn't be called research. But if you can understand the "An exploration of Random Processes for Engineers" you may already know most of the basic and intermediary math necessary.
