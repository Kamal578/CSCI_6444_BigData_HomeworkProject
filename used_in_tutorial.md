Based on the **Graph Analytics tutorial** provided in the PDF and R script, the following `igraph` functions have already been utilized. To meet your assignment requirements, you should avoid using these and instead explore other functions from the `igraph` documentation (such as `articulation_points()`, `page_rank()`, `cluster_walktrap()`, etc.).

### **`igraph` Functions Used in the Tutorial**

#### **1. Network Creation and Information**

* 
**`graph()`**: Used to create graphs from a numeric vector or named character vector.


* 
**`graph_from_literal()`**: Used to generate small graphs using a special mathematical-like notation.


* 
**`V()`**: Used to access and manipulate the vertices (nodes) of a graph.


* 
**`E()`**: Used to access and manipulate the edges of a graph.


* 
**`class()`**: Used to check if an object is an "igraph" object.



#### **2. Structural Properties and Descriptives**

* 
**`edge_density()`**: Calculates the density of the graph.


* 
**`reciprocity()`**: Measures the proportion of mutual connections in a directed graph.


* 
**`transitivity()`**: Calculates the clustering coefficient (probability that adjacent nodes are connected).


* 
**`diameter()`**: Finds the longest geodesic distance (shortest path) in the network.


* 
**`degree()`**: Calculates the number of adjacent edges for each node.


* 
**`degree_distribution()`**: Computes the distribution of node degrees.



#### **3. Centrality and Node Importance**

* 
**`closeness()`**: Measures how many steps is required to access every other node from a given node.


* 
**`betweenness()`**: Measures the extent to which a node lies on paths between other nodes.


* 
**`edge_betweenness()`**: Similar to node betweenness, but calculated for edges.


* 
**`hub_score()`** & **`authority_score()`**: Used to identify "hubs" and "authorities" in directed networks.



#### **4. Paths and Distances**

* 
**`mean_distance()`**: Calculates the average path length between all pairs of nodes.


* 
**`distances()`**: Generates a matrix of shortest paths between nodes.


* 
**`all_shortest_paths()`**: Identifies all shortest paths between specific vertices.



#### **5. Communities and Subgroups**

* 
**`cliques()`**: Finds fully connected subgraphs.


* 
**`cluster_edge_betweenness()`**: A community detection algorithm based on edge betweenness.


* 
**`cluster_label_prop()`**: A community detection algorithm based on label propagation.


* 
**`cluster_fast_greedy()`**: A community detection algorithm based on modularity optimization.


* 
**`coreness()`**: Used for K-core decomposition to find the maximal subgraph where every node has degree $k$.



#### **6. Visualization and Layouts**

* 
**`plot()`**: The primary function for visualizing the graph.


* 
**`tkplot()`**: Provides an interactive version of the network plot.


* 
**`layout_randomly()`**, **`layout_in_circle()`**, **`layout_with_fr()`** (Fruchterman-Reingold), and **`layout_with_kk()`** (Kamada-Kawai): Various functions used to position nodes in space.



#### **7. Assortativity**

* 
**`assortativity_nominal()`**: Checks for categorical homophily (similarity).


* 
**`assortativity()`**: Checks for assortativity in ordinal or continuous variables.


* 
**`assortativity_degree()`**: Specifically checks if nodes of similar degrees connect to each other.