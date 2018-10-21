# NetatmoEnergyRoomAppEedomus
Gestion d'un [thermostat Netatmo](https://www.netatmo.com/fr-FR/product/energy/) via la box eedomus

Script cr�� par [@Thibautg16](https://twitter.com/Thibautg16/)

D�pot GIT : [https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/)

Changelog : [https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/CHANGELOG.md](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/CHANGELOG.md)

## Pr�requis 
Vous devez au pr�alable disposer d'un thermostat et d'une vanne Netatmo install�s et configur�s sur l'application Netatmo.

## Installation
### Ajout du p�riph�rique 
Cliquez sur "Configuration" / "Ajouter ou supprimer un pr�riph�rique" / "Store eedomus" / "Netatmo Energie Room" / "Cr�er"

![creer_peripherique](https://user-images.githubusercontent.com/4451322/47272033-e8e9cf00-d57f-11e8-832f-a027da87d1d5.png))


### Configuration du p�riph�rique 
Vous devez renseigner les diff�rents champs suivants:

#### Caract�ristiques :
* [Optionnel] - Nom personnalis� : personnalisation du nom de votre p�riph�rique
* [Optionnel] - Pi�ce : vous devez d�finir dans quelle pi�ce se trouve votre thermostat

#### Configuration :
* [Obligatoire] - Pi�ce : nom de la pi�ce (dans l'application Netatmo) que vous souhaitez ajouter.
* [Obligatoire] - Pi�ce ID : identifiant associ� � cette pi�ce
* [Obligatoire] - Thermostat : s�lectionez votre thermostat dans la liste d�roulante

#### Canaux :
* [Optionnel] - Consigne : choisissez si vous souhaitez cr�er ce module
* [Optionnel] - Mode : choisissez si vous souhaitez cr�er ce module


Plusieurs modules sont cr��s sur votre box eedomus, ainsi que le script Netatmo. 

![netatmo_widget](https://user-images.githubusercontent.com/4451322/47272034-ebe4bf80-d57f-11e8-8043-464066beb265.png)


[![release](https://img.shields.io/github/release/Thibautg16/NetatmoEnergyRoomAppEedomus.svg?style=for-the-badge)](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/releases)
[![license](https://img.shields.io/github/license/Thibautg16/NetatmoEnergyRoomAppEedomus.svg?style=for-the-badge)](https://github.com/Thibautg16/NetatmoEnergyRoomAppEedomus/blob/master/LICENSE)
[![Status: Prod](https://img.shields.io/badge/Status-Prod-green.svg?style=for-the-badge)]()
[![@Thibautg16](https://img.shields.io/badge/twitter-@Thibautg16-blue.svg?style=for-the-badge)](https://twitter.com/Thibautg16)
