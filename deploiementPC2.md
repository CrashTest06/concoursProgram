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


# - Installation de PC2

+ recuperer et dezipper le logiciel pc2 sur le site officiel http://pc2.ecs.csus.edu/
+ deposer le dossier sur le serveur
+ configurer le fichier pc2v9.ini du dossier en inserant l'ip du serveur ``` server=ipServeur:50002 ``` , vous pouvez egalement modifier 
+ copier et coller ce meme fichier dans les dossiers 'bin' et 'lib' 
