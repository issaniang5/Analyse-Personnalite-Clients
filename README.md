# Analyse de la Personnalité Client

- Lien vers le dataset Kaggle: https://www.kaggle.com/imakash3011/customer-personality-analysis
--------------------------------------
## Contexte 📜:
- **Problème** 🚨:
L'analyse de la personnalité client est une analyse détaillée des clients idéaux d'une entreprise. Elle aide les entreprises à mieux comprendre leurs clients, ce qui leur permet de modifier leurs produits en fonction des besoins, comportements et préoccupations spécifiques des différents segments de clientèle.

Elle permet également d'adapter les produits selon les segments ciblés au lieu de promouvoir un produit auprès de tous les clients. Par exemple, une entreprise peut analyser quel segment est le plus susceptible d'acheter un produit et concentrer ses efforts de marketing sur ce segment spécifique.

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Blog_Banner_v1-01-1024x410.jpg' width='600px' ></img>
----------------------------------
## Contenu 📃:
**Attributs**

- ID: Identifiant unique du client.
- Year_Birth: Année de naissance du client.
- Education: Niveau d'éducation du client.
- Marital_Status: Statut matrimonial du client.
- Income: Revenu annuel du ménage du client.
- Kidhome: Nombre d'enfants dans le foyer du client.
- Teenhome: Nombre d'adolescents dans le foyer du client.
- Dt_Customer: Date d'inscription du client à l'entreprise.
- Recency: Nombre de jours depuis le dernier achat du client.
- Complain: 1 si le client a fait une réclamation au cours des 2 dernières années, sinon 0.
Produits
------------------------------------------------------------------
- MntWines : Dépenses en vin des 2 dernières années.
- MntFruits : Dépenses en fruits des 2 dernières années.
- MntMeatProducts : Dépenses en produits carnés des 2 dernières années.
- MntFishProducts : Dépenses en produits de la mer des 2 dernières années.
- MntSweetProducts : Dépenses en sucreries des 2 dernières années.
- MntGoldProds : Dépenses en produits d'or des 2 dernières années.
Promotions
------------------------------------------------------------
- NumDealsPurchases : Nombre d'achats avec réduction.
- AcceptedCmp1 à AcceptedCmp5 : 1 si l'offre de la campagne respective a été acceptée, sinon 0.
- Response : 1 si l'offre de la dernière campagne a été acceptée, sinon 0.
Canaux d'achat
----------------------------------------------------------------------------
- NumWebPurchases : Achats via le site web de l'entreprise.
- NumCatalogPurchases : Achats via un catalogue.
- NumStorePurchases : Achats directs en magasin.
- NumWebVisitsMonth : Visites sur le site web au cours du dernier mois.

-------------------------------------------------------------------------
## Objectif 🎯:
**L'objectif est de réaliser un clustering pour segmenter les clients en différents groupes. Les réponses à ces questions sont essentielles :**

- Quelles sont les opinions des clients ?
- Elles révèlent l'attitude des clients envers le produit.

- Que font réellement les clients ?
- Elles indiquent ce que les clients font, au-delà de ce qu’ils disent.

----------------------------------------------------------------------
## Approche 🪧:
- Importation des données avec Pandas depuis Kaggle. Analyse des colonnes, lignes et valeurs nulles.
- Visualisation des attributs binaires (0 & 1) avec Matplotlib, Seaborn, et Plotly. Remplissage des valeurs manquantes par la moyenne.
- Regroupement de colonnes similaires, suppression des colonnes inutiles et préparation des données pour le clustering.
- Application de K-Means Clustering avec le Silhouette Method pour déterminer le nombre optimal de clusters.
- Visualisation et analyse des clusters et génération d’un rapport.------------------------------------------------------------------------------
## Visualisations 📈📊:
- Exemples de graphiques avec Plotly


Line[39]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot.png' height=300px, width=350px></img>

Line[40]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot2.png' height=300px, width=350px></img>

Line[41]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot3.png' height=300px, width=350px></img>

Line[42]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot4.png' height=300px, width=350px></img>

Line[43]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot5.png' height=300px, width=350px></img>

Line[44]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot6.png' height=300px, width=350px></img>

Line[45]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot7.png' height=300px, width=350px></img>

Line[46]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot8.png' height=300px, width=350px></img>

Line[47]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot9).png' height=300px, width=350px></img>

--------------------------------------------------------------------------------------------------------------------------------------------------
## Tableau Dashboards:

Dashboard 1:
(Utilisant **data_visuals.csv**)

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Dashboard1.png'></img>

Dashboard 2:
(Utilisant **data_visuals2.csv**)

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Dashboard2.png'></img>

-----------------------------------------------------------------------------------------------------------------

## ThankYou !