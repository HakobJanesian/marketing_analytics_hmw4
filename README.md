# Social Network Analysis Project

## Overview

This project demonstrates a comprehensive analysis of a social network using various network analysis techniques. The primary objective is to understand the structure, influential nodes, and communities within a given network, derived from a dataset of connections. The analysis provides insights into different aspects of the network, which can be utilized for various applications, including marketing strategies, community detection, and understanding network dynamics.

## Data

The project uses a dataset representing a social network, where each record indicates a directed connection between two nodes. The dataset is loaded and processed using the Pandas library in Python.

## Key Features

The project includes several key features, focusing on different aspects of network analysis:

### 1. Graph Creation

- A directed graph is constructed from the dataset using NetworkX, a Python library for network analysis.

### 2. Identification of Bridge Nodes

- Bridge nodes in the network are identified. These nodes act as crucial points of connection between different components of the network, playing a significant role in maintaining the network's connectivity and information flow.

### 3. Graph Density Analysis

- The density of the graph is calculated to understand how sparse the network is, providing insight into the overall connectivity of the network.

### 4. Node Connection Analysis

- Nodes with the highest and lowest number of connections are identified, highlighting the most and least connected nodes in the network.

### 5. Analysis of Incoming and Outgoing Connections

- Nodes with the highest number of incoming and outgoing connections are determined, indicating their influence and engagement levels within the network.

### 6. Centrality Measures

- Nodes with the highest closeness, betweenness, and eigenvector centrality are identified. These measures provide insights into the most influential and central nodes in the network.

### 7. Community Detection

- The Infomap algorithm is used to detect communities within the network. This step identifies groups of nodes that are more densely connected to each other than to the rest of the network.

### 8. Community Size Analysis

- The largest and smallest communities are identified, providing insight into the dominant and niche groups within the network.

### 9. Community Visualization and Key Node Analysis

- Visualizations are created for the largest three communities, both with and without key nodes identified by various centrality measures. This step helps in understanding the structure and key players in different segments of the network.

### 10. Influencer Identification and Visualization

- Top influencers within the largest three communities are identified and visualized, focusing on nodes with significant impact based on various centrality measures.

### 11. Action Plan for Marketing Strategy

- A hypothetical action plan is designed for a marketing agency, utilizing the insights gained from the network analysis. This plan includes strategies for targeting influential nodes and communities with a specified marketing budget and advertisement cost.

## Tools and Libraries Used

- **Pandas**: For data loading and manipulation.
- **NetworkX**: For creating and analyzing the network graph.
- **Matplotlib**: For visualizing the network and its communities.
- **Infomap**: For community detection within the network.

## Applications

The insights derived from this project can be applied in various domains, such as:

- Developing targeted marketing strategies.
- Understanding the flow of information in social networks.
- Identifying key influencers and decision-makers.
- Studying the dynamics of social interactions and community formations.

## How to Use

To run this project:

1. Ensure you have Python installed along with Pandas, NetworkX, Matplotlib, and Infomap libraries.
2. Load your dataset in a similar format as described.
3. Execute the provided Python scripts (in the ipynb file) to perform the analysis.
