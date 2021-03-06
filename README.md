# TP noté L1 MASS


## - **Prise en main**:
+ [Prise en main](https://github.com/GRnice/concoursProgram/blob/master/priseEnMain.md "Prise en main")

## - Liste des exercices:
+ [Echauffement](https://github.com/GRnice/concoursProgram/blob/master/echauffement.md "échauffement")
+ [Problème du 42](https://github.com/GRnice/concoursProgram/blob/master/Exercice42.md "Le 42")
+ [Problème muxArray](https://github.com/GRnice/concoursProgram/blob/master/MuxArray.md "MuxArray")
+ [Problème des moyennes](https://github.com/GRnice/concoursProgram/blob/master/moyenne.md "Moyennes")
+ [Problème de l'épluchage](https://github.com/GRnice/concoursProgram/blob/master/epluchage.md "Epluchage")
+ [Problème de permutations](https://github.com/GRnice/concoursProgram/blob/master/permutation.md "Permutations")
+ [Problème Découpage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast")


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
  ***Si vous ne l'utilisez pas, votre résultat sera faussé.***


+ **Pour récuperer les deux tableaux du problème MuxArrray dans l'entrée standard:**


  ```R
  flux=file("stdin","r");
  tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  tableau2=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  ```

## - Traitement des sorties avec R

+ **Pour afficher votre résultat utilisez la fonction ``` cat(arg)``` et non la fonction ``` print(arg)```.** ``` res="test" cat(res) ```
  
+ **Cas particulier pour ``` intToUtf8 ```**
  La fonction ``` intToUtf8 ```affiche une string mal formatée dans la sortie standard si son résultat n'est pas affecté à une variable. Donc pour le [Découpage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast") affichez votre résultat de la façon suivante:

  ```R
    res=intToUtf8(mon_vecteur)
    cat(res)
  ```


