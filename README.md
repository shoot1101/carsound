# 🔊 Carsound
60+ Custom Engine sound Fivem


![GitHub followers](https://img.shields.io/github/followers/shoot1101?style=for-the-badge) ![GitHub Repo stars](https://img.shields.io/github/stars/shoot1101/carsound?style=for-the-badge) [![](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)]((https://discord.gg/X36mxQTk5b)) ![Twitch Status](https://img.shields.io/twitch/status/BobMarly1?style=for-the-badge)


## **ℹ️ Informations**


**English** :

Vehicle Sound Modification Guide

This guide provides instructions for modifying vehicle sounds in FiveM using the "carsound" resource. Follow the steps below to add or modify vehicle sounds according to your preferences.

Step 1: Installing the carsound Resource

Make sure you have already installed FiveM on your server. To add the "carsound" resource, follow these steps:

Place the "carsound" folder into the "resources" directory of your FiveM server.
In your server's server.cfg file, add the following line: ensure carsound.
Restart your FiveM server to apply the changes.
Step 2: Modifying Vehicle Sounds

Open the vehicles.meta file of the vehicle you want to modify. You can usually find this file in the vehicle's data folder. Look for the line that looks like this: (played sound name). This line indicates the name of the sound played by the vehicle. Replace the "(played sound name)" with the name of the sound you want to use. Use the proper format: sound_name. Make sure the sound name matches the one you have in your "carsound" resource. Example:

If you want to use the sound named "dlc_aq11bmw298cc", replace the line (played sound name) with aq11bmw298cc.

Step 3: Final Configuration

Once you have made the modifications in the vehicles.meta file, save it and restart your FiveM server to apply the changes.


I am not the creator of the sounds; they all come from the website : https://www.gta5-mods.com/

I only make this pack to make it easier for users to have several sounds in one resource.



**Francais** :

Guide de Modification de Sons de Véhicules

Ce guide fournit des instructions pour modifier les sons des véhicules dans FiveM en utilisant la resource "carsound". Suivez les étapes ci-dessous pour ajouter ou modifier les sons de véhicules selon vos préférences.

Étape 1 : Installation du resource carsound

Assurez-vous d'avoir déjà installé FiveM sur votre serveur. Pour ajouter le resource "carsound", suivez les étapes suivantes :

Placez le dossier "carsound" dans le répertoire "resources" de votre serveur FiveM.
Dans le fichier server.cfg de votre serveur, ajoutez la ligne suivante : ensure carsound.
Redémarrez ensuite votre serveur FiveM pour que les changements prennent effet.

Étape 2 : Modification des Sons de Véhicules

Ouvrez le fichier vehicles.meta du véhicule que vous souhaitez modifier. Vous pouvez généralement le trouver dans le dossier data du véhicule.
Recherchez la ligne qui ressemble à ceci : <audioNameHash>(nom du son joué)</audioNameHash>. Cette ligne indique le nom du son qui est joué par le véhicule.
Remplacez le "nom du son joué" par le nom du son que vous souhaitez utiliser. Utilisez le format approprié : <audioNameHash>nom_du_son</audioNameHash>. Assurez-vous que le nom du son correspond à celui que vous avez dans votre ressource "carsound".
Exemple :

Si vous souhaitez utiliser le son nommé "dlc_aq11bmw298cc", remplacez la ligne <audioNameHash>(nom du son joué)</audioNameHash> par <audioNameHash>aq11bmw298cc</audioNameHash>.

Étape 3 : Configuration Finale

Une fois que vous avez effectué les modifications dans le fichier vehicles.meta, enregistrez-le et redémarrez votre serveur FiveM pour que les changements prennent effet.


## **🧱Exigences et ⚙️Configuration**


```lua
ensure carsound
```

## **💌Crédits**


* I'd also like to mention that the content of this pack comes mainly from 5MODS, as no comparable package has been available until now. Many thanks to the original creators for their fantastic work! Please don't hesitate to contact me if there's any specific content you'd like to see removed!

* Je voudrais également mentionner que le contenu de ce pack provient principalement de 5MODS, car aucun package comparable n'était disponible jusqu'à présent. Un grand merci aux créateurs originaux pour leur travail fantastique ! N'hésitez pas à me contacter s'il y a des contenus spécifiques que vous aimeriez voir supprimés !


## **⚠️Licence**


* If you are a creator and don't want the sound to be here on GitHub, just create an issue and pull request!
* Si vous êtes un créateur et que vous ne voulez pas que les sons soient ici sur GitHub, créez simplement un problème et une pull request !


