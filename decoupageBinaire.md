# - Découpage binaire

  Déchiffrez le message qui se cache derriere cette suite de 0 et 1...
  
  Sur la première ligne du fichier vous trouverez le nombre de binaire à couper.
  A savoir que pour tous les exercices les fichiers d'entrées seront bien formés.
####  Exemple:
```R
input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
```
```R
output -> [1] "GOOD"
```

  
## - Exercices
  
+ **1) Ecrire sur une feuille la représentation décimal ou héxadécimal du binaire que vous avez coupé en morceau de 8 et trouvez dans la table Ascii (que vous trouverez au bas de ce document) le caractère correspondant.**
  
  ####  Exemple:

```R
    input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
```
```R
    Code R -> print("GOOD")
```
```R
    output -> [1] "GOOD"
```
  + ***A vous de jouer avec cet input:***
```R
      input  -> 0 1 0 0 1 1 1 1 0 1 0 0 1 0 1 1
```

+ **2) Faites la même chose que pour l'exercice n°1, mais en lisant un fichier avec R. Obtenez le caractère ascii en utilisant:```intToUtf8(arg)```**

+ **3) Nouveauté: le fichier contient désormais sur la deuxième ligne un suite d'entier positif. Ces entiers vont vous permettre de découper la binaire.En effet, vous ne découperez plus par morceau de 8, mais par des morceaux de taille qui est indiqué par la suite d'entier présente sur la deuxième ligne du fichier.Ecrivez un code R, qui découpe et traduit en ascii la suite de binaire selon la suite d'entier se trouvant sur la deuxième ligne du fichier**
  #### Exemple:

```R
      input -> 1 0 1 0 0 0 1 1 1 1 0 1 0 1 0 1 0 1 0 1 1 0 0 0 0 1 1 0 1 0 0 1
               6 13 19 26 32
```
```R
      output -> [1] "(z*a)"
```


### Table Ascii:
 
![Alt text](/ressources/table_ascii.png)
