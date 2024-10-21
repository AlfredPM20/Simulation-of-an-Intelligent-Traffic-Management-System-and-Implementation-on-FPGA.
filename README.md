# Simulation-of-an-Intelligent-Traffic-Management-System-and-Implementation-on-FPGA.

****Détails de Mise en Œuvre****

Ce projet peut être divisé en 3 modules :

Module de Détection des Véhicules 

Ce module est responsable de la détection du nombre de véhicules dans l'image reçue en entrée de la caméra. Plus précisément, il fournira en sortie le nombre de véhicules de chaque classe de véhicule tels que voiture, moto, bus, camion et rickshaw.

Algorithme de Changement de Signal 

Cet algorithme met à jour les temps de feu rouge, vert et jaune de tous les signaux. Ces minuteries sont réglées en fonction du nombre de véhicules de chaque classe reçus du module de détection des véhicules ainsi que plusieurs autres facteurs tels que le nombre de voies, la vitesse moyenne de chaque classe de véhicule, etc.

Module de Simulation 

Une simulation est développée à partir de zéro en utilisant la bibliothèque Pygame pour simuler les signaux de trafic et les véhicules se déplaçant à travers une intersection routière.

***Etapes pour faire la simulation du projet***

Pour exécuter la simulation de l'intersection routière en utilisant Visual Studio Code (VS Code), suivez ces étapes :

1) Téléchargez le Dossier :

Téléchargez le dossier Traffic Intersection Simulation sur votre bureau.

2) Ouvrez VS Code :

Lancez Visual Studio Code.

3) Ouvrez le Dossier :

Dans VS Code, allez dans le menu et cliquez sur Fichier > Ouvrir un dossier....
Accédez à votre bureau, sélectionnez le dossier Traffic Intersection Simulation, puis cliquez sur Sélectionner le dossier ou Ouvrir.

4) Exécutez la Simulation :

Assurez-vous d'avoir installé les dépendances nécessaires. Cela peut inclure Python, Pygame, et toute autre bibliothèque spécifiée dans les exigences du projet.
