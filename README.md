# 📊 Projet Data : Analyse des Ventes TechNova

## 📌 Description du projet
L'objectif est d'analyser les données de vente de la boutique **TechNova** pour l'année 2025 afin d'en tirer des insights stratégiques (performances, logistique, tendances).

## 📂 Structure des Données
Le fichier `ventes_technova.csv` contient les colonnes suivantes :
- `id_commande` : Identifiant unique.
- `date_achat` : Date de la transaction.
- `nom_produit` : Nom de l'article acheté.
- `quantite` : Nombre d'unités.
- `mode_paiement` : Carte Bleue, PayPal, ou Apple Pay.
- `ville_client` : Ville de livraison.
- `delai_livraison_jours` : Nombre de jours pour recevoir le colis.
- `prix_unitaire` : Prix d'un article (attention : contient des erreurs/vides).

## 🎯 Missions à réaliser
1. **Data Cleaning** :
   - Supprimer les doublons.
   - Gérer les valeurs manquantes dans la colonne `prix_unitaire`.
2. **Analyse de Performance** :
   - Calculer le Chiffre d'Affaires (CA) total ($Quantité \times Prix$).
   - Identifier les 3 produits les plus vendus.
3. **Visualisation** :
   - Créer un graphique de l'évolution du CA par mois.
   - Comparer les délais de livraison par ville via un Boxplot.
