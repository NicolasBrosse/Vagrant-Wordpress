# Le projet

Il s'agit ici d'un travail personnel qui consiste à créer et paramétrer un environnement de développement local avec Vagrant, Ansible et Wordpress.

Pour l'instant, j'utilise [Varying-Vagrant-Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV) qui a les mêmes objectifs, est beaucoup plus avancé et semble avoir été adopté par la communauté Wordpress. Mais le but est ici de mettre les mains dans le camboui pour apprendre et de construire un environnement adapté à mes besoins et mon niveau.

# Historique

Le but a été au départ de mettre en place un serveur web local afin d'y installer Wordpress.

Or j'utilise plusieurs machine de développement, l'une sous Mac et l'autre sous Linux. Les fichiers sont synchronisés entre les deux machines mais je voulais aller plus loin que d'installer MAMP pour le premier et LAMP pour le deuxième, avec les problèmes de base de données que cela ne manquerait pas d'apporter.

Je me suis donc orienté vers [Vagrant](https://www.vagrantup.com) pour un environnement au plus près d'un serveur de production sur une machine virtuelle, facilement réplicable et partageable.

# Pré-requis et choix techniques

- [VirtualBox](https://www.virtualbox.org/) pour ma virtualisation
- [Vagrant](https://www.vagrantup.com) pour l'automatisation et la configuration des machines virtuelles
- [Ansible](https://www.ansible.com) pour le provisionnement de Vagrant
- git pour le versionning des fichiers