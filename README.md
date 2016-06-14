#Polisci Reading Group on Deep Learning and Neural Networks
##Resources

###[Google's Tensorflow mooc](https://classroom.udacity.com/courses/ud730/lessons/6370362152/concepts/63798118150923)
This is a deep learning mooc by google that uses tensorflow. It does seem to cover a lot of foundational topics in DL and consequently NNs. It covers the two main topics I am (and presumably we all are) interested in: RNNs for sequential data, and CNNs for image data. They present it as a very hands-on approach, with Ipython NB assignments, and practical training in how to use Tensorflow. 
The main problem with this is that it may be a little too basic. 

***

### [Stanford Computer Vision ](http://cs231n.stanford.edu/syllabus.html)
This is an undergrad class on computer vision that revolves mostly around current practices and foundations of CNNs. They have all the resources online (notes + slides + assigments), which are all well-written and easy to pick up. The assignments are nice ipython NBs that guide you through the problems (which to me is the sign of good assigments).
The main problem with this is that this is mostly focused on computer vision as an application of ML and NNs, however I think that we'll be able to translate anything we learn here to applications that are of interest to us easily.

***

###[Stanford  Deep Learning for NLP](http://cs224d.stanford.edu/index.html)
This is the same as computer vision but for text analysis. It goes through applications of deep learning to NLP, as well as some foundations of DL  and NNs itself. It's all nicely available and self-contained much like the CV class. 

***

###[Bishop ML]
THE book on theoretical ML. We'll be getting our math from here. 

***

###[UFLDL](http://ufldl.stanford.edu/wiki/index.php/UFLDL_Tutorial)
THE tutorial on deep learning. Was once a class at Stanford, not it's a publicly editable wiki. 

##Syllabus
Here is a list of topics that I think would be beneficial to know. It mostly follows the Google Mooc. The idea would be to adopt its structure but complement it with readings/assigments from the other classes and books which should be somewhat more advanced.  I'll update this with links to the relevant sections of the resources listed above. We don't necessarily have to go through everything. 

### Introduction/General ML  
1. Classification Problems (GG) (What is Deep Learning? - Let's Get Started.)
 	. . a ([CV](http://cs231n.github.io/classification)) KNN Image Classification.
2. Softmax Classifier (GG) (Training Your Logistic Classifier - One-Hot Encoding)
	. . a ([CV](http://cs231n.github.io/linear-classify)) Linear Classification
	. . b ([UL](http://ufldl.stanford.edu/wiki/index.php/Softmax_Regression)) Softmax Regression
3. Loss Functions (GG) (Cross Entropy - Assignment 1: notMNIST)
4. Cross-Validation (GG) (Measuring Performance - Validation Test Set Size Continued)
5. Stochastic Optimization (GG) (Optimizing a Logistic Classifier - Momentum and Learning Rate Decay)
 	. . a ([CV](http://cs231n.github.io/optimization-1/)) Optimization
 	. . b ([UL](http://ufldl.stanford.edu/wiki/index.php/Gradient_checking_and_advanced_optimization)) Gradient Checking
6. Hyperparameter Tuning (GG) (Parameter Hyperspace)

### Neural Networks
1. Rectified Linear Units (GG) (Intro to Lesson 2 - Rectified Linear Units)
2. Simple Network (GG) (Network of ReLUs - 2-Layer Neural Network)
	. . a ([CV](http://cs231n.stanford.edu/slides/winter1516_lecture4.pdf)) Intro to NNs.
	. . b ([NLP](http://cs224d.stanford.edu/lecture_notes/notes3.pdf)) NNs for Named Entity Recognition.
	. . c ([UL](http://ufldl.stanford.edu/wiki/index.php/Neural_Networks)) Neural Networks.
3. Backpropagation (GG) (The Chain Rule - Assignment 2)
	. . a ([UL](http://ufldl.stanford.edu/wiki/index.php/Backpropagation_Algorithm)) Backpropagation.
	. . b ([CV](http://cs231n.github.io/optimization-2/)) Backpropagation.
4. Deep Networks (GG) (Training a Deep Learning Network)
5. Regularization (GG) (Regularization Intro - Assigment 3: Regularization)
5. Autoencoders

### Convolutional NNs
1. Statistical Invariance
2. Convolutions
3. Inception 
4. Advice for Training Convnets

### Recursive NNs 
1. Embeddings
2. Word2Vec
3. RNNs
	a. Backprop through time
	b. Vanishing Gradients
4. LSTM
	a. Cells
	b. Beam Search
	c. Regularization 
	
	
##Organization
How should we organize the group? Should we have one of us summarize and present on each topic every week? How many times a week should we meet? I was thinking 2 to 3, but we could also meet once and go over everything for that section. 

##Projects/Practice
I think we should practice while we go through the material. Most of the online classes listed have nice Ipython NBs guided assigments that we could do. Otherwise we could try and develop our own project but I'm afraid that we might not be able to do it without practicing first. 

##Which Library?
So most of these use Tensorflow, which I'd be ok with learning. Alternatives are theano or torch. I have no strong preference, Tensorflow seems the most convenient because most of the material in the resource list depends on it. 

	