# Challenge : French Web Domain Classification

This project was part of a Kaggle Challenge : https://www.kaggle.com/c/fr-domain-classification

Rules were as follows :
- In this challenge, you are given a subgraph of the French web graph where nodes correspond to domains (~28K domains).
A directed edge between two nodes indicates that there is a hyperlink from at least one page of the source domain to at least one page of the target domain. 
Furthermore, your are provided with the text extracted from all the pages of each domain.
A subset of these domains were manually classified into 8 categories and split between a training set and a test set.
Your task is to predict the categories to which the domains of the test set belong.

**Data :** 
- edgelist.txt - edgelist for the domain graph. It has 28,002 vertices and 319,498 weighted, directed edges. Nodes correspond to domain ids and there is an edge between two nodes if there is a hyperlink from at least one page of the source domain to at least one page of the target domain.
- text - a directory that contains one .txt file per domain. Each file contains the text of all the webpages of the corresponding domain.
- train.csv - 2,125 labeled domain ids. One domain id and label per row.
- test.csv - 560 domain ids of which the category must be predicted. One domain id per row.

We ended up 7/45 (104 contestants) during this challenge.

In the "Team GCM French_web_domain_classification.pdf" we explained our different approaches of the problem.

**Contributors** : Cochet Camille, Gajendran Mithuran, Mallet Hugo
