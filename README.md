# P2.13_seed 

# Deep Learning

This is the first part of the Deep Learning Course for the Master in High-Performance Computing (SISSA/ICTP):
**Introduction to Neural Networks**.

You can find [here](https://github.com/denocris/MHPC-Natural-Language-Processing-Lectures-2020) the second part of the course, **Natural Language Processing**, by [Cristiano De Nobili](https://denocris.com/).


### Main Topics

**First Part**

- Artificial neural networks
- Train, validate and test a deep learning model
- Convolutional neural networks
- Brief remarks on unsupervised models

**Second Part**

- Natural Language Processing
- Transformers and contextual word embeddings
- PyTorch, SpaCy and Hugging Face libraries

# Teachers

- Alessio Ansuini (Research and Technology Institute, AREA Science Park)
- Cristiano De Nobili (HARMAN International, a Samsung Company)

Follow-up course P2.14: [Deep generative models with TensorFlow 2](https://gitlab.developers.cam.ac.uk/pc620/dl_course)

- Piero Coronica (RSE @ Research Computing Services - University of Cambridge)

# Detailed Syllabus of the First Part

**Day 1**

- The artificial neuron, activation functions, capacity of a single neuron
- The limits of a single neuron, transformations of the input: the concept of 
representation
- Fully connected architectures, exact count and scaling of the number of parameters
- Universal approximation theorem (sketched)
- Softmax, probabilistic interpretation of the output, discriminative models
- Cross-entropy loss, probabilistic interpretation as maximum-likelihood inference,
information-theoretical interpretation as KL distance between the probability of 
the data and the model
- Optimization and learning rules for gradient descent and its stochastic counterparts 
- Regularization L2, L1 and their influence on training dynamics


Sources (see below): Hugo Larochelle's Neural networks class, Michael Nielsen's free book


**Day 2** 

- Representations as a scientific object of investigation
- More on regularization: dropout
- Convolutional networks: convolutional layers, pooling layers
- Transfer learning

Sources: Michael Nielsen's free book, [image kernels](https://setosa.io/ev/image-kernels/), [PyTorch Tutorials](https://pytorch.org/tutorials/), [Intrinsic dimension](https://www.nature.com/articles/s41598-017-11873-y), [SVCCA](https://arxiv.org/abs/1706.05806), [PWCCA](https://arxiv.org/abs/1806.05759), [CKA](https://arxiv.org/abs/1905.00414),
[T-SNE](https://distill.pub/2016/misread-tsne/)

**Day 3**

- Basics of autoencoders, linear autoencoders: relationship with PCA (see [here](https://www.youtube.com/watch?v=xq-I0Rl8mt0) for a proof)
- Description of the exam: [Deconstructing the Lottery Ticket Hypothesis](https://eng.uber.com/deconstructing-lottery-tickets/)
  More resources are embedded in the notebook for the exam!


# Exam

The exam will consist in an exploration of a recent finding on network pruning
called "The Lottery Ticket Hypothesis"

# Videos

In order to see a video I suggest to download it (otherwise only shortened previews are available)

- Day 1 (08/06/2020) Exercises 

  https://www.dropbox.com/s/8xcdd4be31xc0t5/P2.13_seed_Day1_Exercises.mp4?dl=0
  
- Day 2 (09/06/2020) Exercises
   
  https://www.dropbox.com/s/axj8z8rdm6rbrc4/P2.13_seed_Day2_Exercises.mp4?dl=0
  

# Resources

There are excellent free resources to deepen your knowledge
on topics such as Deep Learning, Reinforcement Learning and more
in general Artificial Intelligence.

Here is a selection of very good ones.


*******************************************************************
Books for free
*******************************************************************

- Michael Nielsen

  http://neuralnetworksanddeeplearning.com/


- The Deep Learning Book

  https://www.deeplearningbook.org/

  in a single pdf version

  https://github.com/janishar/mit-deep-learning-book-pdf
  
- Information Theory, Pattern Recognition, and Neural Networks (Dave McKay)

  http://www.inference.org.uk/mackay/itprnn/book.html



*******************************************************************
Courses for free
*******************************************************************

- Fast AI (Jeremy Howards)
  
  Invaluable resource for quickly getting your hands dirt into practical Deep Learning
  
  https://www.fast.ai/

- Deep learning specialization (auditing is for free)
  on Coursera (Andrew Ng).
  
  One of the best resources to learn basic and intermediate concepts.
  
  (Check the Coursera website for other resources: auditing
  is sometimes for free, certificates are generally not.)

- Deep unsupervised learning (Pieter Abbeel)

  A glimpse into state-of-the-art research problems.

  https://sites.google.com/view/berkeley-cs294-158-sp20/home

- Deep reinforcement learning (Dave Silver)

  The legendary course of Dave Silver on YouTube

  https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-

- Neural network class (Hugo Larochelle)

  After almost 10 years still a very useful resource: crystal clear explanations
  of an impressive amount of topics, starting from the very basics (I used this
  a lot!)

  https://www.youtube.com/watch?v=SGZ6BttHMPw&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH
  
  
- Information Theory, Pattern Recognition, and Neural Networks (Dave McKay)
  (See also the accompanying book)

  The Lectures of Dave MacKay will accompany you to the study of its beautiful book:
  on of the most precious resources you will find on this topic.
  
  Information theory is very relevant in many fields, and particularly in Unsupervised Deep Learning.
  
  https://www.youtube.com/watch?v=BCiZc0n6COY&list=PLruBu5BI5n4aFpG32iMbdWoRVAA-Vcso6


*******************************************************************
Websites and Blogs
*******************************************************************

- Deepmind

  https://deepmind.com
  https://deepmind.com/blog


- OpenAI

  https://openai.com/


*******************************************************************
YouTube channels
*******************************************************************

- Yannick Kilcher's channel

  https://www.youtube.com/channel/UCZHmQk67mSJgfCCTn7xBfew


- Two minutes papers

  https://www.youtube.com/user/keeroyz
