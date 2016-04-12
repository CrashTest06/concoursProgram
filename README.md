# concoursProgram
Repository du concours de programmation , sujet de TER

## - Enoncés:
+ [probleme du 42](https://github.com/GRnice/concoursProgram/blob/master/Exercice42.md "Le 42")
+ [probleme muxArray](https://github.com/GRnice/concoursProgram/blob/master/MuxArray.md "MuxArray")
+ [probleme des moyennes](https://github.com/GRnice/concoursProgram/blob/master/moyenne.md "Moyennes")
+ [probleme de l'épluchage](https://github.com/GRnice/concoursProgram/blob/master/epuchelage.md "Epluchage")
+ [probleme de permutations](https://github.com/GRnice/concoursProgram/blob/master/permut.md "Permutations")
+ [decoupage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast")


## - Traitement des entrées avec R

+ **Pour lire la ligne L de l'entrée standard:**
```R
flux=file("stdin","r")
suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
```

Veillez à bien utiliser l'option suivante:
```R
quiet=TRUE
```
Si vous ne l'utiliser pas, votre résultat sera faussé.




+ **Pour récuperer les deux tableaux du problème MuxArrray dans l'entrée standard:**
```R
flux=file("stdin");
open(f , open="r", what = "character");
t1 <- readLines(f,1);
t2 <- readLines(f,2);
close(f);
splitT1 <- strsplit(t1,' ');
splitT2 <- strsplit(t2,' ');
tableau1 <- splitT1[[1]];
tableau2 <- splitT2[[1]];
```



