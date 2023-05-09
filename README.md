# DVWA_deployer
This bash script installs DVWA and configures its associated MySQL database by installing necessary packages, downloading DVWA, creating a new database and user, and configuring DVWA's settings.

Ce script bash permet d'installer DVWA (Damn Vulnerable Web Application) et de configurer la base de données MySQL associée.
## Prerequisite
sudo privileges to execute the script
## Installation
Téléchargez le script bash sur votre machine

Ouvrez le terminal et accédez au répertoire où se trouve le script
Exécutez la commande sudo ./nom_du_script.sh nom_de_la_base_de_donnees

## Use

Le script va installer les paquets nécessaires et télécharger DVWA dans le répertoire /var/www/html/. Ensuite, il va configurer la base de données MySQL en créant une nouvelle base de données et un nouvel utilisateur avec un mot de passe. Enfin, il va configurer DVWA en remplaçant les paramètres par défaut dans le fichier de configuration.
## Deployment

To deploy this project run

```bash
  git clone https://github.com/joblinours/dvwa_deployer 
  cd /dvwa_deployer
  sudo ./dvwa_deploy database_name
```

## info supplémentaire

the script only works on a server version (ubuntu server for example).
Tested on kali, but without success
