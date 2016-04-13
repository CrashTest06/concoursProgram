# - Découpage binaire

  Déchiffrez le message qui se cache derriere cette suite de 0 et 1...
  
  Sur la première ligne du fichier vous trouverez le nombre de binaire à couper.
  A savoir que pour tous les exercices les fichiers d'entrées seront bien formés.
####  Exemple:
```R
input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
```
```R
output -> GOOD
```

## - Entrée & sortie

+ **Entrées**:
  + **Exercice 2**
  
    ```R
    flux=file("stdin","r");
    suiteBinaire=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    ```
  + **Exercice 3**
  
     ```R
    flux=file("stdin","r");
    suiteBinaire=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    nombrePourDecouper=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    ```
+ **Sortie**:

  ```R
  cat(intToUtf8(mon_vecteur))
  ```
  
## - Exercices
  
+ **1) Calculer à la main la représentation décimal du binaire que vous avez coupé en morceaux de 8 chiffres et trouvez dans la table Ascii (que vous trouverez au bas de ce document) le caractère correspondant à chaque morceau ou bien utiliser la fonction ```intToUtf8(arg)```de R. Envoyez le résultat avec un code R utilisant la fonction ```cat(arg)```**
  
  ####  Exemple:

```R
    input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
```
```R
    Code R -> cat("GOOD")
```
```R
    output -> GOOD
```
  + ***A vous de jouer avec cet input:***
```R
      input  -> 0 1 0 0 1 1 1 1 0 1 0 0 1 0 1 1
```

+ **2) Faites la même chose que pour l'exercice n°1, mais en lisant un fichier avec R. Obtenez le caractère depuis le nombre décimal que vous trouvez depuis le binaire en utilisant:```intToUtf8(arg)```**

+ **3) Nouveauté: le fichier contient désormais sur la deuxième ligne un suite d'entiers positifs. Ces entiers vont vous permettre de découper le binaire. En effet, vous ne découperez plus par morceau de 8, mais vous dépcouperez le binaire au indices (inclus) qui sont indiqués par les entiers présent sur la  deuxième ligne du fichier.Ecrivez un code R, qui découpe et obtient le caractère correspondant à la suite de binaire en fonction des differentes tailles de decoupes**
  #### Exemple:

```R
      input -> 1 0 1 0 0 0 1 1 1 1 0 1 0 1 0 1 0 1 0 1 1 0 0 0 0 1 1 0 1 0 0 1
               6 13 19 26 32
```
```R
      output -> (z*a)
```


### Table Ascii:
 
![Alt text](/ressources/table_ascii.png)
