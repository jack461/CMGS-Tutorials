# Tutorial 1: The Octo Project

## Description

The **Octo Project** is basically a concert program, where different composers sent a set of samples. I have kept the files that where put in creative common by their authors. Here are the sources of the files, ordered by group number.

3. Gilles Roussi
7. Diego Losa
11. Francis Valery
12. Alain Girardot
13. Jean-Jacques Girardot
20. Alain Girardot

Groups 0, 1, 33 are variations of these, using a mix of the provides files.

## Installing

You need the **CMGS** plug-in, that you can download from the https://github.com/jack461/CMGS directory, and of course a recent version of **REAPER** (v7.25 or later), from http://reaper.fm/download.php.

Check first that your sound card is recognized by REAPER (open the menu "Options > Setting...", and check "Audio > Device").

> [!IMPORTANT]
> Some settings may prevent the GameMaster to function correctly. Do check in the "REAPER Preferences" that in "Audio", both "Close audio device when stopped..." options are *not* set, and in "Audio > Playback" that "Run FX when stopped" is set. 

1.  Download the tutorials (Go to https://github.com/jack461/CMGS-Tutorials, click on the green "Code" button, and select "Download ZIP"), and install the folder *GM-OCTO-2024* anywhere on your system.
2.  In *GM-OCTO-2024*, *Remove* the file **Effects**
3.  Copy the **CMGS** (or **CMGS-main**) folder into the project directory, and rename it **Effects**.
4.  Double-click "GM-Octo.RPP"
5.  This runs REAPER, but in the "System Log" of the plug-in, you get a lot of error messages, like "ERR: 2405 can't compile ..."
6.  Drag and drop the "GM-Octo.RPP" file in the "GameMaster" window. Thanks to this action, the plug-in can determine the location of the needed files.
7.  Save the project and quit REAPER.
8.  Run REAPER again. This time, the configuration files are found, and the last script displays ** GAME MASTER / SESSION OCTO READY **.

## Exploring

You can now test the automatic generation of sounds. Just click the grey **Auto-play** (upper left, just under the "Main" tabulation indicator). It should turn green, and you should hear something playing. Note that the output is stereo. If you have a multi-channel configuration, you can switch easily to octo: click the FX button on the MASTER Track, and uncheck the second plug-in (channels-folder.jsfx). 

It is now time to read the manual :-(

# Tutoriel 1: Le projet Octo

## Description

Le **Projet Octo** est à la base un programme de concert, où différents compositeurs ont envoyé un ensemble d'échantillons. J'ai conservé les fichiers qui ont été mis en creative common par leurs auteurs. Voici les sources des fichiers, classées par numéro de groupe.

3. Gilles Roussi
7. Diego Losa
11. Francis Valery
12. Alain Girardot
13. Jean-Jacques Girardot
20. Alain Girardot

Les groupes 0, 1, 33 sont des variantes de ceux-ci, utilisant un mélange des fichiers fournis.

## Installation

Vous avez besoin du plug-in **CMGS**, que vous pouvez télécharger depuis le répertoire https://github.com/jack461/CMGS, et bien sûr d'une version récente de **REAPER** (v7.25 ou ultérieure), téléchargeable depuis http://reaper.fm/download.php.

Vérifiez d'abord que votre carte son est reconnue par REAPER (ouvrez le menu "Options > Réglage...", et vérifiez "Audio > Périphérique").

> [!IMPORTANT]
> Certains paramètres peuvent empêcher le GameMaster de fonctionner correctement. Vérifiez dans les "Préférences REAPER" que dans "Audio", les deux options "Fermer le périphérique audio à l'arrêt..." ne sont *pas* définies, et dans "Audio > Lecture" que "Exécuter les effets à l'arrêt" est défini.

1. Téléchargez les tutoriels (allez sur https://github.com/jack461/CMGS-Tutorials, cliquez sur le bouton vert "Code" et sélectionnez "Télécharger le ZIP") et installez le dossier *GM-OCTO-2024* n'importe où sur votre système.
2. Dans *GM-OCTO-2024*, *Supprimez* le fichier **Effects**
3. Copiez le dossier **CMGS** (ou **CMGS-main**) dans le répertoire du projet et renommez-le **Effects**.
4. Double-cliquez sur "GM-Octo.RPP"
5. Cela exécute REAPER, mais dans le "System Log" du plug-in, vous obtenez de nombreux messages d'erreur, comme "ERR: 2405 can't compile ..."
6. Faites glisser et déposez le fichier "GM-Octo.RPP" dans la fenêtre "GameMaster". Grâce à cette action, le plug-in peut déterminer l'emplacement des fichiers nécessaires.
7. Enregistrez le projet et quittez REAPER.
8. Exécutez à nouveau REAPER. Cette fois, les fichiers de configuration sont trouvés et le dernier script affiche ** GAME MASTER / SESSION OCTO READY **.

## Exploration

Vous pouvez maintenant tester la génération automatique de sons. Cliquez simplement sur le bouton gris **Auto-play** (en haut à gauche, juste sous l'indicateur de tabulation "Main"). Il devrait devenir vert, et vous devriez entendre quelque chose jouer. Notez que la sortie est stéréo. Si vous avez une configuration multicanal, vous pouvez facilement passer en octo : cliquez sur le bouton FX de la piste MASTER, et décochez le deuxième plug-in (channels-folder.jsfx).

C'est maintenant le moment de lire le manuel :-(
