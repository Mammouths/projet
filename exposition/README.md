# Exposition

Cette section documente l'exposition publique du projet.

## Permanence 

Ce tableau indique les responsables quotidiens de l’exposition, désignés par chaque équipe pour assurer la permanence pendant la semaine.

| Jour       | Responsable |
|------------|-------------|
| Lundi      |    Alexandre   |
| Mardi      |    Mikael  |
| Mercredi   |    Rafael  |
| Jeudi      |    Mathieu  |
| Vendredi   |    Toute l'équipe

## Procédure d’ouveture quotidienne

Cette section décrit les étapes nécessaires pour ouvrir l’installation chaque matin.
Elle a pour objectif de garantir une mise en place cohérente, sécuritaire et fidèle au projet, quel que soit le responsable de permanence.

## Documentation finale

### Étapes pour ouvrir Arbre en Face:

#### 1.	Ouvrir l’ordinateur avec le compte de Mikael.
Regarder le petit papier coller sur l’ordinateur avec le nom d’utilisateur et le mot de passe. Le projecteur s’ouvre automatiquement quand l’ordinateur est allumé. (Si le projecteur n’est pas allumé, ouvrir Microsoft Edge et ouvrir l’onglet projecteur dans la barre des favoris. Sinon, allumer le projecteur directement avec le bouton POWER sur celui-ci)

![Appuyer sur le bouton POWER du projecteur si celui-ci ne s'ouvre pas avec l'ordinateur](https://github.com/user-attachments/assets/a0b7dfe9-c703-4db9-a0fd-df9e2640baf8)

#### 2.	Ouvrir le Raspberry Pi en appuyant sur le petit bouton sous la machine. Sinon, on peut aussi débrancher et rebrancher le câble ethernet.

![Le bouton POWER du Raspberry Pi sous celui-ci](https://github.com/user-attachments/assets/0a12304b-b7ba-42d8-b263-135b09b5e935)

#### 3.	Demander à l’équipe de Quand les yeux se croisent d'allumer leurs caméras.

#### 4.	Les lumières ellipsoidales pour les photos s'allument automatiquement quand l’ordinateur s'allume (si les lumières ne fonctionnent pas, aller dans la salle des matrices pour débrancher et rebrancher le câble ethernet du pi qui contrôle les lumières du studio.)

![Le Raspberry Pi qui contrôle les lumières du studio](https://github.com/user-attachments/assets/d7ced079-7437-464b-9ae4-aef6b7824b4c)

#### 5.	Les hauts-parleurs sont déjà allumés.
(S’il y a un problème de son, aller dans les paramètres audios et vérifier que le volume est assez fort.)

![Paramètres de sons de l'ordinateur](https://github.com/user-attachments/assets/801e3286-436d-4e07-8045-af2621cb4d12)

#### 6.	Le pi va automatiquement ouvrir le LIDAR.
(Si le LIDAR ne s’ouvre pas automatiquement, regarder dans le script aef-lidar.sh et changer /dev/ttyUSB0 ou /dev/ttyUSB1.)

#### 7.	L’ordinateur va aussi ouvrir automatiquement l’application Touch Designer.
Aucune modification n’est nécessaire. (Si le projet ne s’ouvre pas, aller dans l’explorateur de fichiers → Windows (C:) → dossier arbre en face 2 → ouvrir les fichiers TouchDesigner : arbres_en_face2, juste_arbres, touch_visage  pour ouvrir tous les arbres aller dans le dossier arbres : arbre_1-67.17,arbre_1-6-7,arbre_3-4-5,sapin.10,sapin.)

![Les fichiers du projet](https://github.com/user-attachments/assets/2365f3f6-3d4b-4b1a-8858-4bd5a578986c)

![Les fichiers Touch Designer](https://github.com/user-attachments/assets/cf922131-eb73-4b86-915f-c40aea90f32b)

#### 8.	Voir si le LIDAR est calibré dans le TouchDesigner : arbres_en_face2 dans le TouchDesigner aller dans section calibrage il y a deux math un pour le Y et un pour le X.

![Ce qui doit être modifié pour la calibration](https://github.com/user-attachments/assets/70f7e1f9-3784-4b0e-a5f8-52a016af3ac6)

#### 9.	L’ordinateur va également ouvrir automatiquement REAPER. 
Quand Reaper s’ouvre, attendre environ 5 secondes avant de fermer le message d’évaluation pour que le son soit disponible dans le projet. (Si Reaper ne s’ouvre pas : explorateur de fichiers → Windows (C:) → dossier arbre en face 2 → ouvrir le fichier reaper_osc.)

![Le fichier Reaper](https://github.com/user-attachments/assets/93226725-9eda-4f1d-b1f7-cb27dbc7b1ac)

#### 10. Allumer l'appareil photo installé sur le cadre. Vérifier que le focus est bien placé dans le milieu du portique du studio.


### Étapes pour fermer Arbre en Face :

1.	Fermer toutes les pages de Touch Designer.
2.	Fermer la page de REAPER
3.	Fermer l’ordinateur qui ferme automatiquement le projecteur et le projecteur de lumière.
4.	Fermer le pi en appuyant sur le bouton sous celui-ci.
5.	Fermer l'appareil photo dans le cadre de l'exposition.


## Documentation vidéo finale

[![Vidéo finale](https://github.com/user-attachments/assets/e0118d1a-be5c-4887-963e-50fc414113d2)](https://youtu.be/Qbv81vm1Bek)
<!-- Intégration d’une vidéo : méthode 1 (vidéo hébergée sur YouTube, pouvant être non répertoriée publiquement)
-->
<!-- 
[![Description de la vidéo](http://img.youtube.com/vi/ABWCq8j8qys/0.jpg)](http://www.youtube.com/watch?v=ABWCq8j8qys)
