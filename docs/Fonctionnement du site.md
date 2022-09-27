# Fonctionnement du site HTML
Cette page du wiki est là pour expliquer le fonctionnement de l'éditeur de site. Elle sera disposée de la manière suivante :

-- Une image de la page ou de la fonction à expliquer. --

Une explication de ce qu'elle fait.
* Les explications de ses différents composants.
## Page de login
<p align="center"> 
<img width="960" height="540" src="https://user-images.githubusercontent.com/70138284/189620292-5f3bb4e9-9200-4855-b5f4-c14f461cbd35.png">
</p>
Page très simple servant simplement à l'utilisateur de se connecter avec un compte au préalablement créé via l'activité PC-Virtuel ou depuis l'API.

* Champs
    * `email` : Email de l'utilisateur
    * `Mot de passe` : MdP de l'utilisateur
* Boutons
    * `Se connecter` : Si les identifiants sont corrects, redirige l'utilisateur sur le site en mode `connecté`.
    * `Mode invité` : Redirige la personne sur le site en mode `guest`.

## Page principale
<p align="center"> 
<img width="960" height="540" src="https://user-images.githubusercontent.com/70138284/189832452-69113acc-1057-48d3-971e-86cb181ed35f.png">
</p>

Celle sur laquelle vous allez être redirigé une fois la connexion effectuée ou le mode invité enclenché. Si l'utilisateur se connecte, la dernière version sauvegardée de son site sera directement affichée dans la colonne de visualisation. S'il n'y en avait pas ou qu'il est en mode invité, la colonne sera vide. C'est sur celle-là que vous allez créer, personnaliser et envoyer votre site. A gauche, sur le côté, vous trouverez des éléments que vous pouvez inclure à votre site, la possibilité de revenir à la dernière version et la possibilité de le sauvegarder pour qu'il soit présent sur la description de votre profil.

* `Sidebar` : (Se trouvant tout à gauche. Permet d'effectuer différentes actions tel qu'ajouter un maximum de 9 éléments, réinitialiser et sauvegarder le site.)
    * `T` : Ajoute un titre `h2` au site.
    * `P` : Ajoute un paragraphe `p` au site.
    * `--` : Ajoute un séparateur `hr` au site.
    * `IMG` : Ajoute une image `img`au site.
    * `Reset` : Retourne à la dernière sauvegarde du site. Si aucune, remet le site à 0.
    * `Save` : Sauvegarde le site sur la base. S'il y avait déjà une sauvegarde, cela l'écrasera.
* Colonne `Visualisation` : (Endroit où seront affiché les éléments qui composeront le site. Permet de sélectionner les divers éléments.)
* Colonne `Modification` : (En fonction de l'élément sélectionné dans la colonne Visualisation, fera apparaître les options de modifications de ce dernier.)
* Colonne `Code` : (Code général et simplifié du site)
    * `HTML` : Code HTML de toute la page (simplifié et coloré).
    * `CSS` : Code CSS de l'élément sélectionné (simplifié et coloré).

## Colonne Visualisation
<p align="center"> 
<img src="https://user-images.githubusercontent.com/70138284/189675085-7410438b-d2f2-46ac-bf4e-07701d6fca8c.png">
</p>

Cette colonne est là pour avoir un aperçu de la version finale du site. Elle permet aussi d'apporter quelque modification concernant l'arrangement des éléments.

* `Clique sur élément` : Surligne l'élément et fait apparaître ses options de modifications et son CSS.
    * `Flèche HAUT` : Monte l'élément d'un cran. Impossible si en haut de la colonne.
    * `Flèche BAS` : Baisse l'élément d'un cran. Impossible si en bas de la colonne.
    * `Croix rouge` : Supprime l'élément sélectionné avec une demande de confirmation.

## Colonne Modification


Cette colonne permet de modifier l'élément sélectionné en fonction de son type.

### Titre / Paragraphe
<p align="center"> 
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/70138284/189680672-6240f9f4-7c0d-45a5-b664-52c1d8119ea7.png">
</p>

Les possibilités de modifications des titres sont les mêmes de celles des paragraphes.

* Contenu :
    * `Zone de texte` : Permet d'écrire un titre ou un paragraphe de maximum 150 lettres.
* Mise en forme:
    * `Police` : Change la police de tout le texte de l'élément.
    * `Alignement` : Change l'alignement de tout le texte de l'élément.
    * `Décoration te texte` : Possibilité de souligner, mettre en gras et en italique tous le texte de l'élément.
    * `Taille` : Change la taille de tout le texte de l'élément.
* Couleur:
    * `Color Picker` : Change toute la couleur de texte de l'élément.

### Séparateur
<p align="center"> 
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/70138284/189824294-a323a995-55ff-4d7d-ac4d-68ad4b0d149c.png">
</p>

Permet de modifier un séparateur.
* Dimension :
    * `Hauteur` : Modifie la hauteur du séparateur.
    * `Largeur` : Modifie la largeur du séparateur.
* Couleur :
    * `Color picker` : Change la couleur du séparateur.

### Image
<p align="center"> 
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/70138284/189832852-0dcec433-19d7-4991-89d0-ee99a13d505d.png">
</p>

Permet de modifier une image. C'est l'option avec le plus de personnalisation.
* Choix de l'image:
    * `Carrousel` : Permet de changer l'image présente sur le site parmi celles mises à disposition.
* Dimension :
    * `Largeur` : Modifie la largeur de l'image.
    * `Hauteur` : Modifie la largeur de l'image.
    * `Cadenas` : Permet de verrouiller ou non la hauteur de l'image. Si la largeur est verrouillée et que la hauteur est modifiée, la largeur changera proportionnellement au ratio de l'image. Par défaut verrouillé.

    * `Alignement` : Permet de changer l'alignement de l'image (gauche, centre, droite).

<p align="center"> 
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/70138284/189833108-0aea75a6-9d4b-49ff-9cd0-e6962e6bfd3f.png">
</p>

* Filtres :
    * `Flou` : Modifie le flou de l'image.
    * `Contraste` : Modifie le contraste de l'image.
    * `Luminosité` : Modifie la luminosité de l'image.
    * `Niveau de gris` : Modifie les nuances de gris de l'image.
* Bordure :
    * `Épaisseur` : Modifie l'épaisseur de la bordure de l'image.
    * `Arrondi` : Ajoute un arrondi à la bordure de l'image.
    * `Color picker` : La couleur de la bordure de l'image.


## Colonne Code
<p align="center"> 
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/70138284/189834195-4ff152ee-cf32-44d7-912c-888a8c923d77.png">
</p>

Cette colonne permet d'avoir un aperçu de ce qu'est le code HTML et CSS. Pour que le code soit compréhensible, il est simplifié autant au niveau HTML que CSS.

* `Bouton` :
    * `Déconnexion` : Permet à l'utilisateur de se déconnecter du site. Ne sauvegarde pas les données du site mais demande tous de même une conformation. N'est pas apparent si le mode invité est activé.
* `HTML` : Permet d'avoir une vue globale et simplifiée de l'HTML du site. Met en évidence l'élément sélectionné.
* `CSS` : Vue simplifiée du CSS de l'élément sélectionné.