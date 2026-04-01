# TP Debugger Thonny NSI Première

Ce fichier HTML est un **TP interactif auto-hébergé** pour enseigner le **débogage Python avec Thonny** aux élèves de **première NSI** (7 séances, 7h). Il utilise **PyScript** pour des éditeurs Python en ligne, sans installation requise.

## Fonctionnalités clés
- **Progression structurée** : Introduction aux bugs → Interface Thonny → Pas-à-pas → Breakpoints → Boucles → Fonctions → Méthode experte.
- **Éditeurs PyScript** : Tests unitaires automatisés ; corrections débloquées après succès ou timer (120s).
- **Thème clair/sombre** : Sauvegarde localStorage.
- **Navigation sticky** : Barre de progression, liens vers 7 séances.
- **Éléments interactifs** : Indices progressifs, encadrets, tableaux de trace, badges d'erreurs. 
## Prérequis
- Navigateur moderne (Chrome/Firefox récents).
- Connexion internet initiale (PyScript 2026.3.1 charge Pyodide ~200MB, puis offline).
- **Thonny installé** pour les exercices pratiques (séances 3-7). 

## Installation & Utilisation
1. Ouvrez `index.html` dans un navigateur.
2. PyScript s'initialise (~1-2min première fois). 
3. Suivez les séances via navigation ; éditeurs prêts à coder.
4. Pour Thonny : copiez codes dans l'IDE, appliquez consignes (breakpoints, variables).

**Offline** : Après chargement initial, fonctionne sans réseau.

## Contenu pédagogique
| Séance | Thème | Durée | Outils |
|--------|-------|-------|--------|
| S1 | Types d'erreurs | 1h | Diagnostic   |
| S2 | Interface Thonny | 1h | Panneaux vars/stack |
| S3 | Pas-à-pas | 1h | Trace exécution |
| S4 | Breakpoints | 1h | Recherche dichotomique |
| S5 | Boucles/conditions | 1h | Variables mal init. |
| S6 | Fonctions/stack | 1h | Step into/over |
| S7 | Méthode 7 étapes | 1h | Éval. complète   |

## Personnalisation
- **CSS variables** : `--bg-main`, `--accent` etc. (thème DarkSATHI).
- **Ajouter exercice** : `<div class="encadre-exercice">` + `<script type="py-editor" data-correction="id">`.
- **Temps déblocage** : `DUREE_MINUTERIE = 120` (JS).
- **Tests** : `assert` dans PyScript ; succès → déblocage correction. 

## Technologies
- **PyScript 2026.3.1** : Python browser-side.
- **Bootstrap 5.3.3** : Responsive.
- **Fonts** : Rubik Dirt (titres), Source Serif 4, JetBrains Mono.
- **localStorage** : Progression persistante. 

## Licence & Crédits
- Créé pour **Lycée Watteau Valenciennes** par **DarkSATHI** (NSI).
- Libre pour usage éducatif NSI ; citez source.
- PyScript : MIT ; Bootstrap : MIT. 

**Contact** : tsautiere@aol.com pour forks/bugs. Mise à jour : Avril 2026.
