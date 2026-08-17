# Playgama Game Maker

Un **skill** qui transforme n'importe quel agent IA en **développeur de jeux expert et
100% autonome** pour [Playgama](https://playgama.com). Court et net : des exigences, des
gardes-fous et des checklists — pour que l'agent ne se perde pas.

## Ce que ça fait

L'utilisateur donne un **concept**. L'agent :

1. Propose **3-5 gameplays + 2-3 styles + la dimension (2D / 2.5D / 3D) justifiée**
   (l'utilisateur choisit).
2. Rédige le **cahier des charges** (`SPEC.md`) : dopamine, échelle de profondeur,
   niveaux, mondes, assets.
3. Télécharge **100% des assets** (rien généré par code).
4. Implémente avec **150-300 niveaux réellement DIFFÉRENTS** (mécanique qui évolue) et
   des **mondes aux assets distincts** (jamais de re-teinte).
5. Conçoit la **dopamine** (cadence, combos, near-miss, jalons, « encore une partie ») +
   le **juice** (game feel, musique, particules, confettis, écrans animés).
6. Intègre la **pub Playgama** (interstitielle + rewarded) et le SDK (bridge.storage,
   game_ready, pause/audio).
7. **Vérifie en exécutant avec preuves** (headless, pixels, confettis mesurés, mondes
   comparés, placement regardé, zéro erreur).
8. **Livre** : repo + GitHub Pages + ZIP — et donne les **3 liens**.

## Pourquoi il est fiable

Le skill encode les **leçons de vrais projets terminés** — les pièges qui font échouer
les jeux : sprites jamais dessinés malgré un code sans erreur, données de fin à zéro,
niveaux tous identiques, mondes re-teintés au lieu d'être distincts, cliché « ciel +
nuages », placement d'assets flottants, contraste pastel, économie déséquilibrée,
difficulté exponentielle, musique de 0,5 s, shop en texte seul, bandes noires sur
desktop, SDK non défensif… Un agent qui suit le skill évite ces erreurs **du premier
coup**.

## Installation

Copier `SKILL.md` dans le dossier de skills de votre agent
(ex. `.agents/skills/playgama-game-maker/SKILL.md`), puis le charger avec l'outil
`skill` au moment de créer un jeu.

## Utilisation

> « Crée un jeu pour Playgama. Concept : [ton idée]. »

L'agent reformule le concept, propose gameplays + styles + dimension, attend ton choix,
puis livre le jeu fini en autonomie totale.

## Template requis

`https://github.com/kingdannydushime1/hypercasual-game-template`
