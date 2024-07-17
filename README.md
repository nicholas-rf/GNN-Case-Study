# GNN Case Study
A case study and design walkthrough of graph neural networks (GNNs) for molecular property prediction. 

# Dataset
The OGB-Molhiv dataset used for this case study is from [Open Graph Benchmark](https://ogb.stanford.edu/docs/graphprop/#ogbg-mol). Meant for graph classification tasks, it contains both node and edge features along with labels that indicate whether or not a molecule can inhibit HIV replication. 

# Case Study Structure
The case study begins with an introduction to the GNN framework, an examination of standard GNN architecture and a general design pipeline. Afterwards the dataset is explained and the design pipeline is followed to create a graph neural network for graph classification. Initially a graph convolutional network is implemented and tested before improvements are suggested. Taking into account improvements, a graph attention network is implemented and compared with the original model. 