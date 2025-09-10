# Moteur-de-recommandations ( EN COURS )
Moteur de recommandations pour l’optimisation du panier client

## Description
Ce projet met en place un système de recommandation client appliqué au secteur du retail et de la supply chain.  
Il permet de suggérer automatiquement des produits complémentaires à partir de l’historique des achats, afin d’améliorer :  
- l’expérience client (panier plus complet et personnalisé)  
- le chiffre d’affaires via le cross-sell  
- la gestion des stocks en anticipant les associations de produits  

---

## Données utilisées
Le projet s’appuie sur le dataset [Instacart Market Basket Analysis](https://www.kaggle.com/competitions/instacart-market-basket-analysis), qui contient des millions de commandes réelles passées par des clients.  

---

## Méthodologie
1. Préparation et nettoyage des données  
2. Construction d’une matrice produits–commandes  
3. Application de deux approches :  
   - Règles d’association (Apriori/FP-growth) pour identifier les produits souvent achetés ensemble  
   - Filtrage collaboratif item–item pour trouver les produits similaires selon les paniers  
4. Génération de recommandations : à partir d’un produit choisi, le modèle propose les produits complémentaires les plus pertinents  

---

## Démo (exemple)
- Input : Pâtes  
- Output : Sauce tomate, Parmesan, Huile d’olive  

---

## Stack technique
- Python  
- pandas, numpy  
- scikit-learn  
- mlxtend (Apriori, FP-growth)  
- Streamlit (optionnel pour interface)  

---

## Résultats attendus
- Amélioration de la personnalisation pour les clients  
- Opportunités de cross-sell pour les enseignes retail  
- Vision exploitable pour les équipes marketing et supply chain  

