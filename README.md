# Modularity on the Karate Club Graph

## Project Overview
This project explores community detection in the Zachary's Karate Club graph using modularity-based optimisation techniques. It compares two approaches — the handout method and Newman's method — to understand how different formulations identify communities within the same network.

## Objectives
- Understand modularity and its role in community detection.
- Implement and compare two modularity-based methods.
- Analyse how successive graph cuts affect community structures.
- Study changes in degree, betweenness, closeness and clustering centrality.
- Compare detected communities with the actual division of the Karate Club using the Adjusted Rand Index (ARI).

## Methodology
1. Load and analyse the Zachary's Karate Club graph.
2. Apply the handout and Newman formulations.
3. Perform successive cuts to identify smaller communities.
4. Calculate modularity and network centrality measures at each stage.
5. Compare the final partitions using ARI.
6. Interpret the results and identify the limitations of both approaches.

## Results and Observations
- The first cut closely reproduces the actual division of the club, achieving an ARI of 0.882.
- The handout method achieves a final modularity of 0.4094, while Newman's method achieves 0.3934.
- The final ARI values are 0.446 for the handout method and 0.435 for Newman's method.
- Centrality measures change as the graph is divided into smaller communities.
- The results demonstrate that higher modularity does not necessarily mean better agreement with the actual communities.

## Network Measures Analysed
- **Degree Centrality:** Measures the number of connections a node has within its community.
- **Betweenness Centrality:** Measures how often a node acts as a bridge along shortest paths.
- **Closeness Centrality:** Measures how close a node is to other nodes in its community.
- **Clustering Coefficient:** Measures how strongly a node's neighbours are connected to each other.

## Key Takeaway
Community detection depends on the mathematical formulation and the structure of the network. Modularity helps identify densely connected groups, but the resulting communities do not always represent the actual social relationships within a network.

## Responsible AI Usage
AI tools were used as supporting resources for understanding complex concepts, simplifying reference material and assisting with advanced coding tasks beyond my current technical skills. The project was approached as a self-learning exercise, with emphasis on understanding the underlying mathematics, methodology and results. The long-term objective is to develop sufficient programming and analytical skills to independently implement similar projects.

## Project Context
**Course:** DSC212 – Graph Theory  
**Topic:** Modularity on the Karate Club Graph  
**Level:** Undergraduate – Second Year
