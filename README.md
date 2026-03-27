# 🎬 Movie Recommender System

Une application web interactive basée sur l'intelligence artificielle pour recommander des films similaires à vos favoris.

## ✨ Fonctionnalités

* ** Moteur de Recommandation :** Suggère 5 films basés sur la similarité du contenu (Content-Based Filtering).
* ** Bandes-annonces :** Affiche automatiquement le trailer YouTube du film recommandé.
* ** Affiches & Résumés :** Récupère les posters officiels et les descriptions via l'API TMDB.
* ** Watchlist :** Permet d'ajouter des films à une liste de favoris et de les gérer.
* ** Interface Moderne :** Interface fluide et réactive construite avec Streamlit.

## 🛠️ Technologies utilisées

* **Python** (Langage principal)
* **Streamlit** (Interface Web)
* **Pandas** (Manipulation de données)
* **Scikit-Learn** (Calcul de similarité Cosine)
* **TMDB API** (Images et données de films)

## ⚙️ Installation locale

Si vous voulez lancer ce projet sur votre propre ordinateur :

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/IMANE-ABDELJALILI/movie-recommender.git](https://github.com/IMANE-ABDELJALILI/movie-recommender.git)
    cd movie-recommender
    ```

2.  **Installer les dépendances :**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Configurer la clé API :**
    Créez un fichier `.env` à la racine du projet et ajoutez votre clé TMDB :
    ```text
    TMDB_API_KEY=votre_clé_api_ici
    ```

4.  **Lancer l'application :**
    ```bash
    streamlit run app.py
    ```

## 📂 Structure des données

Le système utilise deux fichiers principaux (compressés pour GitHub) :
* `movie_dict.pkl` : Dictionnaire contenant les titres et IDs des films.
* `similarity.pkl` : Matrice de similarité pré-calculée.

---
*Développé avec ❤️ par Jihane BOUGRINE
