---
layout: default
---

# Administrer Garden  
## Les commandes de base 

`Console` => screen -x mc-survival

`Stop` => systemctl stop mcserver@survival

`Restart` => systemctl restart mcserver@survival 

`Start` => systemctl start mcserver@survival 
 
## Les fichiers  

Le serveur est lancé par le root dans le répertoire `/srv/mc/survival`   
  
## Installer un plugin

Il suffit de le télécharger dans `/srv/mc/minecraft/plugins/`   
Vous pouvez l'héberger sur [transfer.sh](http://transfer.sh)    
Et le télécharger avec `wget url`  
Il est nécessaire de connaitre les commandes de base linux.  
Un redémarrage est nécessaire pour lancer un plugin  

## Commandes de base linux  

`mv fichier.tmp texte.tmp` => Renommer un fichier (fichier.tmp => texte.tmp)  

`mv fichier.tmp dossier/` => Déplacer fichier.tmp dans dossier  

`cd chemin` => Se déplacer

`ls` => Afficher le contenu du dossier

`rm` => Supprimer un fichier
## Les logs  
Les logs sont dans le dossier `/srv/mc/minecraft/logs`  
## Mettre a jour le serveur
Connectez vous avec le client ftp sur le vps et remplacer le server.jar avec celui voulu
Vérifiez régulièrement la version avec `/ver`  

## Bot Discord

-Allumer le bot

`Accéder` au screen du bot => screen -r discord
cd /srv/discord
node index.js
`Sortir du screen` => Ctrl+A+D

## Contact

Vous pouvez me contacter sur discord, via mon adresse email ou mon numéro de téléphone
















(Ps: Tu crains)