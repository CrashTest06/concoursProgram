# TP noté L1 MASS

## - *Prise en main*:
+ https://github.com/GRnice/concoursProgram/blob/master/priseEnMain.md

## - Liste des éxercices:
+ [Problème du 42](https://github.com/GRnice/concoursProgram/blob/master/Exercice42.md "Le 42")
+ [Problème muxArray](https://github.com/GRnice/concoursProgram/blob/master/MuxArray.md "MuxArray")
+ [Problème des moyennes](https://github.com/GRnice/concoursProgram/blob/master/moyenne.md "Moyennes")
+ [Problème de l'épluchage](https://github.com/GRnice/concoursProgram/blob/master/epuchelage.md "Epluchage")
+ [Problème de permutations](https://github.com/GRnice/concoursProgram/blob/master/permut.md "Permutations")
+ [ProDécoupage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast")


## - Traitement des entrées avec R

+ **Pour lire la ligne L de l'entrée standard:**
  ```R
  flux=file("stdin","r")
  suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
  ```

  **Veillez à bien utiliser l'option suivante:**
  ```R
  quiet=TRUE
  ```
  ***Si vous ne l'utiliser pas, votre résultat sera faussé.***


+ **Pour récuperer les deux tableaux du problème MuxArrray dans l'entrée standard:**
  ```R
  flux=file("stdin","r");
  tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  tableau2=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  ```
## - Traitement des sorties avec R

+ **Pour afficher votre résultat utilisez la fonciton ```R cat(arg)``` et non la fonction ```R print(arg)```.**
  ```R
    res="test"
    cat(res)
  ```
+ **Cas particulier de ```R intToUtf8 ```**
  La fonction ```R intToUtf8 ``` affiche une string mal formaté dans la sortie standard si son résultat n'est pas affecté à une variable. Donc pour le [Découpage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast") affichez votre résultat de la façon suivante:
  ```R
    res=intToUtf8(mon_vecteur)
    cat(res)
  ```


