# Wikipedia-hyperlinks-graph
##### 

Introduction
======

The goal of this project consists in perform an analysis of the Wikipedia Hyperlink graph. In particular, given extra information about the categories to which an article belongs to we rank the articles according to some criteria.

For this purpose we use the Wikipedia graph released by the SNAP group.

<div style="text-align:center"><img src ="https://cryptobriefing.com/wp-content/uploads/2018/04/Wikipedia-and-Request-Network-enable-donors-to-donate-in-cryptocurrency.jpg" /></div>

Download sets of data
======

[Wikicat hyperlink graph](https://drive.google.com/file/d/1ghPJ4g6XMCUDFQ2JPqAVveLyytG8gBfL/view?usp=sharing).  It is a reduced version of the one you find on SNAP. Every row is an edge, the two elements are the nodes (source and destination).

From [this](https://snap.stanford.edu/data/wiki-topcats.html) page download:

-  `wiki-topcats-categories.txt.gz`

-  `wiki-topcats-page-names.txt.gz`


Repository files description
======
`Wikipedia-hyperlinks-graph.ipynb`	
Main file with the work explanation to perform the analisys.

`median_distances.pkl`
The output file resulted from ranking score with median distances

