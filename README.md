![Photo de la FDM 2023](https://raw.githubusercontent.com/yoann-darche/FreeStylerConfig/master/ZZ_RESOURCE/FdM.png)

# Fichiers de config de FreeStyler & EsayView3D pour la fête de la musique de Lagardelle sur Lèze 2023

Softaware : FreeStyler Version 4.1.6 : https://www.freestylersupport.com/fsforum/

## Organisation des fichiers

### Config du Show
* répertoire /FS_SCENE : Config du Show

### Config de FreeStyler (Définition du matériel)

Config nécessaire à FreeStyler pour piloter les Lyres et PARs, Config pour EasyView3D (simualtion 3D) et Doc

* répertoire /_MATERIEL :
  
  - ElectroDepot_D20 (Par LED)
  - IbizaLMH350LED (Lyre)
  - KeyLight_KL120 (Par LED)
  - LytorWash7 (Lyre LED)
  - MuvySpotOne (Lyre / Gobo / Led)
  - Sebruanc (Par LED RGBW)
  - Stiarville-AFH-600 (Machine à Boruillard)
 
* Dans le répertoire /_MATERIEL/_ConfigFressStyler il y a le fichier MidiSetting_V404.fms qui correspond à la configuration Midi des Midicontroler AKAI et NOVATION


# Installation:

Pour la config de FreeStyler copier tout les fichiers contenus dans le répertoire /_MATERIEL/_ConfigFressStyler dans le répertoire d'installation de votre FreeStyler.
Si vous souhaitez importer la config du show copier le contenue de /FS_SCENE dans le répertoire d'installation de votre FreeStyler.
