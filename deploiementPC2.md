# - Deploiement

# - Partie Serveur

Necessite une machine virtuelle pouvant executer du code python , Java et php.
Il nous faut egalement un compte mysql pour enregistrer les inscriptions des etudiants.
Possible d'envoyer un nombre important de mails aux etudiants afin de les authentifier via leur code sesame ?
<br/><br/>
Le code Java est nécessaire pour lancer le serveur de PC2 ainsi que ses divers services.
Le code PHP afin que les etudiants puissent s'inscrire au concours.
Le code python pour envoyer un mail à l'etudiant contenant un lien validant son inscription.

# - Partie Client

Deployer en local sur les machines un dossier contenant la partie client de PC2.
ajouter dans le path l'emplacement du dossier -> PC2HOME.

Dans ce dossier se trouvera egalement un programme python verrouillé en ecriture qui mettra à jour les fichiers de conf
qui contiendront l'adresse IP du serveur (de la VM).
Cette IP est récupérée sur un fichier texte hebergé dans un dossier WWW d'un de nos compte unice.


# - Installation de PC2 sur serveur

+ Récuperer et dezipper le zip pc2 sur le site officiel http://pc2.ecs.csus.edu/
+ Déposer le dossier sur le serveur
+ Configurer le fichier pc2v9.ini du dossier en inserant l'ip du serveur ``` server=ipServeur:numPort ``` , indiquer egalement le numero de port.
+ Copier et coller ce meme fichier dans les dossiers 'bin' et 'lib' 
+ Via le terminal , deplacez vous sur le dossier bin de pc2 et entrez ``` ./pc2server ``` , le serveur se lancera.

# - Installation de PC2 sur le client

/!\ java doit etre imperativement installé /!\

+ Recuperer et dezipper le meme zip pc2
+ Deposer le dossier pc2 en local sur les machines
+ Ajouter dans le path le chemin du dossier bin de pc2
+ Configurer le fichier pc2v9.ini en y inserant l'ip du serveur ``` server=ipServeur:numPort ``` 
+ Le fichier .ini doit etre deposé dans le dossier lib et bin
+ Dans le dossier pc2 , supprimer tout les dossier sauf bin et lib.
+ Via le terminal , tapez pc2team , le client pc2 se lancera.
