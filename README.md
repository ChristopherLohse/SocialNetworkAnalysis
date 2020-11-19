# Tobi's Twitter Network

This is a project about Tobi's Twitter Network. The question we asked ourselves is: "Which people (accounts) are influencing Tobis Feed the most?". To answer this question we are using methods of the Social Network Analysis. Our first approach is to collect all friends (people which Tobi is following) and check which of his friends has overlapping friends. The second approach is to just create a network with all friends and friends of friends (2nd-grade friends) from Tobi and calculate the centrality betweenness of each node.

## Installation steps

### Prerequisites

- python >= 3.7
- pip3 - The Python Package Installer 3

### Easy Setup

Type in the terminal in the repository folder:

``` bash
pip install requirements.txt
jupyter lab
```

After that the jupyter lab interface should start and you can open twitterSNA.ipynb to view the notebook

### View the notebook as html 

Just open the twitterSNA.html file in your browser.

### What if the visualisation doesn't show correctly

Open visualisation.html. It is also necessary to zoom in the visualisation in order to see all details correctly.


