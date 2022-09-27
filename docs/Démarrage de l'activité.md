# Démarrage de l'activité
Concernant le stand, il y a deux manière de le faire fonctionner, la manière online ou local. Qu'il soit lancé d'une manière ou d'une autre, rien ne change au bon fonctionnement de l'application.
## Online
C'est la méthode principale de lancement. On utilise une fonctionnalité `kiosk` de firefox pour restreindre certaines touches et options afin que l'utilisateur soit le moins perturbé durant son activité.

Sur les NUC mis à disposition, il devrait se trouver sur le bureau un lien direct vers le site en mode kiosk.
Si il n'est pas disponible, suivez les étapes suivantes :
* Ouvrez l'invite de commande allez dans le répertoire du navigateur `firefox` en utilisant la commande : `cd "C:\Program Files\Mozilla Firefox"`.
* Lancement de la fenêtre en mode kiosk : `firefox.exe -klosk -private-window html-mars.divtec.ch`.

Normalement, votre fenêtre est ouverte en plein écran avec la page de connexion.

## Local
En cas d'inaccessibilité du site en ligne, la même version se trouve en local et prête à être utilisée. Le fichier est en invisible sur le bureau.

Pour lancer la version en local, suivez les étapes suivantes :
* Ouvrez l'invite de commande `NodeJS` depuis son raccourcis sur le bureau ou en recherchant `Node.js command prompt` depuis le menu démarrer de Windows.
* Naviguez jusqu'à l'emplacement du projet avec la commande : `cd C:\Users\Client\Desktop\2022-PO-LMO-HTML`.
* Vérifiez l'installation des composants Node avec la commande : `npm i`.
* Lancez le site avec la commande suivante : `npm run serve`.
* Une fois terminé, ouvrez l'invite de commande Windows et allez dans le répertoire du navigateur `firefox` en utilisant la commande : `cd "C:\Program Files\Mozilla Firefox"`.
* Lancez la fenêtre en mode kiosk : `firefox.exe -klosk -private-window http://localhost:8080/`.