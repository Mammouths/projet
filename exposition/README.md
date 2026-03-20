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
| Vendredi   |    Matis

## Procédure d’ouveture quotidienne

Cette section décrit les étapes nécessaires pour ouvrir l’installation chaque matin.
Elle a pour objectif de garantir une mise en place cohérente, sécuritaire et fidèle au projet, quel que soit le responsable de permanence.
Documentation finale
Étapes pour ouvrir Arbre en Face :
1.	Ouvrir l’ordinateur avec le compte de Mikael.
Regarde le petit papier coller sur l’ordinateur avec le nom d’utilisateur et le mot de passe.
<img width="1663" height="1247" alt="image" src="https://github.com/user-attachments/assets/a0b7dfe9-c703-4db9-a0fd-df9e2640baf8" />
2.	Le projecteur s’ouvre automatiquement quand l’ordinateur est allumé.
(Si le projecteur n’est pas allumé, ouvrir Microsoft Edge et ouvre l’onglet projecteur dans la barre des favoris.
<img width="1247" height="1663" alt="image" src="https://github.com/user-attachments/assets/e65f3370-77f8-441d-851d-4adf10e25b47" />
3.	Vérifier que la toile du projet soit bien tendue.
(Si la toile est mal tendue, utiliser les petites pinces roses pour la tendre davantage.)
<img width="1663" height="1247" alt="image" src="https://github.com/user-attachments/assets/0a12304b-b7ba-42d8-b263-135b09b5e935" />
4.	Ouvrir le Raspberry Pi en appuyant sur le petit bouton en-dessous de la machine.
Sinon, on peut aussi débrancher et rebrancher le câble ethernet.
6.	Demander à l’équipe de Quand les yeux se croisent si les caméras sont allumées.
(Sinon, aller les allumer soi-même.)
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/d7ced079-7437-464b-9ae4-aef6b7824b4c" />
7.	La lumière du projecteur pour la caméra ouvre automatiquement quand l’ordinateur ouvre (si la lumière ne fonctionne pas, aller dans la salle des matrices pour brancher et débrancher le câble ethernet du pi qui contrôle les lumières du studio.)
   <img width="820" height="502" alt="image" src="https://github.com/user-attachments/assets/801e3286-436d-4e07-8045-af2621cb4d12" />
8.	Les haut-parleurs sont déjà allumés.
(S’il y a un problème de son, aller dans les paramètres audios et vérifier que le volume est assez fort.)
9.	Le pi va automatiquement ouvrir le LIDAR.
(Si le LIDAR ne s’ouvre pas automatiquement, regarder dans le script aef-lidar.sh et changer /dev/ttyUSB0 ou /dev/ttyUSB1.)
10.	L’ordinateur va aussi ouvrir automatiquement l’application TouchDesigner.
Aucune modification n’est nécessaire.
<img width="3423" height="1754" alt="image" src="https://github.com/user-attachments/assets/2365f3f6-3d4b-4b1a-8858-4bd5a578986c" />

<img width="1598" height="1265" alt="image" src="https://github.com/user-attachments/assets/cf922131-eb73-4b86-915f-c40aea90f32b" />

(Si le projet ne s’ouvre pas, aller dans l’explorateur de fichiers → Windows (C:) → dossier arbre en face 2 → ouvrir les fichiers TouchDesigner : arbres_en_face2, juste_arbres, touch_visage  pour ouvrir tous les arbres aller dans le dossier arbres : arbre_1-67.17,arbre_1-6-7,arbre_3-4-5,sapin.10,sapin.) 
<img width="620" height="1259" alt="image" src="https://github.com/user-attachments/assets/70f7e1f9-3784-4b0e-a5f8-52a016af3ac6" />
11.	Voir si le LIDAR est calibré dans le TouchDesigner : arbres_en_face2 dans le TouchDesigner aller dans section calibrage il y a deux math un pour le Y et un pour le X.
12.	L’ordinateur va également ouvrir automatiquement REAPER.
<img width="800" height="433" alt="image" src="https://github.com/user-attachments/assets/93226725-9eda-4f1d-b1f7-cb27dbc7b1ac" />
Quand Reaper s’ouvre, attendre environ 5 secondes avant de fermer le message d’évaluation pour que le son soit disponible dans le projet.
(Si Reaper ne s’ouvre pas : explorateur de fichiers → Windows (C:) → dossier arbre en face 2 → ouvrir le fichier reaper_osc.)
     Étapes pour fermer Arbre en Face :
1.	Fermer tous les pages de Touchdesigner.
2.	Fermer la page de REAPER
3.	Fermer l’ordinateur qui ferme automatiquement le projecteur et le projecteur de lumière.
4.	Fermer le pi en appuyant sur le bouton sous celui-ci.




<!-- 
Chaque composante de l’installation est détaillée ci-dessous avec :

- une description,
- les étapes d'ouverture
- des liens utiles,
- des photos de référence.
-->

## Documentation vidéo finale

<!-- Intégration d’une vidéo : méthode 1 (vidéo hébergée sur YouTube, pouvant être non répertoriée publiquement)
-->
<!-- 
[![Description de la vidéo](http://img.youtube.com/vi/ABWCq8j8qys/0.jpg)](http://www.youtube.com/watch?v=ABWCq8j8qys)
