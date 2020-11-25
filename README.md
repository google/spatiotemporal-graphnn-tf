## spatiotemporal-graph-nn-tf

This colab shows the steps to implement a spatio-temporal graph neural network model(st-gnn) which learns from rich and multidimensional spatiotemporal signals. 

* Specifically, the model architecture is composed by an encoder, a message-passing and an output module to make node level predictions. Each module is defined in the colab and a GraphSTNet model leverages the three modules to have the ability to learn from spatio-temporal signals.
* The colab also has a section “Graph Datasets” that demonstrates the steps to build a batched graph spatio-temporal dataset that can be consumed by the st-gnn model from a random dataset. The user can replace the input random dataset with specific dataset in their problem domain, by following the definition.
* An example of postprocessing of the evaluation results is also provided to show model
inference and metrics computations. The user can add more functionalities  based on the example.

This is not an officially supported Google product.
