# Scénarisation:

## Scène 1 (base)

| Verbe action |               Condition de déclenchement               | Effet visuel | Effet sonore |               Effet interactif                |
| :----------: | :----------------------------------------------------: | :----------: | :----------: | :-------------------------------------------: |
|    Entrer    | Le visiteur entre dans le champ de vision de la kinect |    les précédentes plantes s'envont tranquillement     |    Musique de fond. Des sons de branches qui cassent, feuilles qui tombent, bruits représentants des plantes qui meurent     | activation du système de détection de visages |

## Scène 2  (Quand il n'y a aucune graine / plante dans le projet)

| Verbe action |            Condition de déclenchement            |                                             Effet visuel                                            |                                                        Effet sonore                                                       |                                                                Effet interactif                                                                |
|:------------:|:------------------------------------------------:|:---------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|
| Toucher      | Le visiteur touche la toile brièvement           | Une graine apparaît et tombe au sol. Les lumières s'illuminent                                      | *pooop*                                                                                                                   | Le Lidar reconnait que la toile a été touchée et envoie la position aux logiciels pour les effets visuels. Et passe en Scène 3 (graine présente)                                      |
| Maintenir    | Le visiteur touche la toile longtemps            | Le visage du visiteur apparaît, s'ouvre et laisse tomber de l'eau au sol. Les lumières s'illuminent | *pooop* quand la tête apparaît. Un son d'eau qui tombe constant et d'eau qui tombe au sol, quand la tête relâche de l'eau | Le lidar reconnaît que la toile est touchée et envoie la position pour faire apparaître la tête et pour qu'elle suive le mouvement du visiteur |
| Partir       | Le visiteur repart (satisfait de son expérience) inactivité | Étant donné qu'il n'y a aucun contact, les plantes/arbres (si présents), commencent à disparaître   | Musique de fond. Des sons de branches qui cassent, feuilles qui tombent, bruits représentants des plantes qui meurent                      | La kinect, continue à détecter les visages                                                                                                     |

## Scène 3 (Graine présente)

| Verbe action |                          Condition de déclenchement                          |                                             Effet visuel                                             |                                                        Effet sonore                                                       |                                                                     Effet interactif                                                                    |
|:------------:|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Toucher      | Le visiteur touche la toile brièvement                                       | Une graine apparaît et tombe au sol. Les lumières s'illuminent                                       | *pooop*                                                                                                                   | Le Lidar reconnait que la toile a été touchée et envoie la position aux logiciels pour les effets visuels                                               |
| Maintenir    | Le visiteur touche la toile longtemps                                        | Le visage du visiteur apparaît, s'ouvre et laisse tomber de l'eau au sol. Les lumières s'illuminent. | *pooop* Quand la tête apparaît. Un son d'eau qui tombe constant et d'eau qui tombe au sol, quand la tête relâche de l'eau | Le lidar reconnaît que la toile est touchée et envoie la position pour faire apparaître la tête et pour qu'elle suive le mouvement du visiteur          |
| Arroser       | Le visiteur fait l'action "maintenir" et verse l'eau sur une plante / graine | La graine grandit et devient une fleur.                                                              | Son de plante qui grandit                                                                                                 | Le projet reconnaît que la graine est arrosée, donc il prend un visage et le met sur la plante qu'il fait pousser et passe en Scène 4 (plante présente) |
| Partir       | Le visiteur repart (satisfait de son expérience) inactivité                            | Étant donné qu'il n'y a aucun contact, les plantes/arbres (si présents), commencent à disparaître    | Musique de fond. Des sons de branches qui cassent, feuilles qui tombent, bruits représentants des plantes qui meurent                      | La kinect, continue à détecter les visages                                                                                                              |

## Scène 4 (Plante présente)

| Verbe action |                      Condition de déclenchement                     |                                             Effet visuel                                             |                                                        Effet sonore                                                       |                                                                Effet interactif                                                                |
|:------------:|:-------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|
| Toucher      | Le visiteur touche la toile brièvement                              | Une graine apparaît et tombe au sol. Les lumières s'illuminent                                       | *pooop*                                                                                                                   | Le Lidar reconnait que la toile a été touchée et envoie la position aux logiciels pour les effets visuels                                      |
| Maintenir    | Le visiteur touche la toile longtemps                               | Le visage du visiteur apparaît, s'ouvre et laisse tomber de l'eau au sol. Les lumières s'illuminent. | *pooop* Quand la tête apparaît. Un son d'eau qui tombe constant et d'eau qui tombe au sol, quand la tête relâche de l'eau | Le lidar reconnaît que la toile est touchée et envoie la position pour faire apparaître la tête et pour qu'elle suive le mouvement du visiteur |
| Arroser       | Le visiteur fait l'action "maintenir" et verse l'eau sur une plante | La plante grandit et devient un arbre a fruits.                                                      | Son de plante qui grandit, sons de feuilles, *pooop* pour les fruits                                                      | Le projet reconnaît que la plante est arrosée, donc il prend un visage et le met sur les fruits et retourne en Scène 1 (base)                  |
| Partir       | Le visiteur repart (satisfait de son expérience) inactivité                   | Étant donné qu'il n'y a aucun contact, les plantes/arbres (si présents), commencent à disparaître    | Musique de fond. Des sons de branches qui cassent, feuilles qui tombent, bruits représentants des plantes qui meurent                      | La kinect, continue à détecter les visages                                                                                                     |

# Équipements:

| **Équipement**              | **Quantité** |
| --------------------------- | :----------: |
| Ordinateur de l'école       |      1       |
| Moniteur                    |      2       |
| Clavier                     |      1       |
| Souris                      |      1       |
| Haut-parleur                |      2       |
| Kinect 2.0                  |      1       |
| Lidar                       |     1-2      |
| Projecteur                  |     1-2      |
| Toile en spendax            |      1       |
| Pince pour la toile         |      40      |
| Trépied                     |      4       |
| bc204                       |      1       |
| Baton LED                   |      10      |
| Multiprise électrique       |      4       |
| Rallonge électrique         |      6       |
| Rouleau de velcro pour fils |      4       |
| Cable Ethernet              |      6       |
| Transmetteur Cat6           |      1       |
| Recepteur Cat6              |      1       |
| Cable HDMI                  |      5       |
| Cable XLR                   |      3       |
| Cable USB                   |      4       |
| Cable Display Port          |      2       |
| Sac de sable                |      12~       |
| Bois                        |      -       |

# Logiciels:

- Touch designer
- Reaper
- Maya
- Max8
- Unity
- Davinci
- Hyper HDR

# Synoptique: ...

![Synoptique](https://github.com/user-attachments/assets/b8510cba-cdbe-4364-be41-10b1d93caa0f)

# Plan Implantation 2D / 3D:

## 3D

![Vue de face 3D](https://github.com/user-attachments/assets/56dc1a7a-17b9-4a2e-9427-1ac0f3a25c73)
![Vue de derrière 3D](https://github.com/user-attachments/assets/5a5e69f1-e229-4f35-ba78-887e7bc78909)

## 2D

![Vue de face 2D](https://github.com/user-attachments/assets/a38288bd-df49-4a2c-a91d-1658fbaf32a2)
![Vue de derrière 2D](https://github.com/user-attachments/assets/3f160456-4831-4b8b-aab7-4b0406dab82d)



# Budget Estimé:

| _Équipement_         |  _Coûts_  |
| -------------------- | :-------: |
| Pince pour la toile  |   60 $    |
| la toile en splandex |   200 $   |
| bois                 |   150 $   |
| **Total**            | **410 $** |
