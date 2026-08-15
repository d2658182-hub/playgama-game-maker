# Playgama Game Maker

Un **skill** qui transforme n'importe quel agent IA en **développeur-penseur expert et
100% autonome** de jeux web pour [Playgama](https://playgama.com).

## Ce que ça fait

L'utilisateur donne un **concept**. L'agent :

1. Propose **3-5 gameplays + 2-3 thèmes/styles** (l'utilisateur choisit).
2. Rédige un **cahier des charges** (`SPEC.md`).
3. Télécharge **100% des assets** (rien généré par code).
4. Implémente en **vanilla JS** sur le template, avec **150-300 niveaux** à progression
   réelle et visible.
5. Conçoit la **dopamine** d'un hit (cadence de récompense, combos, near-miss, jalons,
   « encore une partie ») et le **juice** (musique, particules, confettis, écrans animés).
6. Intègre la **pub Playgama** (interstitielle + rewarded) et le SDK (bridge.storage,
   game_ready, pause/audio).
7. **Vérifie en exécutant** (headless, pixels, zéro erreur, matrice responsive).
8. **Livre** : repo + GitHub Pages + ZIP (index.html à la racine).

Puis il donne les **3 liens** : repo, Pages, ZIP.

## Pourquoi il est fiable

Le skill encode les **leçons tirées de vrais projets terminés** — les pièges qui ont
fait échouer des jeux (sprites jamais dessinés malgré un code sans erreur, données de fin
de partie à zéro, contraste pastel/sur-ciel, économie déséquilibrée, difficulté
exponentielle ingagnable, musique de 0,5 s, shop en texte seul, bandes noires sur desktop,
SDK non défensif…). Un agent qui suit le skill évite ces erreurs **du premier coup**, sans
aller-retour avec l'utilisateur.

## Installation

Copier `SKILL.md` dans le dossier de skills de votre agent (ex. `.agents/skills/playgama-game-maker/SKILL.md`),
puis le charger avec l'outil `skill` au moment de créer un jeu.

## Utilisation

> « Crée un jeu pour Playgama. Concept : [ton idée]. »

L'agent reformule le concept, propose des gameplays + styles, attend ton choix, puis
livre le jeu fini en autonomie totale.

## Template requis

`https://github.com/kingdannydushime1/hypercasual-game-template`
