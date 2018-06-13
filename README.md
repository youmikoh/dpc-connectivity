# 🏆 Dota 2 Pro Circuit Connectivity
Visualizing player connectivity in the 2018 Dota 2 pro circuit

![graph.gif](img/graph.gif)

## Data

### Part I - [Collection](http://nbviewer.jupyter.org/github/youmikoh/dpc-connectivity/blob/master/part1_collect.ipynb)
- *Data*: History of teams for each player within the 2018 Dota 2 pro circuit
- *Source*: [Liquipedia](https://liquipedia.net/dota2/Main_Page)
- *Method*: [MediaWiki API](https://liquipedia.net/commons/Liquipedia:API_Usage_Guidelines) for Liquipedia ( [usage compliance](http://nbviewer.jupyter.org/github/youmikoh/dpc-connectivity/blob/master/part1_collect.ipynb#Liquipedia-API-usage-compliance) is strongly recommended 👍)

### Part II - [Stratification](http://nbviewer.jupyter.org/github/youmikoh/dpc-connectivity/blob/master/part2_stratify.ipynb)
- *Hierarchy*: player ↦ Flag ↦ Region
- *Connections*: ab ∈ connections ⟺ a.History ∪ b.History > 0
- *Graph*: G = {V, E} : dpc ↦ V, connections ↦ E

## Visualization

### [Interactive](https://beta.observablehq.com/@youmikoh/dota-2-pro-circuit-connectivity)
Powered by [ObservableHQ](https://beta.observablehq.com/)

### [Graph](https://youmikoh.github.io/dpc-connectivity/)
Powered by [Github Pages](https://pages.github.com/)
