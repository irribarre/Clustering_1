## 1) PROJET :
Problème de clustering (méthode d'apprentissage non supervisée).
<br/>
<br/>
<br/>
## 2) PROBLEMATIQUE : 
Segmenter les clients d’un site e-commerce.<br/>
Analyser la stabilité des segments au cours du temps.<br/>
Proposer un contrat de maintenance.
<br/>
<br/>
<br/>
## 3) DATASET :
Données client fournies par Olist (le plus grand site e‑commerce brésilien) : historique de commandes, produits achetés, commentaires de satisfaction, localisation.
<br/>
<br/>
<br/>
## 4) NOTEBOOKS :
- NOTEBOOK D'EXPLORATION : **1_notebook_exploration.ipynb** :<br/>
-- *Analyse univariée.*<br/>
-- *Analyse bivariée.*<br/>
-- *Feature engineering (dataframe commande centré).*<br/>
-- *Dataframe client centré.*<br/>
- NOTEBOOK D'ESSAI DES DIFFRENTES APPROCHES EXPLORATOIRES : **2_notebook_essais_light.ipynb** (version avec des traces réduites) : <br/>
-- *Clustering algorithme K-Means (méthode elbow, méthode coefficient de silhouette).*<br/>
-- *Clustering algorithme DBSCAN.*<br/>
- DETERMINATION DE LA FREQUENCE NECESSAIRE DE MISE A JOUR DU MODELE DE SEGMENTATION : **3_notebook_simulation.ipynb**.