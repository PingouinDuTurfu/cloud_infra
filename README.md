# Français - Cloud infra : Docker

Ce projet est une démonstration d'une infrastructure cloud basée sur Docker.

## Installation

**Attention :** Ce dépôt GitHub ne contient pas tous les fichiers nécessaires au fonctionnement de Docker. Il est impératif d'ajouter les fichiers du drive à la racine du dépôt.

Pour ajouter les fichiers du drive, procédez comme suit :

1. Téléchargez les fichiers du drive à l'adresse suivante : [Google Drive](https://drive.google.com/drive/folders/1179e68y2D1jnn3SgQPcAB5nYu4TzvV5m?usp=sharing)

2. Copiez les fichiers dans la racine du dépôt.

## Lancement du projet

Pour lancer le projet, exécutez la commande suivante : `docker-compose -f docker-compose.yml up`

## Explication
Le projet est structuré autour de trois types de conteneurs :

1. **Conteneur de base de données (MySQL):**
   - Se remplit à partir du fichier `init_pokedle.sql`.

2. **Conteneur d'équilibrage de charge (nginx):**
   - Répartit la charge sur trois applications.

3. **Conteneur de développement:**
   - Partage un volume avec les applications, contenant le code source.

4. **Trois conteneurs pour les applications:**
   - Jeu basé sur les Pokémon.

## Environnement de développement

- **IDE utilisé:** Micro
- **Site accessible depuis:** [localhost:8080](http://localhost:8080)
<br>

# English - Cloud infra: Docker

This project is a demonstration of a cloud infrastructure based on Docker.

## Installation

**Attention:** This GitHub repository does not contain all the files necessary for Docker to function. It is imperative to add the files from the drive to the root of the repository.

To add the drive files, follow these steps:

1. Download the files from the drive at the following address: [Google Drive](https://drive.google.com/drive/folders/1179e68y2D1jnn3SgQPcAB5nYu4TzvV5m?usp=sharing)
2. Copy the files to the root of the repository.

## Project Launch

To launch the project, execute the following command: `docker-compose -f docker-compose.yml up`

## Explanation
The project is structured around three types of containers:

1. **Database Container (MySQL):**
   - Populated from the `init_pokedle.sql` file.

2. **Load Balancing Container (nginx):**
   - Distributes the load across three applications.

3. **Development Container:**
   - Shares a volume with the applications, containing the source code.

4. **Three containers for applications:**
   - Game based on Pokémon.

## Development Environment

- **IDE used:** Micro
- **Site accessible from:** [localhost:8080](http://localhost:8080)


