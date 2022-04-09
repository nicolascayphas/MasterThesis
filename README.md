# MasterThesis
Multi-label classification of social events from textual features

Multi-label classification is a method used to categorize the available data into multiple labels at the same time. This problem occurs generally in multimedia categorization. The main problem is assessing how good the results were since the accuracy only takes into account the whole result instead of assessing each predicted label on its own. This paper introduces the approaches that were implemented using natural language processing on the texts that form the data. These texts are events that were given in an unstructured form, where they needed to be transformed into numbers to be machine-readable. 

The main goal of the thesis is to improve the user experience by categorizing the data into their correct labels and minimizing misclassifications. Not all misclassifications have the same effect on the results, that is the Jaccard Index and the Hamming Loss metrics were used to assess the results. The different experiments with the machine learning models had some fair results when compared with the size of the data. The other goal is to handle incoming data that are not related to any of the available events, by using unsupervised learning with K-Means Algorithm to cluster them into similar labels. And lastly, the final task is to create a recommendation system that relies on previous events that were visited by the user. Two approaches were explained, first one was implemented using the cosine similarity and the second depends if there would be a network of friends in the application, where it recommends events according to what the user's friends visited.
