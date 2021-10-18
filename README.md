# Lego Graph
A graph modelling lego sets, parts, and inventories.

## Prerequsities

* [pyTigerGraph](https://pypi.org/project/pyTigerGraph/)
* [Kaggle](https://pypi.org/project/kaggle/) (if installing from the API)

## Quick Set Up

1. [Get Started with TigerGraph Cloud](https://developers.tigergraph.com/quickstart)
2. Create an account on [Kaggle](https://kaggle.com/) (if directly importing data from kaggle).
3. Run `LegoGraph.ipynb`, replacing it with the appropriate credentials.

## Breakdown

### Data
The data is from the [Kaggle Lego Database](https://www.kaggle.com/rtatman/lego-database).

### EDA
None.

### Scripts

#### Schema

![Lego Schema](https://miro.medium.com/max/4800/1*bEKFLtk3iZ_n39vxrb7U_w.png)

#### Loads
See `LegoGraph.ipynb`.

#### Query
There are a few queries to grab data for analysis, including:

1. `legoInformation.gsql` —> Grabs information from the graph, including year, number of parts, theme id, and theme name. 
2. `quantityParts.gsql` —> Grabs the quantity of sets and the number of parts in each set.
3. `yearParts.gsql` —> Grabs the year a set is released and the number of parts in the set. 

## Projects

`TigerGraph_and_Plotly.ipynb` —> Lab of creating cool visualizations with Plotly and the TigerGraph Lego Graph.

## External Links

* [Enhancing your Kaggle Computations with TigerGraph (Part I): Creating a Lego Graph](https://medium.com/codex/accelerating-your-kaggle-computations-with-tigergraph-part-i-creating-a-lego-graph-f2a43029f78f?sk=d632a28c13880922aed768128bab9efb)

* [Enhancing your Kaggle Computations with TigerGraph (Part II): Creating Visualisations with Plotly Express](https://medium.com/geekculture/enhancing-your-kaggle-computations-with-tigergraph-part-ii-creating-visualisations-with-plotly-1197d7707dac?sk=90c813798389910d49064ba709c664cc)

* [Using Plotly to Visualize your TigerGraph Data](https://www.youtube.com/watch?v=n82PhhWQ0uY)

