# MaintiDoc 

**Equipe ELFATIMI-EZZAHED** : Oumnia EL FATIMI, Kenza EZZAHED (5IAD G1)
Module IA generative multimodale, EMSI 2026, Pr. Mariam CHERRABI

## Objectif du projet
MaintiDoc est un assistant documentaire multimodal et agentique pour un atelier de maintenance d'appareils mobiles. Il repond aux questions des techniciens (texte et photo) avec des citations verifiables (document, page, element), consulte l'historique des equipements via un serveur MCP et prepare des tickets qui ne sont crees qu'apres approbation humaine. Deux familles d'equipements : batteries (BAT-A-01, BAT-B-02) et ecrans (ECR-A-01, ECR-B-02).

## Contenu du ZIP
- `L1_MaintiDoc_ELFATIMI-EZZAHED_Rapport.pdf` : rapport du livrable 1
- `L1_MaintiDoc_ELFATIMI-EZZAHED_LienGitHub.txt` : URL du depot
- `README.md` : ce fichier
- `L1_MaintiDoc_ELFATIMI-EZZAHED_Corpus/` : 40 documents, `inventaire.csv`, `prompts_corpus.md`
  - `documents/famille_1/` : 20 documents batteries (dont 8 fiches en anglais)
  - `documents/famille_2/` : 12 documents ecrans
  - `images/` : 8 photos d'ecrans

## Structure du depot GitHub
```
maintidoc/
├── README.md
├── .gitignore
├── docs/diagrammes/
├── corpus/
│   ├── inventaire.csv
│   ├── prompts_corpus.md
│   ├── documents/famille_1/
│   ├── documents/famille_2/
│   └── images/
└── data/   (jeux de donnees complets, hors corpus)
```
Aucun secret (cle d'API, mot de passe) n'est versionne ; `.gitignore` exclut `.env` et les fichiers de secrets.
