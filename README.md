# NoSQL_Project
La mise en place d’une application web de type single page application, pour le traitement des données
depuis une base de données NoSql.
la base de données cible pour ce projet est MangoDB, il s’agit d’une base de données NoSQL orientée
documents, cette base de données doit être alimentée par un outil de Scraping qui va collecter les
données depuis les sites web en arabe sur des thématiques bien précises . 
Les données récupérées depuis le processus du Scraping doivent être enregistrées dans la BDD
MongoDB, puis un traitement du data preprocessing sur ces données pour améliorer la qualité de
données . 
Essayer d’intégrer Mongodb dans le moteur elasticsearch et Kibana pour faire de l ‘analyse de données
sur les données collectées.
Implémenter le pipeline NLP contenant « tokenization, stemming, limitezation, stopwords, pos-tag, bag
of words, tf-idf, et word to vector ».
Entrainer un model base sur les algorithmes du machine learning pour la détection des fakes news selon
les données collectées.
cette pipeline et le model de détection de fake news doit être par la suite consommer a travers des
servies par l’application front end.
 Outils : Flask, GraphQl, TypeScript, Angular 8 / React, MangoDB, Pandas, Beautifulsoup/scrapy, elastic
search et kibana, spacy/nltk.
