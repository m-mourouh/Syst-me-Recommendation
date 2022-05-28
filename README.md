# Système de recommandation touristique

*-------------------------------PFE LST IRM----------------------------------*
 | Pour Démarrer l'application sur votre machine veuillez ouvrir            |     
 | votre invite de commande ou votre teminal et suivre les étapes suivantes  |
*----------------------------------------------------------------------------*

$ # Création d'environnement virtuel sur Windows
$ # pip install virtualenv (si vous avez pas installer virtualenv sur votre PC)
$ # virtualenv venv    (créer un environnement virtuel)
$ # venv/Scripts/activate (activer l'environnement virtuel)
$
$ # Installer des modules 
$ pip3 install -r requirements.txt 
$
$ # Créer les tables de la base de données
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Démarrer l'application (mode développement)
$ python manage.py runserver <votre port> (port par défaut 8000)
$
$ # Accéder à l'application Web dans le navigateur : http://127.0.0.1:8000/

*----------------------------les Membres de groupes---------------------------*
 |  MOHAMED MOUROUH                                                          |               
 |  FATIMA ERRKIK                                                            |
 |  FADWA BENHAR                                                             |
*-----------------------------------------------------------------------------*
