# What is Machine Learning

If you are in the computer science field, you have probably heard of machine learning and how it is the next big thing. It seems that every new big discovery in computer science have been involving some kind of ML in the process. If you are anything like myself, you probably want to hop in the bandwagon and learn what machine learning is.  

Wikipedia defines machine learning as "the scientific study of algorithms and statistical models that computer systems use to perform a specific task without using explicit instructions, relying on patterns and inference instead". This definition gives us a pretty good idea of what ML really is, but it doesn't give us the big picture. It doesn't tell us what to learn or how the algorithms fit together.

I like to view machine learning as a mean to solve real world problems. We combine our mathematical knowledge and our programming skills to create algorithm that will, indeed, solve our problem by finding pattern and using inference. But ML is more than just algorithms. It's an art. We don't throw any algorithm mindlessly and hope that it solves our predicament. No. There are different ways to solve the same problem. We have to understand the pros and cons of each algorithm by considering its accuracy and its speed. Our job is to choose the one that best fit our needs.  

Not only do we have to consider different types of algorithms, but we have to consider what type of problem we have, as different problem involves different process. We have to understand how the algorithm fits within that framework. Each problem can be classified in the realm of:

- DATA ANALYSIS: describe (what), diagnose (why), predict(future) and prescribe(what can we do) 
- TIME-SERIES: predict future outcome with time and data
- BUSINESS INTELLIGENCE: report business operation, risk management, supply chain, marketing campain, customer retention
- SENTIMENT ANALYSIS: associating meaning to a word or group of word
- COMPUTER VISION: extract information from digital images or videos to reproduce human vision.
- QUANT: forecast future risks, predict macroenconomic trends, predict stock market
- NATURAL LANGUAGE PROCESSING: How a computer understand what we say (speech recognition) and respond back to us (vocal assistant)
- GAME THEORY: decision making in games
- FANTASY SPORT and ONLINE BETTING: assemble virtual team to win money
- SURVIVAL ANALYSIS: reliability analysis(engineering), duration analysis(economics), event history analysis (sociology)

# How to learn

Machine learning can be a daunting subject to learn, but with the right mindset and strategy, we can get the hang of it. We really want to learn the concept before writting code.  

The first thing to learn is basic maths: calculus, linear algebra. It's not primordial to know all the nitty-gritty details, but we want to have a good intuition on how the maths works. I assume you are familiar with that, but if you need a reminder, "Mathematics for Machine Learning" by Marc Peter Deisenroth is a great place to start: https://mml-book.github.io/book/mml-book.pdf

The second thing to learn is data manipulation. We want to be able to scrape data, import/export data, reformat table and manipulate strings. Two good languages for data science would be Python and R. Both do the same stuffs, but each they have their own advantages, so it might be a good idea to be familiar with both.

The third thing to learn is the algorithms. In the machine learning lingo, we refer to these algorithms as "models". Remember, our goal here is to assess the algorithm accuracy and speed by learning how it works ie how do we TRAIN it and how do we TEST it. Then, try to code it by yourself.

Finally, once we are familiar with different types of model, we can learn how to apply them in real world problem. Different problems have different needs. 

# Part 0: Mindset

Being able to read paper and implement maths equations.

# Part 1: Data Fundamentals

1. Gathering Data

Python - Beautiful Soup:
R - Rvest: https://www.youtube.com/watch?v=4IYfYx4yoAI&t=7s
R- Rvest (for tables) by R4DS: https://www.youtube.com/watch?v=0mvlZhYk44E&t=908s

2. Cleaning Data

Manipulate Strings:
Python - :
R - stringr:

3. Data manipulation

Manipulate Arrays:
Python - Numpy:
R - Purrr:

Manipulate DataFrame:
Python - Pandas: 
R - dplyr: https://www.youtube.com/watch?v=jOd65mR1zfw&list=PL9HYL-VRX0oQOWAFoKHFQAsWAI3ImbNPk

4. Plot Data

Python - Matplotlib:
R - ggplot2:
R - plotly:

# Part 2: Models

