# SendLargesteFileFTP
L'app Contient plusieurs elements :

- makefile . Qui permet de lancer l'ensemble du programme .
- bash.sh . Copie des fichiers csv dans le fichier content.txt .
- main.py . Fichier Python3.10 qui a en sortie le fichier csv avec l'indice le plus grand exemple comptage1.csv < comptage5.csv .
- send.py . Fichier Python3.10 qui envoie par mail le fichier comptage déterminer comme ayant l'indice le plus grand par le fichier main.py .
- Les fichiers csv .

Ficher de configuration :
- info.ini . Contiennent les informations pour l'envoi de mail .
  Vous pouvez remplir trois mails pour faire ce mail suivre à ces trois contacte si besoin .
- config.ini . Stockage du nom du ficher Csv avec l'indice le plus grand .

L'ensemble de l'application doit être installé dans le fichier cible de réception des fichiers .csv
L'automatisation du lancement du processus est géré grace a cron tous les premiers du mois .

Détection et envoie par mail du fichier le plus recent sur un dépôt FTP .
