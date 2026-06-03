# luggage-ar-measurer

# 📏 Assistant de Mesure Bagage (OUIGO)

Application web mobile permettant de vérifier si un bagage respecte les dimensions cabine, en utilisant deux méthodes :

## 🚀 Fonctionnalités

1. **Mesure AR (Réalité Augmentée) :** - Utilise l'API WebXR pour détecter le sol.
   - Permet de mesurer manuellement une distance réelle en plaçant deux points dans l'espace 3D.
   - Idéal pour une précision millimétrée sur n'importe quel objet.

2. **Mesure via Intelligence Artificielle (YOLO) :**
   - Utilise TensorFlow.js pour détecter en temps réel un bagage et un ballon de football (référence de taille).
   - Calcule automatiquement les dimensions du bagage par rapport au ballon.
   - Interface intuitive de capture photo.

## 🛠 Technologies utilisées
- **Three.js & WebXR** : Pour le moteur 3D et la réalité augmentée.
- **TensorFlow.js** : Pour l'exécution du modèle YOLO dans le navigateur.
- **HTML5/CSS3** : Design responsive aux couleurs de la marque.

## ⚙️ Installation pour développement
1. Clonez ce dépôt.
2. Assurez-vous d'avoir un serveur local (l'AR nécessite HTTPS ou `localhost`).
3. Placez votre modèle YOLO dans un dossier `/model/`.

## 📝 Licence
Projet réalisé dans un cadre d'étude et d'optimisation de l'expérience voyageur.
