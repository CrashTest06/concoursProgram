# concoursProgram
Repository du concours de programmation , sujet de TER

## - Enoncés:
+ [probleme du 42](https://github.com/GRnice/concoursProgram/blob/master/Exercice42.md "Le 42") <br/>
+ [probleme muxArray](https://github.com/GRnice/concoursProgram/blob/master/MuxArray.md "MuxArray") <br/>
+ [probleme des moyennes](https://github.com/GRnice/concoursProgram/blob/master/moyenne.md "Moyennes") <br/>
+ [probleme des moyennes](https://github.com/GRnice/concoursProgram/blob/master/moyenne.md "Moyennes") <br/>
+ [probleme de l'épluchage](https://github.com/GRnice/concoursProgram/blob/master/epuchelage.md "Epluchage") <br/>
+ [probleme de permutations](https://github.com/GRnice/concoursProgram/blob/master/permut.md "Permutations") <br/>
+ [decoupage binaire](https://github.com/GRnice/concoursProgram/blob/master/decoupageBinaire.md "SplitAndCast") <br/>


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
Si vous ne l'utiliser pas, votre fichier de sortie sera faussé, en effet sans cette option, votre fichier de sortie contiendra sur la première ligne, le nombre d'éléments que la commande scan à lu, chose qui n'est pas souhaité.




+ **Pour recuperer les deux tableaux du probleme MuxArrray dans l'entrée standard:**
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



