# concoursProgram
Repository du concours de programmation , sujet de TER

# - Traitement des entrées avec R

<section>(INPUT-A1) Pour lire la ligne L de l'entrée standard: </section>
```R
flux=file("stdin","r")
suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
```



<section> (INPUT-A2) Pour recuperer les deux tableaux du probleme MuxArrray dans l'entrée standard: </section>
```R
flux=file("stdin","r")
tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
tableau2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
```



Veillez à bien utiliser l'option suivante:
```R
quiet=TRUE
```
Si vous ne l'utiliser pas, votre fichier de sortie sera faussé, en effet sans cette option, votre fichier de sortie contiendra sur la première ligne, le nombre d'éléments que la commande scan à lu, chose qui n'est pas souhaité.
