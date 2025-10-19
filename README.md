# image--generator
Projet IA générative - génération d’images à partir de texte

#  IA Générative d’Images à partir de Texte avec Contrôle de Style

Ce projet est une **application d’IA générative** qui permet de **créer des images à partir de descriptions textuelles**, tout en permettant à l’utilisateur de **choisir un style artistique** 

L’application s’appuie sur la bibliothèque **Diffusers de Hugging Face** et une interface **Gradio** pour une utilisation simple.

---

##  Contenu du projet

- **`app.py`** : script principal contenant le code de l’application Gradio.  
  Il :
  - charge un modèle Stable Diffusion via la librairie `diffusers` ;
  - prend une *invite textuelle* (prompt) et un *style* sélectionné par l’utilisateur ;
  - génère une image cohérente avec la description ;
  - affiche le résultat dans une interface web interactive.

- **`requirements.txt`** : liste des dépendances nécessaires pour exécuter le projet 