Machine learning models can be separated in 5 categories: supervised learning, unsupervised learning, neural networks, reinforcement learning and evolutionary comptuation. Each of these algorithm can be used to PREDICT, CLUSTER or CLASSIFY. Some of them are used specifically for DIMENSIONNALITY REDUCTION. These algorithms can also be SUPERVISED (the model knows the label when it test its accuracy) or UNSUPERVISED (the model doesn't know the label of the data). Understanding a model really boils down to TESTING (how the model transform input into ouputs) and TRAINING (how the model finds the optimal way to transform the inputs into outputs). 

The first thing to understand anout an algorithm is what it does. Is it used for prediction, for classification or for clustering? 
Knowing what the model does will allow you to position it to similar algorithms and to understand why it does what it does. You also want to know in which families the model is in. Models in similar families usually works the same way, so if you know how one works, it will greatly help you to understand its cousin.

The second thing to learn about a new algorithm is how it works. How does the model transform inputs into outputs? Here, you want to describe the transformation made by the model. A trick I like to use is to imagine myself teaching the model to a 5 years old. Forget the fancy words and the fancy maths equation, you just want to explain the process in the simplest terms.

The last thing to understand about a model is how it is being trained/optimized? Does it require supervised or unsupervised learning? How can we reduce the error? How can we improve its accuracy and speed? Is there a tradeoff between the bias, variance and speed? If so, what parameter can we tweak to change their values? Having a good understanding of the algorithm can provide us with a good sense of its strength and its limitation.

We really want to understand the maths behind the algorithm before jumping straight into the code. Otherwise, we only end up copying what the tutorial does without learning anything. Alternatively, we don't want to learn all algorithms in one go before jumping into the code. That's something I had to learn the hard way. I forgot everything that I had seen and I had to relearn everything. Now, I found a better technique: learn one algorithm at a time and then make a quick project about it. When implementing the model, try to remember the steps taken to reach the end goal. If you are stuck and don't know how to write something, google it. But DO NOT FOLLOW A TUTORIAL. At least, not right away. You really want to get stuck and search how to do stuff by yourself. It really helps for memory retention.

Finally, I really want to emphasize that you don't need to learn all algorithm that exist, but it does help to understand the scope of your possibilities. Know what real life application could interest you and spend the most of time on the algorithms preminent in that field. For example, if you are into the application of AI in game development, maybe you should spend more time on reinforcement learning and neural network and less time on analytical stuffs. But again, I might be wrong...  

## SUPERVISED LEARNING / UNSUPERVISED LEARNING

For regression:
- linear regression

For classification:
- logistic regression
- naives bayes classification
- LDA

For Clustering:
- Centroid Clustering: K-means
- Hierarchical clustering: Heatmap and dendogram
- Density clustering:
- Probability clustering:

For dimension reduction:
- PCA
- t-sne
- mds and pcoas
- svm

### REGULARIZATION
- Ridge regression
- LASSO
- Elastic Net

### ENSEMBLE

#### BAGGING 
- decision trees and random forest

#### BOOSTING
- gradient descent
- adaboost

#### STACKING


## NEURAL NETWORK

Deep Learning Crash Course by ACMSIGGRAPH: https://www.youtube.com/watch?v=r0Ogt-q956I
Deep learning overview by Brandon Rohrer on freeCodeCamp: https://www.youtube.com/watch?v=dPWYUELwIdM
Introduction to Deep learning by MIT: http://introtodeeplearning.com/ 

- Deep learning
- Convolutional neural network
- Reccurent neural network
- Autoencoders
- Generative adversial network

Introduction to Neural Network Series by Giant Neural Network: https://www.youtube.com/watch?v=ZzWaow1Rvho&list=PLxt59R_fWVzT9bDxA76AHm3ig0Gg9S3So

Creating neural networks with TensorFlow Tutorial by TechWithTim: https://www.youtube.com/watch?v=tPYj3fFJGjk&t=14815s

## REINFORCEMENT LEARNING

Video Series on Reinforcement Learning by David Silver from DeepMind (Theoric): https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ

Reinforcement Learning with PyTorch by Nachine Learning with Phil on freeCodeCamp: https://www.youtube.com/watch?v=ELE2_Mftqoc

Deep Q Learning Network and GAN with Keras by LiveSessions: https://www.youtube.com/watch?v=OYhFoMySoVs&t=3071s

## EVOLUTIONARY COMPUTATION

- Genetic algorithm explained by The Coding Train: https://www.youtube.com/watch?v=RxTfc4JLYKs&list=PLRqwX-V7Uu6bJM3VgzjNV5YxVxUwzALHV&index=2

Creating genetic algorithm with js by The Coding Train: https://www.youtube.com/watch?v=-jv3CgDN9sc&list=PLRqwX-V7Uu6bJM3VgzjNV5YxVxUwzALHV&index=4

# Part 3: APPLICATION

## DATA ANALYSIS

Data analysis overview by freeCodeCamp: https://www.youtube.com/watch?v=ua-CiDNNj30

Good Machine Learning Practices by Google: https://developers.google.com/machine-learning/guides
Data Analysis Steps by Google: https://developers.google.com/machine-learning/crash-course
Data analysis life cycle by Decisive Data: https://www.youtube.com/watch?v=eYVl2ckF-nQ&t=180s
Descriptive analytics by UC Business: http://uc-r.github.io/descriptive
Predictive anlytics by UC Business: http://uc-r.github.io/predictive
Prescriptive analytics:

## TIME-SERIES

## BUSINESS INTELLIGENCE

## SENTIMENT ANALYSIS

## COMPUTER VISION

## QUANTITATIVE FINANCE

## NATURAL LANGUAGE PROCESSING

## GAME THEORY

## FANTASY SPORT AND ONLINE BETTING

## SURVIVAL ANYSIS

# Online Ressources

Youtube Channels:

- StatQuest with Josh Starmer
- Roger Peng
- TechWithTim
- Keith Galli
- Quantopian
- Decisive Data
- Luis Serano
- Primer
- Allan Kei
- Simcha Pollack
- Quantopian

# HANDBOOK

Theorical Modelling:
- Data Mining, inference and Prediction by Trevor Hastie: https://web.stanford.edu/~hastie/Papers/ESLII.pdf
- Deep Learning Textbook by Yoshua Bengio: http://www.deeplearningbook.org/
- Bayesian Reasonning and Machine Learning by David Barber: http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/270212.pdf

Inferencial Statistics
- Introduction to the Science of Statistics by Joseph Watkins: https://www.math.arizona.edu/~jwatkins/statbook.pdf

Handle large data theoritically:
- Data Mining and Map Reduce from Stanford: http://infolab.stanford.edu/~ullman/mmds/book.pdf

Algorithms:
- Algorithms by Jeff Erickson:http://jeffe.cs.illinois.edu/teaching/algorithms/book/Algorithms-JeffE.pdf

