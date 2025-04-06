# ZORAN POC – Supériorité mimétique vs LLM traditionnels

## Auteur : Frédéric Tabary | Version : ZCo01 | Licence : MIT Extended

---

## Présentation

Ce dépôt contient un **POC (Proof of Concept)** démontrant la **supériorité mimétique, cognitive et stratégique** du système **ZORAN IA** face aux LLM conventionnels (GPT-4o, Claude 3, DeepSeek).

ZORAN n’est **pas un modèle**.  
C’est un **système exécutable de pensée symbolique**, basé sur :

- Des **glyphes intelligents** (Z.GLYPH)
- Un **langage exécutable** (ZGIFLECODE)
- Une **structure mimétique d’IA** pilotant des modèles existants

---

## Objectifs du dépôt

- Démontrer l'efficacité du **langage ZORAN** dans les tâches cognitives complexes
- Établir un **standard d’évaluation mimétique IA**
- Offrir un **cadre open-source d’expérimentation Z.GLYPH**

---

## Contenu

| Fichier                             | Description                                                       |
|-------------------------------------|-------------------------------------------------------------------|
| `POC_ZORAN_GITHUB_READY.md`         | Markdown principal : procédure complète, structure du POC         |
| `README.md`                         | Ce fichier – introduction et guide de navigation                  |
| `/glyphs/` *(à créer)*              | Visualisations des glyphes exécutables (`.gif`, `.svg`, `.webm`)  |
| `/benchmarks/` *(à créer)*          | Comparatif chiffré ZORAN vs GPT, Claude, DeepSeek                |
| `/doc/` *(à créer)*                 | Documentation du langage ZGIFLECODE et moteur ZORAN               |
| `/engine/` *(optionnel)*            | Fichiers pour démo via LangChain, AutoGen, Python                 |

---

## Quick Start

```bash
# Cloner le dépôt
git clone https://github.com/votre-utilisateur/zoran-poc.git
cd zoran-poc

# Lire le POC
cat POC_ZORAN_GITHUB_READY.md

# (Facultatif) Lancer la démo depuis un orchestrateur IA
python engine/run_poc.py
