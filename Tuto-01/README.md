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

1.  Download the folder *GM-OCTO-2024* from this directory, and install it anywhere on your system.
2.  *Remove* the file **Effects**
3.  Copy the **CMGS** folder into the project directory, and rename it **Effects**.
4.  Double-click "GM-Octo.RPP"
5.  This runs REAPER, but in the "System Log" of the plug-in, you get a lot of error messages, like "ERR: 2405 can't compile ..."
6.  Drag and drop the "GM-Octo.RPP" file in the "GameMaster" window. From this action, the plug-in can determine the location of the needed files.
7.  Save the project and quit REAPER.
8.  Run REAPER again. This time, the configuration files are found, and the last script displays ** GAME MASTER / SESSION OCTO READY **.

## Exploring

You can now test the automatic generation of sounds. Just click the grey **Auto-play** (upper left, just under the "Main" tabulation indicator). Il should turn green, and start playing something. Note that the output is stereo. If you have a multi-channel configuration, you can switch easily to octo: click the FX button on the MASTER Track, and uncheck the second plug-in (channels-folder.jsfx). 
