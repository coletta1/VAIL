# [SureStart](https://mysurestart.com/)
Repository for my daily assignments and responses

"SureStart’s mission is to build early opportunity pipelines for a highly diverse tech workforce through technical skills training and project-based learning. We are specifically committed to training and mentoring high-school and college students from communities underrepresented in AI, and connecting them to opportunities for hands-on work in innovative DEI-focused tech startups."

## Responses

<br>

#### Day 1 (February 8th, 2021): Welcome to SureStart!
##### Reflect on what you hope to learn in this program

As a senior poised to graduate from college, I have enjoyed my AI classes and want to dive deeper into the application of these ideas. I have coded many of these types of networks from scratch and am interested in becoming more familiar with ML libraries beyond NumPy, as they are useful in real-world contexts. I'd love to finish this program armed with deeper knowledge of various concepts and architectures, which will hopefully translate into applicable skills so I can get a job in a field I am interested in!

I'm especially excited for the Makeathon because I want to not only learn but develop real solutions to meaningful problems.

***

#### Day 2 (February 9th, 2021): Introduction to Machine Learning (ML) AND Scikit-learn
##### What is the difference between supervised and unsupervised learning? 

Supervised learning is trained on labeled examples, with expected outputs, whereas unsupervised learning aims to find patterns within data without pre-defined relationships between input and output.

##### Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without Graphviz, Pandas, or other data analysis libraries.
As a ML library, Scikit-learn is concerned with data modeling, not with visualization or display. These other libraries are able to bridge the gap and serve as a visualization interface for models and data.


***

#### Day 3 (February 10th, 2021):

##### What are “Tensors” and what are they used for in Machine Learning? 
Tensors are multidimensional arrays that are generalizations of vecotrs matrixes etc. They are used to store data for ML and can be manipulated with various mathematical operations.

##### What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?
I noticed that a lot of the math is hidden behind tensorflow so if you're not careful, you might not actually know what you're doing.
***

#### Day 4 (February 11th, 2021): WHAT IS DEEP LEARNING?
##### Think about a real-world problem and see if you can find a dataset that has the characteristics of the data of that problem. Then, think about the deep learning algorithm that you would likely use to develop a solution to it. Outline why you picked a particular approach.

A real world problem I heard about recently is that oftentimes, in animal shelters, dogs can be grossly mislabeled by breed. This can lead to fewer dogs being adopted due to people becoming frustrated with the process, or getting a dog they aren't expected after putting in the time to select one. Here is a dataset with 20,000 images of dogs of 120 different breeds: https://www.kaggle.com/jessicali9530/stanford-dogs-dataset. I would use a CNN because they tend to be really good for image classification.
***

#### Day 5 (February 11th, 2021): WHAT ARE NEURAL NETWORKS (NN)?

***
### WEEK 2 - CNNS, DATA & MACHINE LEARNING
***

#### Day 8 (February 11th, 2021): INTRODUCTION TO CONVOLUTIONAL NEURAL NETWORKS (CNNS)

***

#### Day 9 (February 16th, 2021): ALGORITHMIC BIAS AND DATA SETS
##### How do you think Machine Learning or AI concepts were utilized in the design of this game?
The game was really interesting because it showed just how innocently bias can appear in ML models. Since they reflect back the patterns they see in data, latent relationships that are actually not important are mimiced and perpretuated. 

##### Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.
I'd say that most models that make judgements on humans are likely to biased. With facial recognition and classification software that has been trained to identify gender of faces, there is potential for bias both racial, as they can be less accurate on darker skinned people, and gender discrimination, especially as it pertains to gender non-conformity. The first problem could be helped with more data, and more a equally distributed training set. This could help with the second as well, but it also brings up the question of if we should even be creating certain models in the first place. It's possible and even likely that for many queer people, these models will never approach fairness because for many people (percieved) gender and appearance are not congruous.

#### Day 10 (February 17th, 2021): NEURAL NETWORK LAYERS
##### Succinctly list the differences between a Convolutional Neural Network and a Fully Connected Neural Network. Discuss layers and their role, and applications of each of the two types of architecture.
CNNs are networks that have a series of layers, that essentially filter pixels in various ways and use these convolutions to extract features. For a fully connected neural network, each neuron in a layer is connected with all the other neurons in the adjacent layers, which makes for a whole lot of weights! CNNs are typically used to do work on images and fully connected neural nets have more general-purpose applications.

#### Day 16 (February 23th, 2021): Activation Functions
##### Write a reflection piece on the advantages of the Rectified Linear activation function, along with one use case.
One advantage of the ReLU function is the it is less susceptible to the vanishing gradient problem. It also is less computationally expensive than sigmoid and tan h because of it's simplicty, as a function that outputs the input directly if it is positive and outputs 0 otherwise. This is also important because it means it can output true zero values. ReLU is commonly used in CNN's, so for example it could potentially be used for classification of dog species.
