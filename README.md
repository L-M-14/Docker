1/ arborescence du projet

project/
├── compose.yml
├── .env
├── config/
│ ├── nginx/
│ │
│ ├── php/
│ │  
│ └── secrets/
│ └── db_name.txt
│ └── db_user.txt
│ └── db_user_password.txt
│ └── db_root_password.txt  
│  
│  
├── src/
│ ├── app/
│ │  
│ └── Dockerfile
└── .gitignore

2/ Dans le repertoire "/config/secrets/" créer et completer les fichiers suivants :

db_name.txt → définir le nom de la DATABASE

db_user.txt → définir le nom d'utilisateur

db_user_password.txt → définir le mot de passe utilisateur

db_root_password.txt → définir le mot de passe ROOT

Chaque fichier ".txt" doit contenir exactement une valeur sans espaces ou sauts de ligne supplémentaires.

3/ Lancer le projet dans Docker puis rendez-vous sur http://localhost:8080/, vous serez redirigé vers http://localhost:8080/wp-admin/install.php afin lancer l'installation de Wordpress.
# Docker
