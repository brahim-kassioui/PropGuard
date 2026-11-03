# PropGuard
<!-- Titre principal du projet -->

Rule-enforcement and execution layer for prop-firm and own-capital trading.
<!-- Description courte : couche d'application des règles et d'exécution pour le trading prop firm et compte propre -->

## What this project is
<!-- Section : ce qu'est ce projet -->

A program that sits between a trading signal and the broker. It blocks any order
that would violate either the prop firm's rules or the trader's personal rules.
<!-- Un programme qui se place entre le signal de trading et le broker. Il bloque toute
     transaction qui violerait soit les règles du prop firm, soit les règles personnelles du trader. -->

## What this project is not
<!-- Section : ce que ce projet n'est PAS -->

- Not a profit predictor
<!-- Pas un prédicteur de profit -->

- Not a strategy optimizer
<!-- Pas un optimiseur de stratégie -->

- Not a backtesting platform (though it logs enough to analyze)
<!-- Pas une plateforme de backtesting (mais il journalise assez pour analyser) -->

## Current status
<!-- Section : état d'avancement actuel -->

- Phase 0: Environment setup — DONE
<!-- Phase 0 : Configuration de l'environnement — TERMINÉE -->

- Phase 1: Backtest the indicator — IN PROGRESS
<!-- Phase 1 : Backtest de l'indicateur — EN COURS -->

- Phase 2: Decision gate — PENDING
<!-- Phase 2 : Porte de décision (decision gate) — EN ATTENTE -->

- Phase 3: Python rule engine — PENDING
<!-- Phase 3 : Moteur de règles Python — EN ATTENTE -->

- Phase 4: MQL5 rule engine — PENDING
<!-- Phase 4 : Moteur de règles MQL5 — EN ATTENTE -->

- Phase 5: Log-only demo — PENDING
<!-- Phase 5 : Démo en mode journalisation seule (sans ordres) — EN ATTENTE -->

- Phase 6: Demo trading — PENDING
<!-- Phase 6 : Trading en démo — EN ATTENTE -->

- Phase 7: Live evaluation — PENDING
<!-- Phase 7 : Évaluation en live — EN ATTENTE -->

## Quick start
<!-- Section : démarrage rapide -->

See `docs/ARCHITECTURE.md` for full setup instructions.
<!-- Voir docs/ARCHITECTURE.md pour les instructions complètes d'installation -->

## Free tools only
<!-- Section : uniquement des outils gratuits -->

- MetaTrader 5 (free)
<!-- MetaTrader 5 (gratuit) -->

- Python 3.10+ (free)
<!-- Python 3.10+ (gratuit) -->

- Git (free)
<!-- Git (gratuit) -->

- VS Code (free)
<!-- VS Code (gratuit) -->

No paid subscriptions, no paid APIs, no cloud services required.
<!-- Aucun abonnement payant, aucune API payante, aucun service cloud requis -->