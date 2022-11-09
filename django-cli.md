# Commandes Django

## Créer une application django

- `django-admin startproject {project_name}` : crée un projet Django
- `django-admin startapp {module_name}` : crée un module dans le projet Django

## Commande commançant par `python manage.py`

- `runserver`: lancer le serveur
- `shell` : lancer la console python au sein du projet
- `sqlmigrate {app_name} {migration_id}` : détail sql de la migration
- `makemigrations {app_name}` : génère les fichiers de migration de l'app
- `migrate` : joue les migrations
- `createsuperuser` : crée un super user pour la page admin
- `test` : joue les tests
