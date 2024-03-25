# supply_chain_analysis

## Acknowledgments

This project uses the dataset provided by Computational Intelligence and Operations Lab - CIOL which is licensed under the GNU Lesser General Public License v2.1. I am thankful to the maintainers of SupplyGraph repo for their contributions to the community.

## License

My project is distributed under MIT License. Additionally, the dataset used is under the GNU LGPL 2.1 license. A copy of the LGPL 2.1 license can be found in the LICENSE file in the root of this repository.

## Modifications to Dataset

None

## About the Notebook

The "Supply Chain Analysis.ipynb" Jupyter Notebook offers an in-depth exploration of a supply chain network through graph theory applications and machine learning models. Initially, it lays the groundwork by constructing a network graph, systematically inputting data, and defining nodes and edges that encapsulate the supply chain components and their interrelations. It delves into graph analysis, employing centrality measures to pinpoint influential nodes, community detection to discern clusters, and path analysis to optimize routes within the network. The incorporation of machine learning is evident in the use of Node2Vec to generate node embeddings, capturing the intricate structure of the network in a form amenable to algorithmic learning. A Random Forest classifier is subsequently trained on these embeddings, classifying nodes with an assessment of model performance provided through accuracy metrics and a comprehensive classification report. Anomaly detection is also featured to identify aberrations, indicative of potential disruptions or significant shifts within the supply chain. Predictive modeling is another key aspect, leveraging the embeddings to hypothesize future network connections, offering valuable foresight into possible supply chain evolutions. The notebook is interspersed with a variety of visualizations, enhancing the understanding of the network’s architecture and attributes. The analysis culminates in a conclusive summary, which reflects on the insights gained, the implications for supply chain management, and proposes avenues for future inquiry or enhancement of operational processes. This notebook is not only a detailed study of supply chain optimization but also serves as a methodological guide for analogous analyses across diverse networks.

