# Mise en place d'un environnement Cloud pour lancer un script PySpark
Pour une entreprise ayant besoin d'analyser un nombre important d'images
## Table des matières :
1. [Informations générales](#information-générales)
2. [Apache Spark](#apache-spark)
3. [AWS](#aws)
4. [Stockage S3](#stockage-s3)
5. [EMR](#emr)
6. [Notebooks](#notebooks)

## Informations générales
![Big Data](https://github.com/Mikael-DataAnalyst/Pyspark_emr_aws/blob/main/images/big_data.png?raw=true)
Objectif : Mettre en place une architecture Big Data avec EMR, S3, IAM pour déployer un script Pyspark

Les données initiales sont disponible sur [Kaggle](https://www.kaggle.com/datasets/moltean/fruits)

Pour un soucis de rapidité d'éxécution, un sample des données a été réalisé.
Le script va donc se réaliser sur plus de 500 images réparties dans 131 catégories.
Le but est d'extraire les features et faire une réduction de dimension en préparation d'un modèle pour la reconnaissance de fruits.

## Apache Spark
![spark](https://github.com/Mikael-DataAnalyst/Pyspark_emr_aws/blob/main/images/pyspark.png?raw=true)

Apache Spark est un puissant moteur de traitement open-source permettant de traiter des bases de données massives en utilisant le calcul distribué.

PySpark est une interface pour Apache Spark en Python. Alternative à la librairie pandas lorsque l’on cherche à traiter des jeux de données volumineux.


## AWS
![aws](https://github.com/Mikael-DataAnalyst/Pyspark_emr_aws/blob/main/images/aws.jpg?raw=true)
AWS a été choisi pour ce projet car il offre une vaste gamme de services de calcul, de stockage, de machine Learning.
Il est un des plus grand fournisseur de services cloud actuellement
Ses avantages :
    - La simplicité
    - La flexibilité

## Stockage S3
![s3](https://github.com/Mikael-DataAnalyst/Pyspark_emr_aws/blob/main/images/s3.png?raw=true)


## EMR
![emr](https://github.com/Mikael-DataAnalyst/Pyspark_emr_aws/blob/main/images/emr.png?raw=true)


## Notebooks