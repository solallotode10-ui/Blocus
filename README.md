# ✊ BLOCUS 3D

Jeu 3D de défense de barricade, jouable dans le navigateur (PC et mobile).

- 🕹️ Joystick de déplacement + joystick de visée des mortiers (style Brawl Stars)
- 🎆 Mortiers d’artifice réalistes (trajectoire en arc, gerbes d’étincelles, sons)
- 🏪 Magasin : soins, boucliers, masque, barricade… et alliés (manifestants, artificiers, medics)
- 👮 CRS blindés et vagues de choc qui s’intensifient avec tes achats
- 🌇 → ☀️ La lumière passe du soir à l’après-midi au fil des vagues
- 🏆 Record sauvegardé et bouton « Défier mes potes »

## Jouer en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (ex. `blocus-3d`).
2. Envoie `index.html` et `README.md` à la racine du dépôt.
3. Va dans **Settings → Pages**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après 1 à 2 minutes, le jeu est en ligne sur `https://TON-PSEUDO.github.io/blocus-3d/`.

Pour tester en local, ouvre simplement `index.html` dans ton navigateur (connexion internet nécessaire pour charger Three.js depuis cdnjs).

## Commandes

| Action | Mobile | Clavier |
|---|---|---|
| Se déplacer | Stick gauche | WASD / flèches |
| Viser et tirer un mortier | Stick rouge (relâcher = tirer, tap = visée auto) | Espace (visée auto) |
| Masque | Bouton 😷 | M |
| Magasin | Bouton 🏪 | — |

Technologies : HTML, JavaScript, [Three.js r128](https://threejs.org/). Un seul fichier, aucune installation.
