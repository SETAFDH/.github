# Projet SETAF

## Projet

La constitution d’un corpus numérique des imprimés évangéliques romands s’inscrit dans le cadre du projet SETAF qui entend mener une ample investigation historique à caractère pluridisciplinaire à partir d’un ouvrage singulier émanant du milieu éditorial du « groupe de Neuchâtel », réuni autour du réformateur Guillaume Farel à partir des années 1530 : les *Faits de Jésus Christ et du pape*. Une importante dimension numérique est prévue pour la réalisation de ce projet, avec l'océrisation de nombre d’imprimés d’une part et l’exploitation computationnelle de ces données d’autre part.

GitHub du projet : https://github.com/SETAFDH 

Site du projet : https://www.unige.ch/setaf


## Financeur

Ce projet est financé par le Fonds national suisse (FNS). Numéro de projet : 205056 (https://data.snf.ch/grants/grant/205056).


## Données TEI

Les données TEI se trouvent dans les dépôts suivants :
- https://github.com/SETAFDH/TEI-SETAF
- https://github.com/SETAFDH/TEI-Malingre


## Données OCR

Les données OCR se trouvent dans les dépôts suivants :
- https://github.com/SETAFDH/HTR-SETAF-Pierre-de-Vingle
- https://github.com/SETAFDH/HTR-SETAF-Jean-Michel
- https://github.com/SETAFDH/HTR-SETAF-LesFaictzJCH
- https://github.com/SETAFDH/OCR-Malingre


Les données se trouvent au chemin ‘./data//.xml‘ et sont au format ALTO. Elles suivent les normes de segmentation SegmOnto (https://segmonto.github.io) et sont cataloguées sur HTR-United (https://htr-united.github.io). Les fichiers sont corrigés manuellement : la qualité de la segmentation des pages et de la transcription produite par l'OCR est indiqué dans le tableau CSV de chaque dépôt ("gold" ou "en cours").

Le contrôle de la transcription produite par l'OCR se base sur un guide redigé par l'équipe : Solfrini et al., Guide de transcription pour les imprimés français du XVIe siècle en caractères gothiques, Version A, 2023, https://hal.science/hal-04281804.


## Infrastructure

Les données pour l'OCR sont produites à l'aide de l’instance genevoise FoNDUE (https://www.unige.ch/lettres/humanites-numeriques/recherche/projets-de-la-chaire/fondue) d'eScriptorium (https://gitlab.com/scripta/escriptorium).

Les calculs sont effectués à l'Université de Genève en utilisant le service Baobab HPC : https://www.unige.ch/eresearch/fr/services/hpc/.


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

