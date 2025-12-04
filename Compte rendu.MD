Rapport d'Analyse : Prédiction de la Valeur Future du Bitcoin
Résumé Exécutif
Ce rapport présente une analyse approfondie de l'évolution du prix du Bitcoin sur la période 2013-2021, dans une perspective d'ingénierie industrielle. L'objectif principal est d'évaluer les tendances historiques pour établir des bases de prédiction de la valeur future de cette cryptomonnaie.

1. Introduction
1.1 Contexte
Le Bitcoin, créé en 2009, est devenu la cryptomonnaie la plus importante et la plus étudiée au monde. Sa volatilité exceptionnelle en fait un sujet d'étude particulièrement intéressant pour l'analyse prédictive.
1.2 Objectifs de l'étude

Visualiser l'évolution historique du prix du Bitcoin (2013-2021)
Identifier les tendances et patterns de croissance
Établir des bases méthodologiques pour la prédiction future

1.3 Méthodologie

Période d'analyse : Avril 2013 - Juillet 2021
Nombre d'observations : 2 991 enregistrements journaliers
Outils utilisés : R, bibliothèques tidyverse, ggplot2, lubridate, scales


2. Caractéristiques des Données
2.1 Structure du Dataset
Le dataset comprend 10 variables pour chaque jour de cotation :
VariableDescriptionTypeSNoNuméro séquentielNumériqueNameNom (Bitcoin)TexteSymbolSymbole (BTC)TexteDateDate d'observationDate/HeureHighPrix maximum journalierNumériqueLowPrix minimum journalierNumériqueOpenPrix d'ouvertureNumériqueClosePrix de clôtureNumériqueVolumeVolume de transactionsNumériqueMarketcapCapitalisation boursièreNumérique
2.2 Extrait des Données (6 premières observations)

