# carsound
60 Custom Engine sound Fivem

English :

Vehicle Sound Modification Guide

This guide provides instructions on how to modify vehicle sounds in FiveM using the "carsound" resource. Follow the steps below to add or modify vehicle sounds according to your preferences.

Step 1: Installing the carsound Resource

Make sure you have FiveM already installed on your server. To add the "carsound" resource, follow these steps:

Place the "carsound" folder in the "resources" directory of your FiveM server.
In your server's server.cfg file, add the following line: ensure carsound.
Then, restart your FiveM server for the changes to take effect.
Step 2: Vehicle Sound Modification

Open the vehicles.meta file of the vehicle you wish to modify. You can usually find this file in the vehicle's data folder.
Look for the line that looks like this: <audioNameHash>(sound name played)</audioNameHash>. This line indicates the name of the sound being played by the vehicle.
Replace the "sound name played" with the name of the sound you want to use. Use the appropriate format: <audioNameHash>sound_name</audioNameHash>. Ensure that the sound name matches the one you have in your "carsound" resource.
Example:

If you want to use the sound named "dlc_aq11bmw298cc," replace the line <audioNameHash>(sound name played)</audioNameHash> with <audioNameHash>aq11bmw298cc</audioNameHash>.

Step 3: Final Configuration

Once you have made the modifications in the vehicles.meta file, save it and restart your FiveM server to apply the changes.

That's it! You have successfully modified vehicle sounds in FiveM using the "carsound" resource.

Remember to back up your original files before making changes and test modifications in a testing environment before applying them to your live server.

If you have any questions or encounter issues, feel free to consult the FiveM documentation or seek help on the FiveM community forums.


Francais :

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
