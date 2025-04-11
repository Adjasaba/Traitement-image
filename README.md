# 🖼️ **Traitement d'Images : Manipulation et Visualisation** 🎨

## 📜 Description du projet

Ce projet propose une série de traitements d'images appliqués sur 9 images récupérées sur **Lorem Picsum**. Le but est de manipuler ces images à travers différentes étapes de transformation, comme le redimensionnement, le recadrage, la normalisation des histogrammes, et l'affichage sous forme de grilles.

Les principales étapes de traitement sont les suivantes :

1. **Redimensionnement et Recadrage** 📏
2. **Normalisation des Histogrammes** 📊
3. **Affichage des Grilles d'Images et d'Histogrammes** 📷
4. **Traitements Avancés sur une Image** 🔧

## 🚀 Fonctionnalités

1. **Redimensionnement et Recadrage** 🔲  
   Les images récupérées depuis **Lorem Picsum** sont au format paysage et de différentes tailles. Elles sont ensuite redimensionnées de manière **homothétique** et recadrées par le centre pour obtenir une taille uniforme de **512x512 pixels**.

2. **Normalisation des Histogrammes** 🌈  
   Chaque image est normalisée en fonction d'une image de référence ou à l'aide de techniques comme :  
   - **Contrast Stretching** 🌟  
   - **Equalisation automatique** 🔄

3. **Affichage des Grilles** 🖼️  
   Une grille de **3x3** est générée pour afficher les images traitées, et une autre pour afficher les histogrammes **normalisés** et **cumulatifs**.  
   Ces grilles sont enregistrées sous forme de fichiers images avec un nom formaté : `NOM_Prenom - Grille n#`.

4. **Traitements Avancés sur une Image** 🛠️  
   Une image choisie aléatoirement parmi le dataset subit diverses transformations, affichées dans une grille de **3x2** :  
   - **Ligne du haut** :  
     1. Image en **noir et blanc** 🖤  
     2. Image en **noir et blanc** avec teinte aléatoire sur chaque couche 🎨  
     3. Image **seuillée en HSV** 🌈  
   - **Ligne du bas** :  
     1. Ajout de **bruit** et **denoising** par filtre moyen non-local 🔊  
     2. Ajout de **bruit** et **denoising** par une autre méthode 🧹  
     3. Ajout de **défauts** et traitement par **inpainting** 🧑‍🔬

## 🛠️ Technologies utilisées

- **Python** 🐍 : Langage principal utilisé pour le traitement des images.
- **matplotlib** 📊 : Pour l'affichage des images et des histogrammes.
- **PIL (Pillow)** 🖼️ : Pour la manipulation des images (redimensionnement, recadrage, conversion en N&B, etc.).
- **NumPy** 🔢 : Pour les manipulations des données d'images sous forme de tableaux.
- **OpenCV** 🏁 : Utilisé pour le filtrage, le denoising et l'inpainting.
- **scikit-image** 🧩 : Bibliothèque pour le traitement d'images, utilisée pour les techniques de normalisation des histogrammes et de seuillage.

