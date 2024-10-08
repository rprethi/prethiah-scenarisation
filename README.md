# Luminatura par Prethiah Rajaratnam

***Luminatura***, où la lumière et la nature s'entrelacent pour éclairer l'esprit à travers la magie des lanternes.

## Concept
---

***Luminatura*** est une installation immersive alliant art et technologie, où des lanternes illuminent votre parcours et des vignes décorent l'espace, créant une atmosphère accueillante. En touchant une plaque métallique, la chaleur corporelle de l'utilisateur déclenche une réponse lumineuse et sonore, illustrant le potentiel de transformation que chacun détient sur son environnement.

### Mise en contexte

À l'entrée de l'installation, le visiteur est accueilli par la douce lumière des lanternes suspendues et les vignes décoratives qui créent une ambiance de tranquillité.

En touchant la plaque, le visiteur déclenche une lumière douce et chaleureuse, accompagnée de sons apaisants de la nature. Ce moment intime lui permet de réfléchir à ses propres expériences de transformation et d’éveiller des émotions profondes, soulignant le pouvoir de l'art et de la technologie pour toucher l’âme humaine.

---

![rajaratnam_prethiah_schema](https://github.com/user-attachments/assets/59e14f05-a5aa-404f-8eca-2d7f221f3de5)

---

## Objectif
---

L'œuvre vise à provoquer une expérience immersive où l'interaction avec des lanternes emblématiques déclenche une transformation lumineuse et sonore, nous invitant à réfléchir sur notre pouvoir d'influencer et d'illuminer notre environnement.

## Motivations
---

### Motivation créative

Mon œuvre ***Luminatura*** s’inspire des profondeurs symboliques des lanternes, des vignes et des métaux, chacun porteur d’un sens profond et d’une histoire unique. À travers cette création, je cherche à établir un dialogue entre ces éléments, illuminant leur interconnexion et la manière dont ils reflètent l’expérience humaine.

### Motivation personnelle

Dans ***Luminatura***, ma motivation personnelle réside dans le désir d'explorer comment la lumière intérieure peut guider chaque individu à travers ses propres ombres, créant une connexion entre le spectateur et son esprit. En intégrant des éléments inspirés de la culture japonaise, je cherche à répondre à un besoin de sérénité et de contemplation dans notre monde contemporain, tout en suscitant une réflexion sur notre relation avec la nature et la technologie.

## Scénario interactif
---
```mermaid
    graph TD;
    ModeVeille[Mode veille] --> AmbianceBase[Lumière et audio de base jouent];
    AmbianceBase --> Interaction[Interaction avec une plaque ?];
    
    %% Interaction Utilisateur 1
    Interaction -- Oui --> Plaque1[Utilisateur 1 touche la plaque 1];
    Plaque1 --> Capteur1[Capteur de chaleur U1 activé];
    
    Capteur1 --> Lumière1[Lumière modifiée pour U1];
    Capteur1 --> Audio1[Audio modifié pour U1];
    
    Lumière1 --> Reste1[Utilisateur 1 reste ?];
    Audio1 --> Reste1;
    
    Reste1 -- Oui --> PlusEffetsLumière1[Effets lumières augmentés pour U1];
    Reste1 -- Oui --> PlusEffetsAudio1[Effets audio augmentés pour U1];
    Reste1 -- Non --> RetourVeille1[Retour au mode veille pour U1];

    %% Interaction Utilisateur 2
    Interaction -- Oui --> Plaque2[Utilisateur 2 touche la plaque 2];
    Plaque2 --> Capteur2[Capteur de chaleur U2 activé];
    
    Capteur2 --> Lumière2[Lumière harmonisée avec U1 pour U2];
    Capteur2 --> Audio2[Audio harmonisé avec U1 pour U2];
    
    Lumière2 --> Reste2[Utilisateur 2 reste ?];
    Audio2 --> Reste2;
    
    Reste2 -- Oui --> PlusEffetsLumière2[Effets lumières augmentés en harmonie avec U1];
    Reste2 -- Oui --> PlusEffetsAudio2[Effets audio augmentés en harmonie avec U1];
    Reste2 -- Non --> RetourVeille2[Retour au mode veille pour U2];

    %% Retour au mode veille global
    Interaction -- Non --> AmbianceBase;
```


## Planche d'ambiances visuelles
---

![rajaratnam_prethiah_planche](https://github.com/user-attachments/assets/5b0aea75-db03-44a2-8884-eec7bfba42be)

---

## Planche d'ambiances sonores
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/NMbSnI1UWFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/-ytgGCetzXs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/igS5kbMBJ1c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/W6xjxjpHJQ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/nE_XAauwu1I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wxflcCxqebU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Références artistiques
---

### L'esthétique et le design

| Couleur                                 | Signification                     |
| --------------------------------------- | --------------------------------- |
| <font color="#A9BCD0">Bleu pâle</font>  | Paix et introspection             |
| <font color="#28587B">Bleu foncé</font> | Vérité et tranquillité            |
| <font color="#EDDEA4">Jaune</font>      | Chaleur, lumière et joie de vivre |
| <font color="#E9B44C">Orange</font>     | Activité et émotion               |
| <font color="#B97375">Rouge</font>      | Énergie et intensité              |

L'esthétique de ***Luminatura*** repose sur une harmonie entre lumière et ombre, évoquant une atmosphère de sérénité et de contemplation. 

Le design intègre également des éléments contemporains, tels que des structures métalliques et des dispositifs technologiques, pour offrir une expérience immersive qui invite les spectateurs à interagir avec leur environnement lumineux et sonore.


### Choix de références visuelles

***Luminatura*** s'inspire des lanternes captivantes de ***Forest of Resonating Lamps - One Stroke***, où chaque lumière interagit avec son environnement, créant une atmosphère magique. De plus, l'œuvre ***Pulse Room*** de Rafael Lozano-Hemmer enrichit notre concept en intégrant une dimension sonore réactive, renforçant ainsi l'expérience immersive de Luminatura.

### Choix de références sonores

Pour ***Luminatura***, les choix d'ambiances sonores se concentrent sur l'harmonie entre lumière et son, créant ainsi une expérience immersive et poétique. Les sons naturels, tels que les bruits de la forêt et les murmures d'eau, renforcent la connexion avec la nature, tandis que les mélodies douces et les vibrations réactives des lanternes évoquent une atmosphère envoûtante et interactive.

## Support médiatique

| Type de médias              | Intégration                                  |
| --------------------------- | -------------------------------------------- |
| Lumière                     | Ampoules LED et lanternes en polycarbonate   |
| Audio                       | Sons ambiants et effets sonores synchronisés |
| Capteurs                    | Capteurs de chaleur                          |
| Contrôle et synchronisation | Contrôle du son et des lumières              |


## Matériaux
---

#### Matériaux et Composants

- Vignes Artificielles
- Ampoules LED 
- Plaques métalliques 
- Lanternes en polycarbonate
- Régulateur de tension
- Câbles
- Fil de cuivre ou d'acier
- Éléments de fixation
- Fils de prototypage
  Ordinateur
- Haut-parleurs

#### Capteurs et Évaluation

| Capteur de chaleur                                        | Composants                   |
| --------------------------------------------------------- | ---------------------------- |
| Cartes d'évaluation pour microcontrôleurs embarqués (MCU) | Arduino A000066              |
| Résistances traversantes                                  | YAGEO CFR-25JB-52-3M6        |
| Cartes d'évaluation de capteurs                           | Adafruit Industries LLC 1374 |

#### Support en Métal

| Support en métal pour la plaque métallique | Composants                          |
| ------------------------------------------ | ----------------------------------- |
| Tube en acier ou en aluminium              | Structure principale du « stand »   |
| Base plate                                 | Assurer la stabilité du « stand »   |
| Vis et boulons                             | Assembler et garantir la durabilité |

## Logiciel
---
  
| Logiciel  | Technique                                                 |
| --------- | --------------------------------------------------------- |
| Reaper    | Montage sonore (base)                                     |
| Arduino   | Capteur de chaleur et connecter les composants ensemble   |
| Pure Data | Modifier des paramètres audio en réponse à des événements |
| QLC+      | Création des scènes lumineuses                            |
| Plugdata  | Modifier la couleur des lumières                          |

| Système de communication | Logiciel | Interaction         |
| ------------------------ | -------- | ------------------- |
| Protocole MIDI           | LoopMidi | QLC+ et Plugdata    |
| Protocole DMX            | QLC+     | Lumiere et logiciel |

## Sources
---

[Arduino - Capteur de chaleur](https://www.digikey.ca/en/maker/tutorials/2021/how-to-add-capacitive-sensing-to-any-arduino-project?msockid=1d6850aaf64a65b4178e445ff73e64f3)
