# Projet Aleph

Aleph est un projet universitaire réalisé dans le cadre du BUT Informatique à l'IUT de Lannion.
En équipe, nous avons développé en React un livre interractif autour de l'oeuvre d'Alice au pays des Merveilles,
avec les fonctionnalités suivantes :

- Laisser l'utilisateur choisir son aventure tout au long,
- Garder en mémoire l'avancement de l'utilisateur,
- Récupérer des objets (inventaire),
- Améliorer les compétences du personnage (système de statistiques),
- Générer des images d'illustrations par IA, via des API.

![Capture d'écran de l'application](/profile/Screenshot.png)

## Organisation du projet

| Dépôt                                                               | Rôle                                                                  |
| ------------------------------------------------------------------- | --------------------------------------------------------------------- |
| (book-game)[https://github.com/sae56-aleph/book-game]               | Coeur du projet, il contient l'ensemble des composants React.         |
| (book-game-api)[https://github.com/sae56-aleph/book-game-api]       | Partie chargée du lien entre les sources de données et l'application. |
| (book-game-docker)[https://github.com/sae56-aleph/book-game-docker] | Ensemble de scripts Dockerfile pour démarrer le projet en production. |

## Démarrage
Le dépôt [book-game-docker](https://github.com/sae56-aleph/book-game-docker) a pour but d'automatiser la création des conteneurs
Docker pour démarrer le projet en production. Il s'agit du point d'entrée offert au client fictif ayant demandé la réalisation
de l'application.

Le lancement de l'application se passe en deux étapes :
- Remplissage des données d'environnement (clés d'API, ports...)
- Démarrage avec docker-compose

Pour plus d'informations, suivre les instructions sur le dépôt.

## Auteurs
(Simon FOUCHET)[https://github.com/SimonnCode]
(Alexie GROSBOIS)[https://github.com/AlexieGrbs]
(Enzo MAROS)[https://github.com/zothma]
(Anthonin VINCENTELLI)[https://github.com/AppleJuice4]