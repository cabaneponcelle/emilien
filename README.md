# Tempête Royale 🌀

Un simulateur de **battle royale** en 3D, jouable directement dans le navigateur, très inspiré de Fortnite :
100 joueurs sautent du bus de combat au-dessus d'une île… sauf que les 99 autres sont des **bots** pilotés par une IA.

## Lancer le jeu

Double-clique sur `index.html` (Chrome, Edge ou Firefox récents). Une connexion internet est nécessaire au
premier lancement pour charger la bibliothèque 3D (Three.js) depuis un CDN.

Options dans l'URL :
- `index.html?bots=30` : moins de bots (de 1 à 99)

## Contrôles

| Touche | Action |
| --- | --- |
| ZQSD / WASD | Se déplacer |
| Souris | Viser |
| Clic gauche | Tirer / frapper / construire / se soigner |
| Clic droit | Viser (lunette pour le sniper) |
| Espace | Sauter / sauter du bus |
| Maj | Sprinter |
| 1 | Pioche |
| 2 à 6 | Armes et soins (ou molette) |
| E | Ramasser / ouvrir un coffre |
| R | Recharger |
| F / C / V | Construire un mur / un sol / une rampe |
| G | Changer de matériau (bois, pierre, métal) |
| M | Carte de l'île |
| Échap | Pause |

## Ce qu'il y a dans le jeu

- **Bus de combat** qui traverse l'île, chute libre (regarde vers le bas pour plonger) et planeur automatique.
- **Île générée aléatoirement** à chaque partie : collines, montagnes, plages, forêts, rochers, et 9 lieux-dits
  (Tours Penchées, Dépôt Poussiéreux, Chalet Solitaire, Parc Plaisant…) avec des maisons à étages.
- **Armes avec raretés** (commun → légendaire) : fusil d'assaut, fusil à pompe, mitraillette, pistolet, fusil de
  précision avec lunette. Tirs à la tête, dispersion, rechargement, munitions par type.
- **Soins** : bandages, trousses de soins, petites potions et potions de bouclier.
- **Coffres** dorés et butin au sol, ramassage automatique des munitions et matériaux.
- **Récolte** à la pioche (arbres, rochers, voitures, murs) et **construction** sur une grille : murs, sols,
  rampes, en bois, pierre ou métal. Tout le décor est destructible.
- **La tempête** qui se resserre en 7 phases et blesse ceux qui restent dehors.
- **99 bots** qui choisissent où atterrir, fouillent les maisons, ouvrent les coffres, changent d'arme selon la
  distance, se soignent, fuient la tempête, cassent les murs à la pioche, et construisent pour se protéger
  quand on leur tire dessus.
- Fil des éliminations, mini-carte, grande carte, chiffres de dégâts, indicateurs de direction des tirs,
  mode spectateur après l'élimination et écran **#1 Victoire Royale**.
