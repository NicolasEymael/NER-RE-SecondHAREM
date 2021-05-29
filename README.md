# NER-RE-SecondHAREM

This project was developed as a partial fulfillment of the requirements for the degree of Bachelor in Computer Engineering at UFRGS. The paper is also available in this repository.

The dataset was processed using Jupyter notebooks and the tasks were performed in the Google Colab environment.

### Abstract

Information Extraction is an essential process for automatically building a Knowledge Graph, a type of knowledge base that represents knowledge through semantic connections and has been gaining focus in recent years. Two tasks required during this construction are Named Entity Recognition (NER), responsible for identifying and classifying the entities in the text, and Relation Extraction (RE), responsible for identifying and classifying the relations between these entities. These two tasks combined will generate the tuples that form the Knowledge Graph. Although there are already works that deal with these two tasks, many of them are focused on the English language and few on Portuguese. The goal of this work was the development of machine learning models capable of extracting entities and relations from texts in Portuguese. The first model was used to extract entities through the Simple Transformers library, while the second model was used to determine the relations between entities through the Kindred library. Both models were trained and evaluated using a simplified version of the Second HAREM Golden Collection dataset, a golden standard for NLP in Portuguese. After evaluating the models, it was observed that the results obtained in the NER task were good for the main classes present in the dataset, however, the results of the RE task did not meet expectations and the metrics were lower compared to the related works. Finally, it would be interesting to develop new models for the RE task using the spaCy or Transformers libraries, alternatives that are more complex than Kindred, but more effective.

### Useful links

https://www.linguateca.pt/

https://simpletransformers.ai/

https://kindred.readthedocs.io/en/stable/
