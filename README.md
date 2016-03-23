# concoursProgram
Repository du concours de programmation , sujet de TER

# - Traitement des entrées avec R


<section> (INPUT-A1) Pour lire la ligne L de l'entrée standard: </section>
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

# - Exercice du 42
Il s'agit de detecter le nombre 42 dans une suite de nombre passée dans l'entrée standard (stdin) , l'idée est que lors de l'itération on affiche le nombre lu tant que 42 n'a pas été lu , si il a été lu alors on l'affiche jusqu'à la derniere iteration.

Exemple:
input   -> 1 2 3 4 5 6 42 0 0 0 7 8
output  -> 1 2 3 4 5 6 42 42 42 42 42 42

1) Ecrire sur feuille le resultat donné avec cette suite de nombre donnée: 1 2 8 41 20 42 1 9 5 3

2) Ecrire un programme en R resolvant le probleme donné
Pour recuperer la suite de nombre , vous devez reprendre le code INPUT-A1 avec
```R
nline=1
```
A chaque iteration vous devez afficher sur la sortie standard (print) le nombre à afficher.
```R
while (length(suiteNombre) >= i)
{
...
print(suiteNombre[i]); # exemple
...
}
```

3) Plus dur , à present on souhaite afficher 42 lorsque la somme des 3 derniers elements lus fait 42.
Exemple:
input   -> 1 3 5 7 1 1 40 9 8
output  -> 1 3 5 7 1 1 42 42 42

# - Exercice MuxArray

Ce probleme demande la réalisation du produit de deux tableaux passés dans l'entrée standard, de la manière suivante:
Employer le code INPUT-A2 pour recuperer les deux tableaux.

Vous afficherez le tableau contenant le resultat de la maniere suivante : 
```R
print(tableau_resultat);
```

![Alt text](/exemple2MuxArray.PNG)



1) Faire sur feuille , le produit des deux tableaux suivants:
<br/><br/>
![Alt text](/exempleExo1MuxArray.PNG)

# - Exercice Epluchage

  Le but est de compter le nombre d'occurences des chiffres qui apparaissent dans un nombre n et d'en faire un nouveau nombre.
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 111112229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
            
  1) Ecrire sur une feuille le resultat pour n = 685415111
  
  2) Ecrire le code R qui renvoie le tableau d'occurences des chiffres d'un nombre récupérer en entré grâce au code INPUT-A1.
  
  3) Ecrire le code R qui renvoie le nombre créé à l'aide du nombre d'occurences des chiffres d'un nombre récupérer grâce au code INPUT-A1.
  
  
# - Exercice Permutation

  Verifier si une suite de nombre est une permutation inverse d'une autre liste
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 2 3 4 5 1
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 1 2 3 4
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; output -> 531
