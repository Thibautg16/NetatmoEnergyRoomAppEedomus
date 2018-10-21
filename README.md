# NetatmoEnergyRoomAppEedomus
Gestion d'un [thermostat Netatmo](https://www.netatmo.com/fr-FR/product/energy/) via la box eedomus

Script créé par [@Thibautg16](https://twitter.com/Thibautg16/)

Dépot GIT : [https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/)

Changelog : [https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/CHANGELOG.md](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/CHANGELOG.md)

## Prérequis 
Vous devez au préalable disposer d'un thermostat et d'une vanne Netatmo installés et configurés sur l'application Netatmo.

## Installation
### Ajout du périphérique 
Cliquez sur "Configuration" / "Ajouter ou supprimer un prériphérique" / "Store eedomus" / "Netatmo Energie Room" / "Créer"

![creer_peripherique](https://user-images.githubusercontent.com/4451322/47272033-e8e9cf00-d57f-11e8-832f-a027da87d1d5.png))


### Configuration du périphérique 
Vous devez renseigner les différents champs suivants:

#### Caractéristiques :
* [Optionnel] - Nom personnalisé : personnalisation du nom de votre périphérique
* [Optionnel] - Pièce : vous devez définir dans quelle pièce se trouve votre thermostat

#### Configuration :
* [Obligatoire] - Pièce : nom de la pièce (dans l'application Netatmo) que vous souhaitez ajouter.
* [Obligatoire] - Pièce ID : identifiant associé à cette pièce
* [Obligatoire] - Thermostat : sélectionez votre thermostat dans la liste déroulante

#### Canaux :
* [Optionnel] - Consigne : choisissez si vous souhaitez créer ce module
* [Optionnel] - Mode : choisissez si vous souhaitez créer ce module


Plusieurs modules sont créés sur votre box eedomus, ainsi que le script Netatmo. 

![netatmo_widget](https://user-images.githubusercontent.com/4451322/47272034-ebe4bf80-d57f-11e8-8043-464066beb265.png)


[![release](https://img.shields.io/github/release/Thibautg16/NetatmoEnergyRoomAppEedomus.svg?style=for-the-badge)](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/releases)
[![license](https://img.shields.io/github/license/Thibautg16/NetatmoEnergyRoomAppEedomus.svg?style=for-the-badge)](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/LICENSE)
[![Status: Prod](https://img.shields.io/badge/Status-Prod-green.svg?style=for-the-badge)]()
[![@Thibautg16](https://img.shields.io/badge/twitter-@Thibautg16-blue.svg?style=for-the-badge)](https://twitter.com/Thibautg16)
