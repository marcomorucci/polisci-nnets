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
1. Classification Problems 
2. Softmax Classifier
3. Loss Functions
4. Cross-Validation 
5. Stochastic Optimization
6. Hyperparameter Tuning

### Neural Networks
1. Rectified Linear Units
2. Simple Network
3. Backpropagation
4. Deep Networks
5. Autoencoders
5. Regularization

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

	