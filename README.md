# Graph Neural Networks for Social Media Analysis


David E. Nieves-Acaron


dnievesacaro2018@my.fit.edu


Spring 2023


Link to Project: https://dna-courseprojects.github.io/DNA-CourseProjects/


## 1. Description: 

The problem of recommendation systems and social media network analysis is one
that many advertisers would gladly invest much time and effort into in order to
gain an edge on the competition. In the field of neural networks, architectures
such as MLPs could be used with reasonable effectiveness to preform predictions
on graphs. However, a new approach involving Graph Neural Networks could yield
better results for this specific task, as well as for many different tasks in
the future.

For this project, the data that will be used will be primarily graph-based,
meaning that it will have a matrix representation in the form of adjacency
matrices or adjacency lists. Social media graphs and in general, graphs
obtained from reputable sources internet are plentiful (particularly in [Stanford's Large
Network Dataset Collection](https://snap.stanford.edu/data/#socnets)) and as a
result, they could be used from such sources or collected perhaps using some web-scraping
technologies such as Python's BeautifulSoup library. The number of features
from the data will depend partially on the relevance of such features. Perhaps
an ablation study of sorts could be performed to determine which features are
useful, or perhaps some other study would be appropriate.

In summary, the main setup that is being considered is having the input to the
graph be a set of nodes with multiple features, and the outputs a collection of
probabilities that a connection between two nodes (in this case, users) is
present. This will then be verified against the actual graph, from which the
input graph will presumably be derived.

## 2. Expected Scope: 

What I am planning to perform for this project is to analyze the provided data
and show the effects of using a graph neural network on social networks for
different kinds of predictions. Of particular interest is edge-level
prediction, which could easily be applied for use in friend suggestions and
recommendation systems.

The timeline for this project will involve Spring Break, by which I will have
selected and/or collected my primary data source, then the end of March, by
which I will have experimented with different Graph Neural Network
architectures, and decided on some models which have performed well. 

I anticipate the task of training to be of difficulty due to dimensionality of
the data. In addition, due to many Graph Neural Network being shallow as a
result of what was previously mentioned, I will have to look at ways of
increasing performance. To avoid such difficulties, I plan on procuring extra
resources for the purpose of future ML use cases, such as a Google Collab
subscription. In addition, one other difficulty might be storing the data and
querying it, which could involve the use of a graph database.

## 3. Expected Outcomes: 

The measure of success of the ICP effort will be determined mainly by the
success of a graph neural network at predicting the characteristics of the graph.

Another aspect of this involves the the breadth of the techniques used to make
predictions about the graph. Some examples of this involve the representation
of the graph, the loss function, and the network architectures. Regarding that
last topic, there are three approaches to Graph Neural Networks that are
specific to Graph Neural Networks: recurrent GNN's Spatial Convolutional GNN's
Spectral Convolutional GNN's. At the very least, the success of the project
will involve exploring at least one of these in depth and implementing it.

## 4. Initial Key References: 

Graph Neural Networks for Social Recommendation
https://arxiv.org/abs/1902.07243

Graph Convolutional Neural Networks for Text Classification
https://arxiv.org/abs/1809.05679

Geometric Deep Learning by Michael Bronstein

A Practical Tutorial on Graph Neural Networks
https://arxiv.org/pdf/2010.05234.pdf

The graph neural network model
EEE Transactions on Neural Networks, 2009

