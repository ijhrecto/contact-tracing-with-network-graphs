# contact-tracing-with-network-graphs
a study that uses graph theory to create a network for contact tracing in Covid context.

Our data is a small simulated data compromising of vulnerability factors based from the World Health Organization, and the social network factors of each sample subject. 

The values from the data was converted into numerical data with values based on the severity or influence of each category, with higher score set as a higher influence. 

We analyzed the data using the centralities, namely degree, eigenvector, and betweenness centralities. Eigenvector centralities was used for vulnerability, while betweenness was used for spreading influence of the person under testing. 

Network graphs was used to visualize the social networks and their vulnerability through the edge weights of the node connections. 

Our method created an automated queue for testing prioritization using the acquired vulnerability and spreader ranking from the centrality analysis. 

This testing priority queue may increase response and help the effort in the containment and monitoring for the infections and significantly minimize the transmission of COVID-19
