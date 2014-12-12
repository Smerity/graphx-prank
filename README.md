[![PRank](http://i.imgur.com/Z100sPh.jpg)](https://www.flickr.com/photos/pasukaru76/4892378102)

# GraphX P[age]Rank

This repository contains a runner for the PageRank implementation found in GraphX.
The aim is to replicate the existing experiments from the [GraphX: Unifying Data-Parallel and Graph-Parallel Analytics](http://arxiv.org/abs/1402.2394) paper and ensure the general setup and experimental methodology are sound before scaling up to far larger graphs -- specifically the [Web Data Commons Hyperlink Graph](http://webdatacommons.org/hyperlinkgraph/) featuring 3.5 billion web pages and 128 billion hyperlinks.

To run:

    sbt package
    ./bin/spark-submit --class GraphXPRank ~/graphx-prank_2.10-0.1.jar [data] [partitions]

# License

MIT License, as per `LICENSE`
