# xastir-nwsdata-fr
Donnees pour les bulletins de vigilance meteo Francais

Ce paquet fournit les ressources nécessaires à l'affichage
des bulletins de vigilance météo sur Xastir.

Les données sont issues du [serveur qui gère les données de vigilance pour la France](https://wxsvr-fr.eu/shp.html).

## Installation
Télécharger le fichier .deb en choisissant la dernière version sur [https://github.com/dscp46/xastir-nwsdata-fr/releases](https://github.com/dscp46/xastir-nwsdata-fr/releases).
En ligne de commande, aller dans le dossier où est ce fichier, puis l'installer avec
```bash
sudo dpkg -i  xastir-nwsdata-fr_1.1-1_all.deb
```

## Comment construire le paquet

Normalement, le paquet `build-essential` devrait suffire pour créer ce paquet.

```
git clone https://github.com/dscp46/xastir-nwsdata-fr/
cd xastir-nwsdata-fr
dpkg-buildpackage -us -uc
```
