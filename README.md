# Presentations

These are a collections of varoious posters and presentation I have given on this dataset in the last few months.

### Abstract

Graphs are powerful data structures used to solve complex problems like recommender systems, path optimization and influence prediction. 
However, graphs by itself have limited information and mining this information to get additional insights is often hard. 
Graph Neural Nets (GNNs), a class of deep neural net, has become a popular method to process graph data to solve downstream tasks like clustering, classification, edge prediction and influence maximization problems pertaining to above emerging applications. 
GNNs are becoming popular these days due to their unique capabilities like incorporation of node, edge and graph level information into the output prediction.
However, dataset sizes have plagued the development of GNNs due to the proprietary nature of industry data, limited size and non-availability of synthetic datasets.

In this work, we introduce, Illinois Graph Benchmark (IGB), a 600 million node heterogeneous graph dataset with 3 billion edges with over 120 million labelled nodes for node classification task. 
Compared to the current available largest graph dataset, IGB provides over 85 times more labelled data for the model developers to create and evaluate model with more accuracy. 
IGB is developed using the Microsoft Academic Graph (MAG) for the edges and nodes and Semantic Scholar database for the node labels. 
IGB also comprises of synthetic and a real graph datasets where the synthetic dataset has randomly initialized node embeddings and the real graph dataset has a variable dimension node embeddings generated using Sentence-BERT model. 
IGB is compatible with popular GNN frameworks like DGL and PyTorch Geometric and comes with predefined popular models like GCN, GraphSAGE, GAT and HGT for easy model development.
