# fortunes-kaamelott
Petite base de citations kaamelottesques pour nos terminaux.

Merci à [sin0light](https://github.com/sin0light/api-kaamelott) pour sa bdd adaptée ici pour fortunes !

* Pour l'utiliser il suffit d'installer fortunes :
`sudo apt install fortunes`
* Si l'on souhaites ne voir que les citations de Kaamelott, supprimer les autres via :
`sudo rm /usr/share/games/fortunes/*`
* Pour importer les citations kaamelottesques, faire :
```
wget -O fortunes-kaamelott https://raw.githubusercontent.com/methatronc/fortunes-kaamelott/main/fortunes-kaamelott
wget -O fortunes-kaamelott.dat https://github.com/methatronc/fortunes-kaamelott/raw/main/fortunes-kaamelott.dat
sudo mv fortunes-kaamelott* /usr/share/games/fortunes/
```
