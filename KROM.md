# Projet IoT

## Nom du groupe: KROM

## Membre du Groupe
Ameni MBTIBAA -- ameni.mtibaa17@gmail.com -- github.com/amenimtibaa <br>
André OBROCHTA -- andreobrochta@gmail.com -- github.com/aobrochta <br>
Lucky RAHERINIAINA -- raheriluc@gmail.com -- github.com/raheriluc <br>
Adlan KADRI -- adlan68@live.fr -- github.com/adlaneKadri <br>

 -----------------------------------------------------------------------------------------------------------------------------------

## Projet 1: transalator

#### idea name: 
a transalator device connected to internet to perform live transalation ! 
here is a link to explain more : https://www.youtube.com/watch?v=WeByuOD8k1c
 
#### framework:
Espressif Systems Audio Development Framework (ESP-ADF): is the official audio development framework for the ESP32 chip.
 
#### hardware:
  -ESP32-LyraT:An open-source development board, supporting Espressif Systems’ ADF and featuring voice wake-up, a wake-up button and an audio player.         Designed for smart speakers and smart-home applications.
    (here is an example that uses this chip : https://github.com/espressif/esp-adf/tree/master/examples/cloud_services/google_translate_device )
#### OR
  -ESP32-LyraTD-MSC: Designed for smart speakers and AI applications. Supports Acoustic Echo Cancellation (AEC), Automatic Speech Recognition (ASR),         Wake-up Interrupt and Voice Interaction.
--> official documentation for both : https://github.com/espressif/esp-adf 
 
useful links: (in this project we can use Google translate API or microsoft transalator: we can use them for free for 12 months )
 
* https://www.google.com/intl/fr/chrome/demos/speech.html
* https://cloud.google.com/text-to-speech/?hl=fr
* https://console.cloud.google.com/freetrial/signup/tos?_ga=2.112472452.-187352321.1547997623&hl=fr
* https://github.com/matheuss/google-translate-api
* https://azure.microsoft.com/fr-fr/services/cognitive-services/translator-speech-api/
* https://azure.microsoft.com/fr-fr/pricing/details/cognitive-services/speech-services/* https://www.youtube.com/watch?v=4swsd1JHxhM
 
------------------------------------------------------------------------------------------------------------------------------------

## Projet 2: Reconnaissance et affichage des panneaux de signalisations 

#### Description

Le projet consiste à ajouter une caméra à notre objet connecté qui sera placé à l'avant d'un véhicule de la 
même manière qu'une 'dashcam'. Celui-ci devra afficher sur un téléphone Android ou IOS, par le biais de Bluetooth, 
les limitations de vitesse actuel. Dans l’idéal il faudrait que l’application prenne une petite partie de l’écran 
afin que l’utilisateur puisse utiliser en même temps une application GPS.
Ainsi il faudra que notre objet connecté 
puisse déterminer si le panneau est adressé à l’utilisateur ou non (par exemple un panneau adressé uniquement aux 
camions ou un panneau qui s’applique uniquement pour une sortie ne devrait pas être pris en compte).
Pour la reconnaissance des panneaux, nous utiliserons la reconnaissance d’image en utilisant le data mining. 
Il existe, certes, déjà un système réalisant la même tâche sur certains GPS, où il est indiqué à l’utilisateur 
la limitation de vitesse, cependant les informations données par le GPS ne sont pas forcément mis à jour. 
Il est fréquent, par exemple sur une voie en travaux, que les limitations indiqués soit erroné.
Notre objet connecté aura l’avantage d’afficher toujours les bonnes limitations.

#### Liste des composants

-ESP32 / Rasbery Pi <br>
-Caméra <br>
-Smartphone (Android ou IOS avec Bluetooth)
