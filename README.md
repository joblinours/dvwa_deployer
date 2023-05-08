# dvwa_deployer
This bash script installs DVWA and configures its associated MySQL database by installing necessary packages, downloading DVWA, creating a new database and user, and configuring DVWA's settings.

Ce script bash permet d'installer DVWA (Damn Vulnerable Web Application) et de configurer la base de données MySQL associée.

Prérequis
Il est nécessaire d'avoir sudoers pour exécuter ce script.

Installation
Téléchargez le script bash sur votre machine
Ouvrez le terminal et accédez au répertoire où se trouve le script
Exécutez la commande sudo ./nom_du_script.sh nom_de_la_base_de_donnees
Utilisation
Le script va installer les paquets nécessaires et télécharger DVWA dans le répertoire /var/www/html/. Ensuite, il va configurer la base de données MySQL en créant une nouvelle base de données et un nouvel utilisateur avec un mot de passe. Enfin, il va configurer DVWA en remplaçant les paramètres par défaut dans le fichier de configuration.

Avertissement
DVWA est une application Web vulnérable, destinée uniquement à des fins éducatives et de test. Il est recommandé de l'utiliser dans un environnement isolé et de ne pas le déployer sur un serveur en production.

Licence
Ce script est publié sous la licence MIT.
