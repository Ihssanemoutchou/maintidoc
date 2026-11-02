# MaintiDoc - Livrable 1 : cadrage, corpus et architecture

**Équipe : ICHQARRANE-MOUTCHOU** - Ihssane MOUTCHOU, Aymen ICHQARRANE
Module IA générative multimodale - EMSI 2026 - semaine 1.

## Objectif du projet
MaintiDoc est un assistant documentaire multimodal et agentique pour techniciens de maintenance : il répond à une question (texte + photo) en citant ses sources (document, page, figure), consulte un historique via un outil MCP et prépare un ticket dont la création exige une approbation humaine. Deux familles d'équipements proches, fictives : pompes HydroFlow HF-200 / HF-350 et compresseurs AirCore AC-30 / AC-55.

## Contenu du ZIP
- `L1_MaintiDoc_ICHQARRANE-MOUTCHOU_Rapport.pdf` : rapport (parties 2.1 à 2.6 et annexes)
- `L1_MaintiDoc_ICHQARRANE-MOUTCHOU_LienGitHub.txt` : URL du dépôt GitHub
- `README.md` : ce fichier
- `L1_MaintiDoc_ICHQARRANE-MOUTCHOU_Corpus/` : `inventaire.csv` (47 lignes), `prompts_corpus.md`, `documents/famille_1` (pompes), `documents/famille_2` (compresseurs), `images/` (6 images synthétiques)

## Structure du dépôt
```
maintidoc/
├── README.md
├── .gitignore
├── docs/diagrammes/
└── corpus/ (inventaire.csv, prompts_corpus.md, documents/, images/)
```

Corpus 100 % synthétique (126 pages de PDF), aucune donnée réelle, aucun secret.
