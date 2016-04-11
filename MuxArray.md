# - Exercice MuxArray

Ce probleme demande la réalisation du produit de deux tableaux passés dans l'entrée standard, de la manière suivante:
![Alt text](/ressources/exemple2MuxArray.PNG)

<br/><br/><br/><br/><br/><br/>

+ 1) Faire sur feuille , le produit des deux tableaux suivants:
<br/><br/>
![Alt text](/ressources/exempleExo1MuxArray.PNG) <br/>
Envoyer un code R faisant un print du resultat en vous basant sur cet exemple:
```R
print("4 6 12 36 78 28");
```

<br/><br/>
+ 2) **Generez un algorithme prenant en entrée les deux tableaux , et faisant un print du resultat via print.
On considere que les tableaux passés en parametre ne sont jamais vide.**

Vous emploierez ces lignes de codes pour récuperer les deux tableaux.
```R
flux=file("stdin","r")
tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
tableau2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
```

Vous afficherez le tableau contenant le resultat de la maniere suivante : 
```R
print(tableau_resultat);
```
<br/><br/>
+ 3) Plus dur , si vous avez reussi le 2 , on vous demandera d'afficher les elements pairs du tableau TableauRes.
Attention les tableaux peuvent etre vide !
