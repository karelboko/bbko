
# Projet d'Analyse et de Prédiction du Bitcoin à partir de Données de News

Ce projet a pour objectif de créer un système d'analyse et de prédiction du prix du Bitcoin en utilisant des données de news et des techniques d'apprentissage automatique. Nous récupérons les données quotidiennes de news concernant le Bitcoin et les analysons à l'aide de trois bibliothèques d'analyse sentimentale : Vader, TextBlob et Fair. Les résultats de ces analyses sont ensuite combinés avec les données historiques du prix du Bitcoin sur une période de 5 ans.

## Objectifs

- Collecter et prétraiter les données de news sur le Bitcoin.
- Appliquer une analyse de sentiment à l'aide des bibliothèques Vader, TextBlob et Fair.
- Intégrer les scores de sentiment aux données historiques du prix du Bitcoin.
- Mettre en place différents modèles d'apprentissage automatique pour la prédiction du prix futur du Bitcoin.
- Explorer la possibilité d'ajouter des indicateurs techniques pour améliorer les performances du modèle.

## Comment ça fonctionne

1. **Collecte des données de news** : Les données de news sur le Bitcoin sont collectées quotidiennement à partir de sources fiables.

2. **Analyse de sentiment** : Les textes des news sont analysés en utilisant les bibliothèques Vader, TextBlob et Fair pour déterminer les scores de sentiment (positif, négatif, neutre).

3. **Intégration des scores de sentiment** : Les scores de sentiment sont combinés avec les données historiques du prix du Bitcoin sur 5 ans.

4. **Prédiction du prix du Bitcoin** : Différents modèles de machine learning (par exemple : réseaux de neurones, arbres de décision, etc.) sont entraînés à prédire le prix futur du Bitcoin en utilisant les données de news et historiques.

5. **Indicateurs techniques (optionnel)** : Des indicateurs techniques comme les moyennes mobiles, le RSI, etc., peuvent être intégrés pour améliorer les performances du modèle.

## Configuration

Pour exécuter ce projet localement, suivez ces étapes :

1. Clônez ce référentiel : `git clone https://github.com/yourusername/your-repo.git`
2. Installez les dépendances requises : `pip install -r requirements.txt`
3. Exécutez le script de collecte de données : `python collect_data.py`
4. Exécutez le script d'analyse de sentiment : `python analyze_sentiment.py`
5. Exécutez le script de prédiction : `python predict_price.py`

## Contribuer

Les contributions à ce projet sont les bienvenues ! Si vous avez des idées d'amélioration, des corrections ou des nouvelles fonctionnalités à ajouter, n'hésitez pas à ouvrir une demande d'extraction (Pull Request).

## Mentions légales

Ce projet utilise les données de l'API NewsCatcher (https://newscatcherapi.com/) pour collecter les informations de news sur le Bitcoin. Assurez-vous de respecter leurs termes et conditions.
