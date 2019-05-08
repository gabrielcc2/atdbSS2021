# atdbSS2019
Range search with neural networks

This project includes a small programming homework for the course Advanced Topic in Databases.

The task consists of employing a neural network for performing range searches on a dataset.

**Task overview:**
Whether the goal is to optimize a data system to support machine learning tasks, or to employ machine learning models in developing efficient data components, there is a rich mix of research  at the intersection of machine learning and data management. From query optimizers based on deep reinforcement learning, to querying databases with natural language, there are many creative ways to extend how databases are built, by using machine learning. In this task we consider a small example of this, by experimenting one simple approach to support range queries with machine learning models.

In detail, your task will be as follows:

1. *Data preparation:* To get acquainted with the dataset (the TPC-H lineitem table at scale factor 1), you will carry out a small data preparation task.

2. *Model fitting:* Here you will fit 2 models: A scikit-learn linear regression model, and a neural network. 

3. *Inference:* Here you will understand the predictions of your models, comparing them to a provided pre-trained network.

4. *Competitive inference for neural networks:* Here you will load a provided pre-trained network into a C++ program, such that inference be done using SIMD instructions, this relies in PocketTensor. Based on this competitive inference process, you will evaluate how the neural network performs for range search compared to one traditional B tree implementation.

Overall you will learn about one possible application of the Software 2.0. idea, by using neural networks to support range searches. You will assess experimentally the pros and cons of a naive approach. Hopefully the task will motivate you to bring this innovative perspective into more everyday tasks.

*You will use:* Python, Scikit-Learn, Keras, PocketTensor (https://github.com/GValiente/pocket-tensor).
*With tooling:* Anaconda, Jupyter Notebooks.

If the task turns out to be interesting for you & your performance demonstrates such interest, you will be invited to collaborate with us in using AutoKeras (https://autokeras.com/start/) for the architecture search task.

Material will be added soon.

Contact: campero@ovgu.de.
