 # Mikael Arseneau

![](mikael_vignette.webp)

## Planification

Cette section, complétée lors de la première semaine, présente les tâches individuelles **hebdomadaires** prévues.

<!--
- Planification sur 9 semaines (8 semaines de cours et 1 semaine de rattrapage) présentant les tâches individuelles hebdomadaires prévues.
- Au moins une tâche par semaine. Les tâches ne peuvent pas se répéter et doivent être suffisamment précises.
- Les tâches doivent être cohérentes avec celles des autres membres de l’équipe et avec le concept du projet, et être mises à jour en continu.
- Critères :
    - Intention et concept clairs
    - Description approfondie de la conception sonore et visuelle
    - Planification détaillée du contenu multimédia à intégrer
    - Planification technique rigoureuse
-->

### Semaine 1

- Création et modification du GitHub
- Création du dossier de touchDesigner
<!-- 
- Tâche
- Tâche
-->

### Semaine 2

- Recevoir les données du lidar et les transmettres a touchDesigner par OSC
- Séparer les données en X et Y dans un tableau
- Calibration du lidar avec toile et le projet
- Commencer le système d'innodation (détection du nombre de touché)
- Terminer le GitHub
<!-- 
- Tâche
- Tâche
-->

### Semaine 3

- Déterminer l'emplacements des arbres dans le projet pour faciliter l'intéraction
- Calibration du lidar avec toile et le projet
- Creation du site web de l'exposition
- Incorporer le système d'innodation
- Commencement du systeme du soleil
- Terminer le système d'innodation
- Avoir mis les textures sur les arbres
<!-- 
- Tâche
- Tâche
-->

### Semaine 4

- Corriger les bugs lier a la calibration du lidar
- Modifications du site web de l'exposition
- Terminer le système du soleil au complet
- Essayer plein d'intéractions pour trouver des problèmes
<!-- 
- Tâche
- Tâche
-->

### Semaine 5
- Optimisation du code et correction de problèmes
- Modifications du site web de l'exposition
- Optimiser des aniamitons du soleil pour la rendre fluide
- Essayer plein d'intéractions pour trouver des problèmes
<!-- 
- Tâche
- Tâche
-->

### Semaine 6
- Optimisation du code et correction de problèmes
- Optimiser des aniamitons du soleil pour la rendre fluide
- Essayer plein d'intéractions pour trouver des problèmes
<!-- 
- Tâche
- Tâche
-->

### Semaine 6.5
- Optimisation du code et correction de problèmes
- Essayer plein d'intéractions pour trouver des problèmes
<!-- 
- Tâche
- Tâche
-->

### Semaine 7
- Optimisation du code et correction de problèmes
- Essayer plein d'intéractions pour trouver des problèmes
<!-- 
- Tâche
- Tâche
-->

### Semaine 8

- Présentation du projet
<!-- 
- Tâche
- Tâche
-->


## Journal de bord

Cette section, complétée **quotidiennement** pendant l’exécution du projet, documente le travail individuel réellement réalisé chaque jour.

<!--
- Une entrée par jour sur 8 semaines (8 semaines à partir de la semaine 2).
   - Un total d'au moins 40 entrées uniques!
- Chaque jour :
    - Documentstion visuelle et/ou sonore du travail effectué
    - Lien vers les billets GitHub résolus
- Démarche rigoureuse de validation de la qualité
- Démonstration d'autonomie.
- Exécution technique précise et complète.
- Évaluation réfléchie de la contribution individuelle au travail d’équipe.
-->

### Semaine 2

