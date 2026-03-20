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
![OSC in du lidar dans touch designer](https://github.com/user-attachments/assets/01e12618-973c-4460-95bf-c840c4ec778b)

#### Mardi

- J'ai séparé les données reçues en 2 tableaux, un pour les données X et un autre pour les données Y. J'ai ensuite mis les différents L-systems dans TouchDesigner et attribué une position à chaque arbre selon leur emplacement sur la toile. J'ai aussi établi une connexion dans le code entre les données du Lidar et les positions des arbres, puis mis en place une détection de collision entre les données X du Lidar et la position de chaque arbre.
- ![separer X et Y](https://github.com/user-attachments/assets/39cd6cd0-dcbf-42a2-98cc-680e4a79bb60)
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

- Désensablage de l’ancienne toile, début de la fabrication du cadre pour la nouvelle, puis installation de pin rose sur le nouveau cadre afin de soutenir la toile
- ![pine rose](https://github.com/user-attachments/assets/d1118bde-30e2-419b-b9d7-21b617a78184)

#### Mercredi

-Installation de la nouvelle toile sur le cadre, réorganisation du câblage du projecteur, de l’ordinateur, de la caméra et des haut-parleurs, puis séparation du TouchDesigner des photos des interacteurs dans un nouveau fichier .toe

- ![cable manegement](https://github.com/user-attachments/assets/6236e8dc-87ed-4cdc-bf93-2819d9746eae)
- ![Nouvelle toile](https://github.com/user-attachments/assets/0826b97a-da84-4247-93b6-dee5bd8c2e8b)

-
- ![fichier du projet](https://github.com/user-attachments/assets/9596775c-89fc-4a80-9b77-1f9aaa85cb8b)

#### Jeudi

- Modification des coordonnées du LiDAR pour l’adapter à la nouvelle toile, resserrage de celle-ci sur le cadre, puis récupération de l’adresse IP du projecteur afin de le contrôler depuis l’ordinateur
- ![projecteur](https://github.com/user-attachments/assets/c15e04ca-ccf4-4607-9bf6-9c9d336ae7bd)

#### Vendredi

- Journée de congée

### Semaine 5

#### Lundi

- Démontage du faux mur derrière la toile, ajustement de son emplacement et réalignement du projecteur pour assurer une projection complète, puis optimisation du câblage pour le rendre plus discret ainsi que réorganisation du fichier TouchDesigner
- ![organisation du touchDesigner](https://github.com/user-attachments/assets/3aa40e8d-bbda-4e33-8986-5a8bd70d06ba)
- ![projectuer](https://github.com/user-attachments/assets/45d33bc0-130b-4190-9d3c-1fffe07e274f)

#### Mardi

- Intégration du nouveau système des arbres permettant un déplacement plus facile et une modification rapide des données, configuration du lancement automatique du projet au démarrage de Windows ainsi que de l’activation du projecteur à l’ouverture de TouchDesigner, amélioration du système de capture des interacteurs par ajustement de la luminosité des images, et ajout d’un système de calibration suivant en temps réel les mouvements sur la toile
- ![ouverture et fermeture du projecteur](https://github.com/user-attachments/assets/01609980-cb95-4cac-b6d6-226ac3ffcd19)
- ![Systême pour modifier les arbres](https://github.com/user-attachments/assets/eee94912-ef10-4956-9491-a347c1563582) -<img width="708" height="232" alt="fichier" src="https://github.com/user-attachments/assets/2743b314-156c-4ece-8e05-290f622e1f4e" />

#### Mercredi

- Ajout de l’arbre numéro 2 (le sapin) dans TouchDesigner, ajustement des éclairages pour les différents rendus des arbres, intégration d’un système de rotation pour les interacteurs, et mise en place d’un calcul permettant de déterminer si une personne interagit à gauche ou à droite d’un arbre selon sa zone de tolérance

#### Jeudi

- Finalisation du système de rotation des arbres dans TouchDesigner

#### Vendredi

- journée de congé

### Semaine 6

#### Lundi

- Jounée de congé

#### Mardi

- Préparation pour la journée pour la visite des étudiants ansi que faire sortir le son via osc
- ![photo d'équipe](https://github.com/user-attachments/assets/6694fe4e-8500-42c5-ac27-981fa96f8c94)

- ![note midi-OSC](https://github.com/user-attachments/assets/2e93ad1a-63e8-40ef-8d0d-84d71b12aaba)

#### Mercredi!

- Ajout d’un système affichant le titre de l’œuvre lorsqu’aucun participant n’est présent
- ![titre dans l'oeuvre](https://github.com/user-attachments/assets/3fe3fb73-b07c-4a7f-99a0-2507a4f10d1f)

#### Jeudi

- Mise en place d’un système permettant aux arbres de pousser n’importe où sur la toile
- ![arbre pousse n'importe-ou](https://github.com/user-attachments/assets/ed5c27b9-553f-4f43-b6f7-d3178ac04ebe)

#### Vendredi

- Jounée de congé

### Semaine 6.5

#### Lundi

- Jounée de congé

#### Mardi

- Resserage de la toile en ajustant les pines roses

#### Mercredi

- Ajout d’un bruit (noise) au contact de la toile pour améliorer la calibration
- ![noise](https://github.com/user-attachments/assets/8386897a-3036-42f8-a2ba-c94b530d421b)

#### Jeudi

- jounée de congé

#### Vendredi

- jounée de congé

### Semaine 7

#### Lundi

- journée de congé

#### Mardi

- J'ai séparé tous les arbres dans différents TouchDesigner. Ils se parlent entre eux avec des TouchIn/TouchOut et se transmettent le rendu de chacun avec des SpoutIn/SpoutOut. Les arbres sont séparés pour maximiser la performance du projet en utilisant plusieurs cœurs de l'ordinateur, ayant chacun son propre Touch. Par la suite, un TouchDesigner final prend chacun des rendus et les ajoute par-dessus le fond, pour ensuite être projeté sur la toile
  ![out finale](https://github.com/user-attachments/assets/dad417c1-7c37-4ede-829d-be68930e1480)
  ![arbre separe en Touch](https://github.com/user-attachments/assets/8491e8fe-d463-4a60-a09f-129756222e36)

#### Mercredi

- Transfert des données sur tous les TouchDesigner afin de recalibrer en cas de déplacement du projecteur
- ![valeur max du lidar](https://github.com/user-attachments/assets/c48cd636-1612-4751-aabb-36620bb2b05a)

#### Jeudi

- Ajout de nouveaux nuages contenant des visages et un arc-en-ciel, et configuration pour que chaque arbre émette son son au bon moment lors de sa croissance
![reaper](https://github.com/user-attachments/assets/28ca512c-912a-4cfd-9811-b8148fb9f6e4)

#### Vendredi

- Ajout d’un son stéréo correspondant à la position de l’interacteur lors de la pousse, ainsi que du son de joie des plantes, et recalibrage de la toile via le contact
- ![stereo](https://github.com/user-attachments/assets/0587b4d9-a699-4394-b73a-25442252f270)

### Semaine 8

#### Lundi

- journée de présentation

#### Mardi

- journée de présentation
- Vernissage

#### Mercredi

- journée de présentation

#### Jeudi

- Création de la vidéo de documentation
- ![documentation](https://github.com/user-attachments/assets/bf787441-d18e-4709-bb86-2c267aae7d6b)

#### Vendredi
