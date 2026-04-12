# 🧠 Autoencodeurs & Autoencodeurs Variationnels (VAE)

## 📝 Description
Ce projet explore la création, l'entraînement et l'utilisation d'Autoencodeurs. Il commence par l'implémentation d'un Autoencodeur classique pour la reconstruction de données, évolue vers un Autoencodeur Variationnel (VAE) pour la génération, et se termine par une application concrète du VAE sur le célèbre jeu de données CelebA (visages humains).

## 📂 Structure du Projet

* **`Autoencoder.ipynb`** : Implémentation et entraînement d'un Autoencodeur standard (réduction de dimensionnalité et reconstruction).
* **`VariationalAutoEncoder.ipynb`** : Implémentation d'un Autoencodeur Variationnel (VAE) introduisant l'échantillonnage latent pour la génération de nouvelles données.
* **`VariationalAutoEncoder_CelebA.ipynb`** : Application spécifique et avancée du modèle VAE sur le dataset CelebA pour générer et reconstruire des visages.
* **`AEmodel_state_dict.pth`** : Fichier contenant les poids (paramètres) sauvegardés du modèle Autoencodeur pré-entraîné.

## ⚙️ Prérequis et Installation

1. **Cloner le dépôt :**

    git clone https://github.com/Tytyaz2/AutoEncodeur.git
    cd AutoEncodeur

2. **Installer les dépendances :**

    pip install numpy torch torchvision matplotlib jupyter

## 🚀 Utilisation

1. **Lancez l'environnement Jupyter :**

    jupyter notebook

2. **Reconstruction basique :** Ouvrez `Autoencoder.ipynb` pour comprendre le fonctionnement de base et tester la reconstruction d'images. Vous pouvez charger les poids existants via `AEmodel_state_dict.pth`.
3. **Génération avec VAE :** Explorez `VariationalAutoEncoder.ipynb` pour voir comment l'espace latent permet de générer de nouvelles images.
4. **Génération de visages :** Lancez `VariationalAutoEncoder_CelebA.ipynb` pour observer les performances du VAE sur des données plus complexes (attention, le téléchargement du dataset CelebA peut prendre un peu de temps lors de la première exécution).

## 👨‍💻 Auteurs
* [@Tytyaz2](https://github.com/Tytyaz2)
* [@LoloLeRigaulO](https://github.com/LoloLeRigaulO)
