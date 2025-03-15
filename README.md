# Pokemon TCG

## Description

Ce projet est une application graphique basée sur PySide6 permettant de simuler l'ouverture de boosters de cartes Pokémon et d'afficher un Pokédex interactif.

## Fonctionnalités

- **Affichage du Pokédex** : Recherche de Pokémon par nom, type, génération ou ID.
- **Ouverture de boosters** : Simulation de l'ouverture d'un booster contenant plusieurs cartes Pokémon.
- **Interface utilisateur** : Navigation fluide entre les différentes scènes via une barre d'outils.

## Installation


### Prérequis

- Python 3.8+
- PySide6
- Requests
- JSON (intégré à Python)

### Étapes d'installation

1. Clonez ce dépôt :
   ```sh
   git clone https://github.com/sltcvtfk/pokemon-tcg-pyside6git
   cd pokemon-tcg
   ```
2. Installez les dépendances :
   ```sh
   pip install -r requirements.txt
   ```

## Utilisation

Lancez l'application avec la commande :

```sh
python main.py
```

## Architecture du Projet

```
📂 pokemon-tcg       
│── 📂 assets              # Dossier des autres fichiers Python
│── 📂 font                # Police d'écriture
│── 📂 img                 # Icônes et images
│── 📂 json                # Fichiers JSON (Pokedex...)
│── 📂 UML                 # Diagrammes de classe
│── 📜 .gitignore          # Fichier ignoré lors des commits
│── 📜 LICENSE             # Fichier de la LICENSE utilisé
│── 📜 README.md           # Documentation       
│── 📜 main.py             # Fichier Python principal
│── 📜 requirements.txt    # Dépendances obligatoires
```

## Technologies utilisées

- **Python** (PySide6, JSON, Requests)
- **PlantUML** (Diagrammes UML pour la conception)
- **GitHub** (Partage du projet)

## Informations supplémentaires

- **pokemon.json** Correction d'un problème avec le nom de certains pokémons
   - [Problème 1 (Pull Request Merged)](https://github.com/Purukitto/pokemon-data.json/pull/27/files)
   - [Problème 2 (Pull Request Open)](https://github.com/Purukitto/pokemon-data.json/pull/28/files)
## Auteurs

- **STAN SALOMON** ([@sltcvtfk](https://github.com/sltcvtfk))
- **EVAN CHAMAND** ([@EvanLeGoat](https://github.com/EvanLeGoat))
- **ROMAIN ARDOISE** ([@ShizuutA](https://github.com/ShizuutA))

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

