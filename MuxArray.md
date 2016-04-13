# - MuxArray

Ce problème demande la réalisation du produit de deux tableaux passés dans l'entrée standard, de la manière suivante:
![Alt text](/ressources/exemple2MuxArray.PNG)

<br/><br/><br/><br/><br/><br/>
### -Exercices
+ 1) **MUXA1 - Faire sur feuille , le produit des deux tableaux suivants:**
<br/><br/>
![Alt text](/ressources/exempleExo1MuxArray.PNG) <br/>
Envoyer un code R faisant un print du resultat en vous basant sur cet exemple:
```R
cat("4 6 12 36 78 28");
```

<br/><br/>
+ 2) **MUXA2 - Generez un algorithme prenant en entrée les deux tableaux , et faisant un print du resultat via print.
On considere que les tableaux passés en parametre ne sont jamais vides et ont strictement la meme taille.**

Vous emploierez ces lignes de codes pour récuperer les deux tableaux.
```R
flux=file("stdin","r")
tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
tableau2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
```
> *aide*
> - Deux tableaux de meme taille facilite la tache au niveau des indices

Vous afficherez le tableau contenant le resultat de la maniere suivante : 
```R
cat(tableau_resultat);
```

Vous trouverez un fichier de test [sur ce lien](https://github.com/GRnice/concoursProgram/blob/master/ressources/muxarrayexo2.in "test") , cliquez droit dessus et enregistrez la cible sur le dossier d'où vous travaillez votre solution.

<br/><br/>
+ 3) **MUXA3 - Plus dur , si vous avez reussi le 2 , on vous demandera d'afficher les élements pairs du tableau TableauRes.
Attention les tableaux peuvent etre vides !**

Utilisez les memes lignes de codes pour récuperer les deux tableaux.
```R
flux=file("stdin","r")
tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
tableau2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
```

Vous afficherez le tableau contenant le resultat de la meme maniere : 
```R
cat(tableau_resultat);
```

Attention , si un des tableaux est vide ,le programme doit **seulement** afficher ```VIDE```
```R
cat("VIDE");
```



Vous trouverez un fichier de test [sur ce lien](https://github.com/GRnice/concoursProgram/blob/master/ressources/muxarrayexo3.in "test") , cliquez droit dessus et enregistrez la cible sur le dossier d'où vous travaillez votre solution.
