fais le readme:
11:44

Je vais créer le README pour le projet calculator en suivant les exigences du TD.

Voici le README avec tous les éléments demandés dans le TD : nom du projet, description, instructions d'installation des dépendances, d'exécution de l'application et des tests.
Readme
Document · MD 


Claude est une IA et peut faire des erreurs. Veuillez vérifier les réponses.
Readme · MD
# Calculator

Une calculatrice simple en Python permettant d'effectuer des opérations arithmétiques de base.

## Description

Ce projet est une calculatrice développée dans le cadre d'un TD DevOps. Elle permet de réaliser des opérations mathématiques courantes et sert de support pour apprendre les bonnes pratiques de collaboration Git, les tests unitaires et l'intégration continue.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/<votre-username>/calculator.git
   cd calculator
   ```

2. Créez un environnement virtuel :
   ```bash
   python -m venv venv
   ```

3. Activez l'environnement virtuel :
   - Linux/Mac : `source venv/bin/activate`
   - Windows : `venv\Scripts\activate.bat`

4. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

```bash
python calculator.py
```

## Tests

Pour exécuter les tests unitaires avec le rapport de couverture :

```bash
python -m coverage run -m unittest tests/test_calculator.py
```

Pour afficher le rapport de couverture :

```bash
coverage report -m
```

## Contributeurs

- Dev A
- Dev B

