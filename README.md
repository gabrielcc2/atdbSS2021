# Range search with learned models- atdbSS2019 

This repository includes a small programming homework for the summer semester 2019 offering of the course Advanced Topics in Databases (http://www.dbse.ovgu.de/Lehre/ATDB.html), at the University of Magdeburg.

The task consists of testing some learned models, including a neural network for performing range searches on a dataset.

**Task overview:**

Whether the goal is to optimize a data system to support machine learning tasks, or to employ machine learning models in developing efficient data components, there is a rich mix of research  at the intersection of machine learning and data management. From query optimizers based on deep reinforcement learning, to querying databases with natural language, there are many creative ways to extend how databases are built, by using machine learning. In this task we consider a small example of this, by experimenting a simplified approach to support range queries with machine learning models.

<p align="center">
  <img src="http://dsail.csail.mit.edu/wp-content/uploads/2018/09/LearnedIndex.jpg?raw=true">
  
Though this task is inspired by the idea of *Learned Index Structures*, as depicted in the image from the original paper, this programming task represents a highly simplified evaluation of the idea.

Here is the reference for the original paper: Kraska, Tim, Alex Beutel, Ed H. Chi, Jeffrey Dean, and Neoklis Polyzotis. "The case for learned index structures." In Proceedings of the 2018 International Conference on Management of Data, pp. 489-504. ACM, 2018.

</p>

In detail, your tasks will be as follows:

1. *Data preparation:* To get acquainted with the dataset (the TPC-H lineitem table at scale factor 1), you will carry out a small data preparation task.

2. *Model fitting:* Here you will fit 2 models to be able to do range searches on the selected data. You will compare a scikit-learn linear regression model, and a neural network. 

3. *Inference:* Here you will understand the predictions of your models, comparing them to a provided pre-trained network.

4. *Competitive inference for neural networks:* Here you will load a provided pre-trained network into a C++ program, such that inference be done using SIMD instructions. This relies on PocketTensor. Based on this competitive inference process, you will evaluate how your neural network performs for range search compared to a traditional B tree implementation.

*You will use:* Python, Scikit-Learn, Keras, PocketTensor (https://github.com/GValiente/pocket-tensor).

*With tooling:* Anaconda, Jupyter Notebooks.

**Takeaways:**

Overall you will learn about one possible application of the Software 2.0. idea, by using a learned model to support range searches. You will assess experimentally the pros and cons of this naive approach, and will be able to think on how to improve it. Hopefully this assignment will motivate you to seek novel applications of machine learning in more everyday software tasks.

If this programming assignment turns out to be interesting for you & your performance demonstrates such interest, you will be invited to collaborate with us in using AutoKeras (https://autokeras.com/start/) for the architecture search task, or alternatively on improvements to the inference process.

Material will be added soon.

Contact: campero@ovgu.de.
