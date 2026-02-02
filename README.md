# ✈️ RAM Companion : Moteur Prédictif & Intelligence Client
> **Innovation Data pour Royal Air Maroc** | *Focus : Feature Engineering, Analyse Statistique & Visualisation Stratégique*

##  Contexte et Enjeux Business
Dans le cadre d'un projet d'innovation pour **Royal Air Maroc**, j'ai conçu le moteur analytique de l'application **RAM Companion**. Le défi : personnaliser l'expérience de 8,2 millions de passagers annuels sans collecte de données intrusives (*Privacy-First*).

Le moteur résout le problème du **"Cold Start"** (démarrage à froid) : il génère des recommandations pertinentes dès le premier voyage en transformant 5 variables transactionnelles basiques en indicateurs comportementaux avancés.

---

##  Résumé Exécutif 
L'analyse de **103 904 observations** a permis de valider 12 corrélations comportementales majeures ($p < 0,05$).

* **Gisement de Valeur (Upsell) :** Identification de **27 790 passagers** au profil "Business" voyageant actuellement en classe Économique.
* **Performance Opérationnelle :** Réduction prévue de **8 à 12%** du volume d'appels au centre de contact par l'anticipation proactive du stress passager.
* **Précision du Modèle :** Précision initiale de **75%** via des règles heuristiques, avec une trajectoire vers **90%** via Machine Learning (XGBoost).

---

## 🏗️ Maîtrise Technique : Feature Engineering & Pipeline
L'essentiel de ma contribution réside dans la création de **7 variables intelligentes** pour révéler les préférences cachées à partir de données "froides" :

| Variable Créée | Logique Analytique (Proxy) | Valeur Ajoutée Business |
| :--- | :--- | :--- |
| **Motif_Voyage** | Corrélation entre l'âge, le type de vol et la durée du séjour. | Adaptation de l'interface (Business vs Loisir). |
| **Risque_Churn** | Scoring basé sur les "points de douleur" (Cabine Éco + Long-Courrier). | Rétention proactive des segments fragiles. |
| **Appétence_Digitale** | Agrégation des notes de services Wifi et boarding en ligne. | Priorisation du self-service vs assistance humaine. |
| **Etat_Aeroport** | Proxy via la localisation de la porte (Gate Location). | Prédiction du stress pour suggestions de Fast-Track. |



---

##  Analyse & Visualisation Stratégique (Power BI)
Le dashboard a été structuré pour transformer le diagnostic technique en plan d'action immédiat.

<img width="527" height="339" alt="Screenshot 2026-02-02 224717" src="https://github.com/user-attachments/assets/26a6fd7b-2e10-48d6-a07b-7e930dda3bd0" />


<img width="533" height="378" alt="Screenshot 2026-02-02 224754" src="https://github.com/user-attachments/assets/ac14d28b-27c3-49f2-a77b-6e863daa064a" />

### 1. Diagnostic de la Satisfaction
* **Analyse de la Flotte :** Mise en évidence d'une baisse de confort de **15%** sur les Boeing 737-800 par rapport aux 787 Dreamliner.
* **Cartographie des "Pain Points" :** Visualisation d'une chute de satisfaction de **-40%** liée aux retards supérieurs à 15 minutes.

### 2. Fracture Digitale
Alors que **70% des 25-60 ans** présentent une appétence "High Tech", ce chiffre chute à **20% pour les seniors**. Cette donnée impose une architecture d'application **adaptative**.



---

## 🛠️ Stack Technique
* **Langages :** Python (Pandas, NumPy, SciPy pour les tests statistiques).
* **Visualisation :** Power BI (Modélisation de données, DAX, Power Query).
* **Infrastructure :** Déploiement MVP sur Azure avec API FastAPI.
* **Rigueur Scientifique :** Validation des patterns via tests de significativité ($p-value$).

---

## 📈 Stratégie d'Amélioration Continue
1.  **Phase 1 (Actuelle) :** Moteur heuristique (Précision 75%) pour valider l'UX.
2.  **Phase 2 (M6) :** Transition vers **XGBoost** (Machine Learning supervisé) après collecte de 20 000 interactions.
3.  **Phase 3 (M12) :** Extension de la solution en mode SaaS pour le réseau africain.

---
> **Note :** Projet académique réalisé à l'**École Centrale Casablanca** en collaboration avec **Royal Air Maroc** (Décembre 2025).

---
**Contact :** [MAJRI Douha] – [www.linkedin.com/in/douha-majri]
