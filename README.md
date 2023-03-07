# Neo4J-Graph-Analytics
In this project, graph data was used to implement a kind of recommendation system.<br>
All the detailed information about the project are inside the report (in italian) _orlandi_attivita_neo4j.pdf_

### Data
The graph used are avaiable [here](https://neo4j.com/graphgists/the-cantina-bar/) and the data used to fill this graph structure are avaiable [here](https://www.kaggle.com/datasets/ai-first/cocktail-ingredients).<br>
The graph shown in the following image represents cocktail data, how they are composed by different ingredients, people who like a certain cocktail and where these people come from.<br>
<p align="center">
<img src="https://github.com/pietroorlandi/Neo4J-Graph-Analytics/blob/main/images/graph_schema.png" alt="Example image" width="550" height="250">
</p>

### Query
In this project have been developed 11 queries. <br>
_Query 10_ used a content-based filtering to recommend a cocktail to a person based on the person's favorite ingredients.<br>
_Query 11_ used a collaborative-based filtering to reccomend a cocktail to a person based on the tastes of other people similar.<br>

### Graph algorithms
It has been used graph algorithms on the graph to figure out which cocktails were the most liked.
