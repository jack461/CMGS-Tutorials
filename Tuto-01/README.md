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

You need a recent version of **REAPER** (v7.25 or later), from http://reaper.fm/download.php, and **CMGS**, installed as explained in its README (https://github.com/jack461/CMGS#installation): the folders **CMGS-effects** and **CMGS-data** go into the folders *Effects* and *Data* of the REAPER resource folder.

Check first that your sound card is recognized by REAPER (open the menu "Options > Settings...", and check "Audio > Device").

> [!IMPORTANT]
> Some settings may prevent the GameMaster to function correctly. Do check in the "REAPER Preferences" that in "Audio", both "Close audio device when stopped..." options are *not* set, and in "Audio > Playback" that "Run FX when stopped" is set. 

1.  Download the tutorials (Go to https://github.com/jack461/CMGS-Tutorials, click on the green "Code" button, and select "Download ZIP"), unzip the file, and put the folder *GM-Octo-2024* (in *Tuto-01*) anywhere on your system.
2.  Double-click "GM-Octo.RPP".
3.  This runs REAPER, but in the "System Log" of the GamePlayer (track "GAME PLAYER"), you get error messages: the plug-in still uses the paths of the computer where the project was saved, and does not find its initialisation script (*Data/Scripts/GM_mSL_ini.mSL*, the "Profile") nor the samples (*Data/WAVES*).
4.  Drag and drop the "GM-Octo.RPP" file into the window of the GamePlayer. Thanks to this action, the plug-in can determine the location of the needed files.
5.  Save the project and quit REAPER.
6.  Run REAPER again. This time, the Profile and the samples are found, and the last line of the System Log displays ** GAME MASTER / SESSION OCTO READY **.

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

Vous avez besoin d'une version récente de **REAPER** (v7.25 ou ultérieure), téléchargeable depuis http://reaper.fm/download.php, et de **CMGS**, installé comme l'explique son README (https://github.com/jack461/CMGS#installation) : les dossiers **CMGS-effects** et **CMGS-data** vont dans les dossiers *Effects* et *Data* du dossier des ressources de REAPER.

Vérifiez d'abord que votre carte son est reconnue par REAPER (ouvrez le menu "Options > Préférences...", et vérifiez "Audio > Périphérique").

> [!IMPORTANT]
> Certains paramètres peuvent empêcher le GameMaster de fonctionner correctement. Vérifiez dans les "Préférences REAPER" que dans "Audio", les deux options "Fermer le périphérique audio à l'arrêt..." ne sont *pas* définies, et dans "Audio > Lecture" que "Exécuter les effets à l'arrêt" est défini.

1. Téléchargez les tutoriels (allez sur https://github.com/jack461/CMGS-Tutorials, cliquez sur le bouton vert "Code" et sélectionnez "Download ZIP"), décompressez le fichier, et placez le dossier *GM-Octo-2024* (dans *Tuto-01*) n'importe où sur votre système.
2. Double-cliquez sur "GM-Octo.RPP".
3. Cela lance REAPER, mais dans le "System Log" du GamePlayer (piste "GAME PLAYER"), vous obtenez des messages d'erreur : le plug-in utilise encore les chemins de l'ordinateur où le projet a été enregistré, et ne trouve ni son script d'initialisation (*Data/Scripts/GM_mSL_ini.mSL*, le "Profile") ni les échantillons (*Data/WAVES*).
4. Faites glisser et déposez le fichier "GM-Octo.RPP" dans la fenêtre du GamePlayer. Grâce à cette action, le plug-in peut déterminer l'emplacement des fichiers nécessaires.
5. Enregistrez le projet et quittez REAPER.
6. Relancez REAPER. Cette fois, le Profile et les échantillons sont trouvés, et la dernière ligne du "System Log" affiche ** GAME MASTER / SESSION OCTO READY **.

## Exploration

Vous pouvez maintenant tester la génération automatique de sons. Cliquez simplement sur le bouton gris **Auto-play** (en haut à gauche, juste sous l'indicateur de tabulation "Main"). Il devrait devenir vert, et vous devriez entendre quelque chose jouer. Notez que la sortie est stéréo. Si vous avez une configuration multicanal, vous pouvez facilement passer en octo : cliquez sur le bouton FX de la piste MASTER, et décochez le deuxième plug-in (channels-folder.jsfx).

C'est maintenant le moment de lire le manuel :-(
