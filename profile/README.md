# Projet SETAF

## Projet

Le volet numérique du projet SETAF entend construire un corpus de textes de l’époque de la Réforme, comprenant les textes écrits et réédités par Guillaume Farel (1489-1565) et son cercle. Le corpus primaire comprend les ouvrages publiés par les imprimeurs Pierre de Vingle et Jean Michel, actifs respectivement dans les années 1525-1535 et 1538-1545, entre Genève et Neuchâtel. Ce corpus permettra de développer des outils d’analyse textuelle spécifiques pour la Réforme francophone et des modèles pour le traitement automatique des imprimés du XVIe siècle en langue française. Une importante dimension numérique est donc prévue pour la réalisation de ce projet, avec l'océrisation de nombre d’imprimés d’une part et l’exploitation computationnelle de ces données d’autre part.

GitHub du projet : https://github.com/SETAFDH 

Site du projet : https://www.unige.ch/setaf


## Financeur

Ce projet est financé par le Fonds national suisse (FNS). Numéro de projet : [205056](https://data.snf.ch/grants/grant/205056).


## Données TEI et OCR

Le dépôt [TEI-SETAF](https://github.com/SETAFDH/TEI-SETAF) comprend les textes en TEI des données OCR contenues dans les dépôts suivants :
- [HTR-SETAF-Pierre-de-Vingle](https://github.com/SETAFDH/HTR-SETAF-Pierre-de-Vingle) (caractères gothiques)
- [HTR-SETAF-Jean-Michel](https://github.com/SETAFDH/HTR-SETAF-Jean-Michel) (caractères gothiques)
- [HTR-SETAF-LesFaictzJCH](https://github.com/SETAFDH/HTR-SETAF-LesFaictzJCH) (caractères gothiques)
  
Le dépôt [TEI-Varia-Malingre](https://github.com/SETAFDH/TEI-Varia-Malingre) comprend les textes en TEI des données OCR contenues dans les dépôts suivants :
- [HTR-Varia-Malingre-romain](https://github.com/SETAFDH/HTR-Varia-Malingre-romain) (caractères romains)
- [HTR-Varia-Malingre-gothique](https://github.com/SETAFDH/HTR-Varia-Malingre-gothique) (caractères gothiques)

Les données OCR se trouvent au chemin ‘./data//.xml‘ et sont au format ALTO. Elles suivent les normes de segmentation de [SegmOnto](https://segmonto.github.io) et sont cataloguées sur [HTR-United](https://htr-united.github.io). Les fichiers sont corrigés manuellement : la qualité de la segmentation des pages et de la transcription produite par l'OCR est indiqué dans le tableau CSV de chaque dépôt ("gold" ou "en cours").

Le contrôle de la transcription produite par l'OCR se base sur un guide redigé par l'équipe : Solfrini et al., _Guide de transcription pour les imprimés français du XVIe siècle en caractères gothiques_, Version A, 2023, https://hal.science/hal-04281804.

Notre modèle d'OCR, CATMuS Gothic Print, est disponible en ligne : https://zenodo.org/records/10599911.


## Infrastructure

Les données pour l'OCR sont produites à l'aide de l’instance genevoise [FoNDUE](https://www.unige.ch/lettres/humanites-numeriques/recherche/projets-de-la-chaire/fondue) d'[eScriptorium](https://gitlab.com/scripta/escriptorium).

Les calculs sont effectués à l'Université de Genève en utilisant le [service HPC](https://www.unige.ch/eresearch/fr/services/hpc/).


## Citer le projet 

Sonia Solfrini, Geneviève Gross, Brigitte Roux, Nathalie Szczech et Daniela Solfaroli Camillocci, _SETAF (S’en tenir aux 'Faits de Jésus Christ et du pape'). Les imprimés évangéliques romands et les pratiques de communication religieuse à l’époque de la Réforme_, Genève, université de Genève, 2023, https://www.unige.ch/setaf.

```bibtex
@misc{solfrini_SETAF_2023,
  author={Solfrini, Sonia and Gross, Geneviève and Roux, Brigitte and Szczech, Nathalie and Solfaroli Camillocci, Daniela},
  title={SETAF (S’en tenir aux 'Faits de Jésus Christ et du pape'). Les imprimés évangéliques romands et les pratiques de communication religieuse à l’époque de la Réforme},
  address={Genève},
  publisher={université de Genève},
  year={2023},
  url={https://www.unige.ch/setaf},
  note={numéro de projet FNS : 205056},
}
```

