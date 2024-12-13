# ProjetPYTHON_4AGSI
# Gestion de Tournoi

Ce projet Python permet de gérer un tournoi sous forme de coupe éliminatoire ou de championnat entre des équipes. Les utilisateurs peuvent entrer le nombre d'équipes, ajouter les noms des équipes, saisir les scores des matchs et suivre les résultats jusqu'à la détermination du gagnant.

## Fonctionnalités

- **Saisie des équipes** : Permet à l'utilisateur d'ajouter des équipes et de spécifier le nombre d'équipes (doit être une puissance de 2).
- **Gestion des matchs** : Génère aléatoirement les matchs à chaque tour du tournoi et permet à l'utilisateur de saisir les scores.
- **Calcul des résultats** : Les statistiques sont mises à jour après chaque match, y compris les victoires, les défaites, les nuls, et les points.
- **Prochain tour** : Lorsque tous les matchs d'un tour sont terminés, un nouveau tour est généré avec les équipes gagnantes.
- **Affichage du gagnant** : Lorsque le tournoi est terminé, l'équipe gagnante est affichée.

## Prérequis

- Python 3.x
- Tkinter (pour l'interface graphique)

## Installation

1. Clonez ce repository :
   ```bash
   git clone [https://github.com/username/repository.git](https://github.com/roa212003/ProjetPYTHON_4AGSI.git)
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd repository
   ```

3. Installez les dépendances (si nécessaire) :
   ```bash
   pip install tkinter
   ```

## Utilisation

1. Lancez le script `main.py` pour démarrer l'application :
   ```bash
   python main.py
   ```

2. Suivez les instructions à l'écran pour entrer les équipes, saisir les scores et suivre l'évolution du tournoi.

## Structure du projet

- `main.py` : Le fichier principal qui lance l'application.
- `championnat.py` : Gère la logique du tournoi et des matchs.
- `coupe.py` : Contient la logique de la coupe éliminatoire, y compris la génération des rencontres et la mise à jour des statistiques.
- `equipe.py` : Définit la classe `Equipe`, qui contient les informations relatives aux équipes, telles que le nom, les statistiques de match, etc.

## Contributeurs

- **Dai Han TRAN** - *Développeur principal* - [https://github.com/roa212003]

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE] pour plus de détails.
```

### Explication :

- **Clonez le repository** : Utilisez `git clone` pour récupérer le projet depuis GitHub.
- **Installation** : Installez les bibliothèques nécessaires avec `pip install tkinter` si elles ne sont pas déjà installées.
- **Lancer l'application** : Exécutez `python main.py` pour démarrer l'application et gérer le tournoi.
