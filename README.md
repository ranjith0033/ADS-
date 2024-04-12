1.(i) **Named Entity Recognition:**

Named Entity Recognition (NER) is a crucial natural language processing (NLP) technique aimed at identifying and categorizing named entities within text,
assigning them to specific categories such as people's names, locations, organizations, dates, quantities, monetary values, percentages, etc.
Its primary goal is to extract structured information from unstructured text, essential for various NLP applications like document summarization, information retrieval, and dialogue systems.
The typical process involves tokenizing the input text into words or phrases and then categorizing each token into predefined entity categories.
NER employs a range of techniques including deep learning models like Bidirectional LSTMs, statistical models like Conditional Random Fields (CRF), and rule-based approaches.

1(ii). **Python Script for Named Entity Recognition:**
This Python script executes Named Entity Recognition (NER) on a provided text document. 
The script utilizes the spaCy library for NER, extracting recognized named entities along 
with their respective labels and writing them to an output file. 
Prior to running the script, ensure that spaCy is installed (via pip install spacy) and 
the English language model "en_core_web_sm" is downloaded (using python -m spacy download en_core_web_sm). 
To utilize the script, specify the input and output file paths within the code. 
The input text document should contain 200-300 words.

2. **Analysis of Zachary's Karate Club Network using NetworkX:**
 
This Python script analyzes Zachary's karate club network, accessible via the "karate.gml" file using NetworkX, a graph analysis library. It undertakes the following tasks:

   i. Creates a graph from the "karate.gml" file and provides basic network information.
   
   ii. Stores metadata pertaining to actors within the network.
   
   iii. Calculates various centrality measures (degree, betweenness, closeness, eigenvector, and pagerank centrality) and offers analysis based on these values.
   
   iv. Identifies potential k-components of the network and computes the clustering coefficient.
   
   v. Detects communities within the network using the Girvan-Newman algorithm and Louvain method.

Before executing the script, ensure that NetworkX is installed (via pip install networkx) and 
download the "karate.gml" file from the repository, updating the file path accordingly.
