# Créer des raccourcis pour ` Arrêter ` et ` redémarer ` un ordinateur

Par ce qu'on est des Geek... voir des Nerds et qu'on n'a pas l'time.  
Voici un tutoriel pour créer des raccourcis à mettre dans la barre des tâches.  
Parce que trop long ` Démarrer `=>` Marche/Arrêt `=>` Arrêter ` ou  ` Redémarrer `.  
( :computer: Windows 11 [^*] )

## Créer un raccourci pour arrêter l'ordinateur :

0 - cliquer droit sur le bureau  
1 - aller sur le menu déroulant ` Nouveau `  
2 - cliquer sur ` Raccourci `

![image 000 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_000.png)

3 - dans le champ ` Entrez l'emplacement de l'élément : `, écrir : ` shutdown -s -t 0 `  
4 - cliquer sur ` suivant `

![image 001 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_001.png)

5 - dans le champ ` Entrez un nom pour le raccourci : ` entrer le nom souhaité ( exemple : ` Arrêter `, ` Stop ` ... )  
6 - cliquer sur ` Terminer `

![image 002 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_002.png)

7 - faire un clique droit sur le nouveau raccourci  
8 - cliquer sur ` Propriétés `

![image 003 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_003.png)

:warning: __Les quelques étapes suivantes nécessitent d'avoir deux fichiers ` .ico `__  
les icônes du tutoriel sont téléchargeables ici : [eteindre.ico](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/eteindre.ico), [recharger.ico](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/recharger.ico)  
vous pouvez en télécharger d'autres si bon vous semble et les nommer comme vous le souhaitez.  
les mettre dans un dossier simple à retrouver par exemple votre dossier d'image principale ` C:\Users\<votreNomD'utilisateur>\Pictures\Icones `

9 - cliquer sur l'onglet ` Raccourci `  
10 - cliquer sur ` Changer d'icône... `

![image 004 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_004.png)

la fenêtre suivante indique qu'il n'y a aucune icône attenante à l'exécutable cliquer sur ` OK `

![image 005 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_005.png)

cliquer sur ` Parcourir... ` naviguer jusqu'à votre ` .ico ` selectionnez le, puis cliquez sur ` OK `

![image 006 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_006.png)

on peut voir que l'icône est bien changée, puis cliquez sur ` OK `

![image 007 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_007.png)

le raccourci est créé

11 - faire un clique droit sur ce dernier  
12 - cliquer sur ` Épingler au menu démarrer `

![image 008 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_008.png)

rester en clique gauche sur le raccourci pour le glisser dans la barre des tâches

![image 009 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_009.png)

13 - Sélectionner le/les raccourci.s, faire un clique droite dessus la sélection  
14 - cliquer sur ` Supprimer `

![image 010 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_010.png)

Voila le raccourci est créé et intégré dans la barre des tâches et dans le menu Démarrer.

## Créer le raccourci pour redémarer l'ordinateur :

Pour cela il suffit de suivre le tutoriel plus haut ` Créer le raccourci pour arrêter l'ordinateur : `  
en faisant attention sur les étapes ` 3 `, ` 5 ` et ` le chois de l'icône `  
` 3 ` : pour la partie ` Entrez l'emplacement de l'élément ` écrir : ` shutdown -r -t 0 `  
` 5 ` : le nom de l'icône est quant à lui ` Restart `, ` Redémarrer `, ou que sais-je comme vous le souhaitez  
` le chois de l'icône ` : coisir votre icône de redémarage (pour l'exemple : ` recharger.ico ` )

Voila les raccourcis sont créés et intégré dans la barre des tâches et dans le menu Démarrer.

## Bonus :

Dans le menu démarrer les icônes se trouvent à la fin. Autant les mettre en premier pour ne pas avoir à les chercher.  
Pour un ordre plus logique commencer par le raccourci de redémarage.  
15 - clique droite sur le raccourci  
16 - puis cliquer sur ` Placer en début `  
Puis refire les manipulations ` 15 ` et ` 16 ` pour celui d'arrêt.

![image 011 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_011.png)

félicitation vous avez de jolis nouveaux boutons bien pratiques comme le montre la capture d'écran suivante.

![image 012 tuto shortcut Turn Off And Restart](https://raw.githubusercontent.com/itsumiuwu/shortcutTurnOffAndRestart/main/public/img/shutdown_012.png)

:warning: Attention à ne pas faire d'erreur de clique dessus...

:octocat: __Pe@cE__

[^*]: pour Windows 8 ou 10  
il faut écrire ` shutdown /s /t 0 ` et ` shutdown /r /t 0 ` pour l'étape ` 3 `  
pour les boutons respectif ` s => arrêt ` et ` r => redémarage ` et  
lors de l'étape ` 11 ` il faut penser à l'` épingler à la barre des tâches `  
comme dans ` l’écran de démarrage ` ce qui évite la manipulation de gliser dans la barre des tâches
