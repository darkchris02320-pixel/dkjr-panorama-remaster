# Notice — version Nintendo Switch (homebrew)

Cette version est un **homebrew** (fichier `.nro`). Elle se lance depuis le **Homebrew Menu (hbmenu)** d'une Switch qui fait tourner des homebrews.

## Installation

1. Télécharge [`DKJr-Panorama-Remaster-V3.0-Switch.zip`](../telechargements/DKJr-Panorama-Remaster-V3.0-Switch.zip) et décompresse-le.
2. Copie le dossier `switch` **à la racine** de la carte SD (il se fusionne avec le dossier `switch` déjà présent).
3. Copie la **ROM d'origine** dans le dossier `/switch/DKJrPanorama/` de la carte SD :
   - soit le fichier `gnw_dkjrp.zip` (tel quel) ;
   - soit les deux fichiers `cj-93.program` et `cj-93.melody`.
4. Lance **DK Jr Panorama** depuis le Homebrew Menu.

```
sd:/
└── switch/
    └── DKJrPanorama/
        ├── DKJrPanorama.nro
        └── gnw_dkjrp.zip      ← la ROM, à ajouter toi-même
```

Si la ROM manque, un écran texte l'indique : appuie sur **+** pour quitter, ajoute-la et relance.

Conseil : lance le Homebrew Menu en maintenant **R** au démarrage d'un jeu (et non depuis l'Album), pour que le homebrew ait toute la mémoire disponible.

## Commandes en jeu

| Bouton | Action |
|---|---|
| Croix ou stick gauche | Déplacer Junior |
| A / B | Sauter / attraper |
| X | Game A |
| Y | Game B (difficile) |
| L | Heure |
| R | Alarme |
| ZL | Changer de tableau (seulement ceux débloqués) |
| ZR | Son : symphonique / original (bip) / coupé |
| − | Menu |
| + | Quitter |

## Dans le menu (−)

| Bouton | Action |
|---|---|
| A | Jouer en Game A |
| Y | Jouer en Game B |
| X | ACL (remise à zéro) |
| L | Trophées |
| R | Classement en ligne (QR code) |
| ZL | Défi final (Monde Dark à 980 points) |
| B ou − | Revenir au jeu |

## Sauvegarde

Les réglages, le record et les trophées sont enregistrés dans `/switch/DKJrPanorama/` sur la carte SD.
