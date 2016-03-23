# - Deploiement

# - Partie Serveur

Besoin d'une machine virtuelle pouvant executer du code python , Java et php.
Il nous faut egalement un compte mysql pour enregistrer les inscriptions des etudiants.
<br/><br/>
Le code Java est nécessaire pour lancer le serveur de PC2 ainsi que ses divers services.
Le code PHP afin que les etudiants puissent s'inscrire au concours.
Le code python pour envoyer un mail d'activation à l'etudiant afin qu'il valide son inscription.

# - Partie Client

Deployer en local sur les machines un dossier contenant la partie client de PC2.
ajouter dans le path l'emplacement du dossier.

Dans ce dossier se trouvera egalement un programme python verrouillé en ecriture qui mettra à jour les fichiers de conf
qui contiendront l'adresse IP du serveur (de la VM).
Cette IP est récupérée sur un fichier texte hebergé dans un dossier WWW d'un de nos compte unice.
