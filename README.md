# AI Wikipedia Network Analysis

This project analyzes the connections between 10 AI-related Wikipedia articles using network analysis.

## Research Question

Which AI-related Wikipedia articles are the most important within a network of interconnected AI topics?

## Network

Each node represents an AI-related Wikipedia article, and each directed edge represents a hyperlink from one article to another.

The network contains:
- 10 nodes
- 74 unique directed edges

## Analysis

I used PageRank to measure the importance of each article within the network. The analysis found that Large Language Model had the highest PageRank score, followed closely by Deep Learning. Natural Language Processing and Artificial Intelligence were tied for the next-highest score.

## Tools Used

- Python
- Jupyter Notebook
- NetworkX
- pandas
- matplotlib
- requests
- BeautifulSoup

## Files

`AI_Wikipedia_Network_Analysis.ipynb` contains the data collection, network construction, PageRank analysis, validation, and visualizations for this project.
