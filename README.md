# Second_sentiment_analysis
The objective of this project is to know how to do word embedding in NLP sentiment analysis tasks.

Description below (In French):
Dans le brief précédent, nous avons vu comment faire pour encoder des mots sous forme de chaines de caractères en nombres entiers et comment faire pour encoder une suite de mots en vecteurs One-Hot. Le but de ce brief est de comprendre comment faire pour encoder des mots numérisés sous forme de nombres entiers en vecteurs ayant pour coordonnées des nombres flottants : oui, cette phrase est compliquée ! Pour mieux la comprendre, je vous propose d'effectuer une présentation type Powerpoint (entre 5 et 10 diapositives) sur les mots-clés suivants :

Word2Vec
GloVe
Word Embedding
​

Ces approches permettent de transformer des mots encodés sous formes de nombres entiers en vecteurs, ces vecteurs ayant des propriétés redoutables !

Le travail à effectuer ensuite est d'ajouter en entrée d'un perceptron multicouche, en utilisant TensorFlow/Keras, une couche de Word Embedding qui va donc transformer les mots sous forme de nombres entiers de la BDD IMDb en vecteurs. Il faut ensuite entrainer le réseau de neurones dans son ensemble à effectuer l'analyse de sentiment sur la BDD IMDb.

​

Activité facultative : pour les plus chevronné.e.s d'entre vous, essayer d'intégrer les couches de Word Embedding pré-entrainées (= Transfer Learning) de Word2Vec, GloVe ou autres et effectuer le Fine-Tuning sur la BDD IMDb. Conclure.