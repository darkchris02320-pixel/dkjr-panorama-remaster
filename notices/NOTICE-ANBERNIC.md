# Notice — version Anbernic (RG35XXSP et consoles PortMaster)

Testée sur **Anbernic RG35XXSP**. Elle fonctionne sur les consoles qui ont **PortMaster** (Knulli, muOS, ROCKNIX…), car elle utilise le moteur LÖVE fourni par PortMaster.

## Installation

1. Télécharge [`DKJr-Panorama-Remaster-V3.0-Anbernic-RG35XXSP.zip`](../telechargements/DKJr-Panorama-Remaster-V3.0-Anbernic-RG35XXSP.zip) et décompresse-le sur ton ordinateur.
2. Branche la carte SD de la console sur l'ordinateur.
3. Copie **le fichier `DK Jr Panorama.sh`** et **le dossier `dkjrpanorama`** dans le dossier des ports de la carte SD :
   `ROMS/PORTS` ou `roms/ports` selon le système.
4. Copie la **ROM d'origine** dans le dossier `dkjrpanorama/gamedata/` :
   - soit le fichier `gnw_dkjrp.zip` (tel quel, sans le décompresser) ;
   - soit les deux fichiers `cj-93.program` et `cj-93.melody`.
5. Remets la carte SD dans la console : le jeu apparaît dans la liste des **Ports**.

Le résultat doit ressembler à ça :

```
ports/
├── DK Jr Panorama.sh
└── dkjrpanorama/
    ├── dkjrpanorama.gptk
    └── gamedata/
        ├── gnw_dkjrp.zip      ← la ROM, à ajouter toi-même
        ├── main.lua
        ├── assets/
        └── …
```

Si la ROM manque, le jeu affiche « ROM d'origine introuvable » : vérifie qu'elle est bien dans `gamedata`.

## Commandes

| Bouton | Action |
|---|---|
| Croix | Déplacer Junior |
| A / B | Sauter / attraper |
| START | Game A |
| SELECT | Game B |
| X | Heure |
| Y | Alarme |
| L1 | Changer de tableau (seulement ceux débloqués) |
| R1 | Son : original (bip) / symphonique HD |
| L2 | Trophées ; L2 une 2ᵉ fois : QR code du classement en ligne |
| R2 | Défi final : Monde Dark, la partie commence à 980 points |
| SELECT + START | Quitter |

## Tableaux à débloquer (meilleur score)

Original, Remake HD et Origine embellie sont ouverts dès le début.
Automne 150 · Halloween 300 · Hiver 450 · Noël 600 · Monde Dark 800.

## Vraie fin

Dans le Monde Dark à 980 points, récupère le lance-pierre puis attrape un parapluie : la vidéo de fin se lance (A ou START pour la passer).

## Classement en ligne

À la fin d'une partie, le score s'affiche avec un QR code. Scanne-le avec ton téléphone pour enregistrer ton score et tes trophées dans le classement en ligne (le même que sur PC).

## En cas de problème

- **« Cannot load game at path »** : le dossier `dkjrpanorama` n'est pas au bon endroit. Il doit être à côté du fichier `DK Jr Panorama.sh`, dans `ports`.
- **Pas de vidéo de fin** : mets à jour PortMaster (le moteur LÖVE doit être récent).
