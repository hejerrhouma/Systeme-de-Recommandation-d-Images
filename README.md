# Système de Recommandation d'Images

Ce projet implémente un système complet de recommandation d'images basé sur le contenu, développé dans un Jupyter Notebook. Le système combine plusieurs étapes :

1. **Collecte de données**  
   Téléchargement d'images depuis Wikimedia Commons (par exemple, la catégorie "Eiffel Tower") et extraction de leurs métadonnées (dimensions, format, données EXIF, etc.).

2. **Annotation**  
   Analyse des images pour en extraire les couleurs dominantes via l'algorithme K-means et génération de tags à partir des métadonnées.

3. **Analyse et Création de Profils**  
   Construction et mise à jour des profils utilisateurs à partir des images sélectionnées. Les profils incluent des préférences telles que l'orientation, la catégorie de taille, la couleur préférée et les tags favoris.

4. **Visualisation**  
   Génération de graphiques interactifs pour explorer la répartition des images (par année, taille, orientation, etc.) ainsi que les profils utilisateurs.

5. **Recommandation**  
   Mise en œuvre d’un système de recommandation basé sur le contenu. Le système compare les caractéristiques des images avec le profil utilisateur pour recommander les images les plus pertinentes.

## Aperçu

Ce projet démontre comment construire un système de recommandation d'images en utilisant un Jupyter Notebook. Chaque phase du projet est organisée dans des cellules distinctes pour faciliter l'expérimentation et l'analyse.  
Les étapes vont de la collecte des données et leur annotation jusqu'à la création de profils utilisateurs et la recommandation finale d'images.

## Fonctionnalités

- **Collecte de données** : Extraction d'images et de leurs métadonnées depuis Wikimedia Commons.
- **Annotation** : Extraction des couleurs dominantes et génération de tags pour chaque image.
- **Création de profils utilisateurs** : Construction d'un profil utilisateur basé sur des sélections d'images (simulant des préférences).
- **Visualisation** : Création de graphiques (barres, diagrammes circulaires) pour explorer les données.
- **Recommandation** : Système de recommandation basé sur la similarité entre le profil de l'utilisateur et les caractéristiques des images.

## Structure du Projet

Le projet est contenu dans un unique Jupyter Notebook  qui regroupe toutes les phases sous forme de cellules :
- **Cellules Markdown** pour décrire chaque étape et interpréter les résultats.
- **Cellules Code** pour implémenter les fonctionnalités (collecte, annotation, analyse, visualisation, recommandation).

