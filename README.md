# Reframing-Financial-Markets-as-Complex-Systems Notebook 

## Overview

This notebook provides the code for the case study in the CFA Institute
Research and Policy Center paper on [Reframing Financial Markets as Complex Systems](https://rpc.cfainstitute.org/research/reports/2025/reframing-financial-markets-as-complex-systems), with further details provided in the paper. The Reframing Financial Markets as Complex Systems 
report shows how viewing financial markets as complex, interconnected systems can reveal new ways to 
understand risk, strengthen portfolios, and navigate an increasingly dynamic global economy. 
The case study considers how network analysis can be used to inform asset allocation in a portfolio 
using a spanning tree approach, where data on European 10Y sovereign bond yields are used.  

------------------------------------------------------------------------

## 🧩 Objectives

-   Demonstrate how network theory can be applied to portfolio allocation. 
-   Implement and visualise a **spanning tree network** using European sovereign bond yield data. 
-   Categorise portfolio allocation based on eigenvector centrality in the spanning tree.

------------------------------------------------------------------------

## 🧠 Key Concepts

-   **Graph Representation**: A set of nodes and edges represented by a correlation matrix (nodes are assets
  and edges are represented by correlations between assets).
-   **Spanning Tree**: A subgraph where all nodes are connected, undirected, without any cycles.
-   **Maximum Spanning Tree**: A spanning tree where the total edge weight is maximised.
-   **Eigenvector Centrality**: A measure of influence for one node relative to all other nodes in the network.
  
------------------------------------------------------------------------

## ⚙️ Requirements

Ensure the following Python libraries are installed:

``` bash
pip install eikon pandas sklearn matplotlib seaborn networkx
```

------------------------------------------------------------------------

## 🧑‍💻 Usage

1.  Open the notebook:

    ``` bash
    jupyter notebook "Spanning tree notebook.ipynb"
    ```

2.  Add API key for LSEG data
  
3.  Run cells sequentially.

4.  **Extra:** Experiment with different centrality measures and network construction methods

