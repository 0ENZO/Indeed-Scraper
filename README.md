# Indeed-Scraper

Ce projet a été développé sur un notebook google colaboratory avec streamlit, ngrok, scraperapi, beautifulsoup et pandas. 

Une petite web app streamlit mise en ligne via ngrok, permettant de récupérer scrapper indeed et de récupérer les offres selon 4 critères: 

* Intitulé du poste
* Type de contrat
* Localisation
* Date de publication

Le tout est affiché et téléchargeable au format csv. 

Le projet tient sur un notebook et a été développé exclusivement sur google colaboratory de part sa portabilité. Un environnement qui nous suit où que l'on aille peut importe le support. 


## Installation

* Télécharger le notebook
* Importer dans google colaboratory 
* Créer un compte ngrok et scraperapi afin de récupérer un token d'authentification
* Créer un fichier pwd.txt au format suivant et l'ajouter dans les fichiers du notebook


```
scraperapi:TOKEN
ngrok:TOKEN
```
<br/></br>
<img width="960" alt="App" src="https://user-images.githubusercontent.com/53021621/127635752-ba9df016-7acd-46ed-bd76-7c34cc4d63d3.PNG">

## A faire

Mettre les offres dans une base de données mongoDB