#### Lundi
-Aujourd'hui, j'ai avancé sur le GitHub, tout en travaillant sur la réception des données Lidar dans TouchDesigner via OSC pour les intégrer et les traiter en temps réel.
![oscin_lidar](https://github.com/user-attachments/assets/01e12618-973c-4460-95bf-c840c4ec778b)

#### Mardi
- J'ai séparé les données reçues en 2 tableaux, un pour les données X et un autre pour les données Y. J'ai ensuite mis les différents L-systems dans TouchDesigner et attribué une position à chaque arbre selon leur emplacement sur la toile. J'ai aussi établi une connexion dans le code entre les données du Lidar et les positions des arbres, puis mis en place une détection de collision entre les données X du Lidar et la position de chaque arbre.
- ![separer-X_Y](https://github.com/user-attachments/assets/39cd6cd0-dcbf-42a2-98cc-680e4a79bb60)
- ![position des arbres](https://github.com/user-attachments/assets/7536ca5b-cf84-474d-a6a9-2c99d3a62c85)


#### Mercredi
- J'ai créé un système d'inondation lors de six contacts sur la toile, ainsi qu'un soleil qui se déplace de droite à gauche et qui affiche un message dans la console si lorsqu'il partage le même X que l'un des arbres.
- ![soleil qui tue les arbres](https://github.com/user-attachments/assets/0f6f2633-af8d-4cd4-97ef-64220239ac18)


#### Jeudi
-J'ai fait en sorte que le soleil tue les arbres selon leur position, créé l'animation de l'inondation, amélioré l'animation du soleil et amélioré la détection du Lidar sur les arbres.
- ![animation du soleil](https://github.com/user-attachments/assets/b0c27e63-4070-4c27-a2db-cd9ef0ff7137)


#### Vendredi
- J'ai importé les nouveaux L-systems(arbres) dans TouchDesigner et créé un système de capture de photo des interacteurs qui sauvegarde automatiquement les photos dans un dossier.
- ![code qui prend des photos](https://github.com/user-attachments/assets/1cda17e9-bfc8-43f7-a197-570b9ec9e3ee)
- ![galerie de photo](https://github.com/user-attachments/assets/1710c7d3-4d27-4048-a458-84a3bd1ac588)


### Semaine 3

#### Lundi
- J'ai implémenté tous les L-systems(arbres) dans un render, ajouté le background dans TouchDesigner et séparé les différentes parties du background pour créer un effet de parallaxe

#### Mardi
- Implémenter les photos recue et les mettres comme texture sur les L-systems(arbres) et amélioration de l'animation du soleil pour rendre plus fluide
- ![texture des faces](https://github.com/user-attachments/assets/5909ac9a-2e87-4c61-8f95-69ce5fba0927)
#### Mercredi
- J'ai optimisé le code en supprimant les parties inutiles et testé toutes les interactions en vue de la journée des portes ouvertes.
#### Jeudi
- J'ai fait en sorte que les visages changent au contact du soleil, analysé les comportements des interacteurs sur la toile et mis du tape noir sur les lumières des haut-parleurs derrière.
- ![Voir les intéractions](https://github.com/user-attachments/assets/59fba6d3-c4c4-4ef0-bf31-50b8d2651d18)


#### Vendredi
- journée de congé

### Semaine 4

#### Lundi
- Journée de congé 

#### Mardi
- Creation du frame pour tenir la toile
- Commencement du désensabalage du l'ancienne toile
- Commencement de mettre des pine rose pour tenir la toile
- ![pine rose](https://github.com/user-attachments/assets/d1118bde-30e2-419b-b9d7-21b617a78184)



#### Mercredi

- Installer la nouvelle toile sur le frame
- ![Nouvelle toile](https://github.com/user-attachments/assets/0826b97a-da84-4247-93b6-dee5bd8c2e8b)
- Refaire le cable managenement du projecteur
- Refaire le cable managenement de l'ordinateur
- Refaire le cable managenement de la caméra
- Refaire le cable managenement des haut-parleurs
- ![cable manegement](https://github.com/user-attachments/assets/6236e8dc-87ed-4cdc-bf93-2819d9746eae)

- Separer le touchDesigner de captures des intéracteur dans un nouveau fichier toe
- ![fichier du projet](https://github.com/user-attachments/assets/9596775c-89fc-4a80-9b77-1f9aaa85cb8b)

#### Jeudi
- Changer les coordonées du lidar pour la nouvelle toile
- Reserrage de la nouvelle toile sur le frame
- Aller chercher l'adresse IP du projecteur pour l'ouvrir de l'ordinateur
#### Vendredi
- Journée de congée

### Semaine 5

#### Lundi
- Enlever le faux murs qui était derrière la toile
- Bouger l'emplacement de la toile
- Replacer le projecteur pour projeter sur toute la toile
- - ![projectuer](https://github.com/user-attachments/assets/45d33bc0-130b-4190-9d3c-1fffe07e274f)
- Rendre le cable management plus beau en cachant les fils
- Organisation du ficher TouchDesign
- ![organisation du touchDesigner](https://github.com/user-attachments/assets/3aa40e8d-bbda-4e33-8986-5a8bd70d06ba)


#### Mardi
-<img width="708" height="232" alt="{165A2618-CDE4-4636-B938-A7ED7862A787}" src="https://github.com/user-attachments/assets/2743b314-156c-4ece-8e05-290f622e1f4e" />
- Ajouter le nouveau système des arbres qui permet de les déplacement plus facilement et de pouvoir changer ses données rapidement
- ![Systême pour modifier les arbres](https://github.com/user-attachments/assets/eee94912-ef10-4956-9491-a347c1563582)

- Faire en sorte que le projet ouvre lors de l'ouverture de Windows
- Faire en sorte que le projecteur ouvre lors de l'ouverture du projet touchdesigner
- Amélioration du système de capture des intéracteurs en ajoutant plus de luminosité si la photo est trop foncé
- Ajouter un système de calibration qui suit en direct les mouvement des intéracteurs sur la toile
- ![ouverture et fermeture du projecteur](https://github.com/user-attachments/assets/01609980-cb95-4cac-b6d6-226ac3ffcd19)

#### Mercredi
- Ajout de l'arbre numéro 2 dans le touchDesigner(le sapin)
- Modification des lumières pour les différents render des arbres dans touchDesigner
- Ajouter un système de rotation pour les intéracteurs 
- Calculer si une personne touche a gauche ou a droite d'un arbre dans sa zone de tolérance
#### Jeudi

#### Vendredi
- journée de congé

### Semaine 6

#### Lundi
- jounée de congé

#### Mardi
- Préparation pour la journée pour la visite des étudiants
- Faire sortir le son via osc
#### Mercredi
- Ajout d'un système pour affiche le tittre de l'oeuvre si aucun participant
#### Jeudi
- Faire en sorte que les arbres peuvent pousser n'imporent ou sur la toile
#### Vendredi
- jounée de congé
### Semaine 6.5

#### Lundi
- jounée de congé
#### Mardi
- resserage de la toile
#### Mercredi
- ajout d'un noise au contact de la toile pour la calibration
#### Jeudi
- jounée de congé
#### Vendredi
- jounée de congé
### Semaine 7

#### Lundi
- journée de congé

#### Mardi
- J'ai séparé tous les arbres dans différents TouchDesigner. Ils se parlent entre eux avec des TouchIn/TouchOut et se transmettent le rendu de chacun avec des SpoutIn/SpoutOut. Les arbres sont séparés pour maximiser la performance du projet en utilisant plusieurs cœurs de l'ordinateur, ayant chacun son propre Touch. Par la suite, un TouchDesigner final prend chacun des rendus et les ajoute par-dessus le fond, pour ensuite être projeté sur la toile

#### Mercredi

#### Jeudi

#### Vendredi

### Semaine 8

#### Lundi

#### Mardi

#### Mercredi

#### Jeudi

#### Vendredi
                                                   
