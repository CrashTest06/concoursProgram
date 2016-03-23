# concoursProgram
Repository du concours de programmation , sujet de TER

# - Traitement des entrées avec R


<section> <font color = "red"> (INPUT-A1) </font> Pour lire la ligne L de l'entrée standard: </section>
```R
flux=file("stdin","r")
suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
```



<section>
<font color = "blue">
(INPUT-A2) 
</font>
Pour recuperer les deux tableaux du probleme MuxArrray dans l'entrée standard: </section>
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
Pour recuperer la suite de nombre , vous devez reprendre le code <font color='red'> INPUT-A1 </font> avec
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
![Alt text](/exemple2MuxArray.PNG)

Employer le code <font color='blue'> INPUT-A2 </font> pour recuperer les deux tableaux.

Vous afficherez le tableau contenant le resultat de la maniere suivante : 
```R
print(tableau_resultat);
```


+ 1) Faire sur feuille , le produit des deux tableaux suivants:
<br/><br/>
![Alt text](/exempleExo1MuxArray.PNG)
Envoyer un code R faisant un print du resultat en vous basant sur cet exemple:
```R
print("4 6 12 36 78 28");
```


+ 2) Generez un algorithme prenant en entrée les deux tableaux , et faisant un print du resultat via print.

+ 3) Plus dur , si vous avez reussi le 2 , on vous demandera d'afficher les elements pairs du tableau TableauRes.

# - Exercice Epluchage

  Le but est de compter le nombre d'occurences des chiffres qui apparaissent dans un nombre n et d'en faire un nouveau nombre.
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 111112229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
            
  1) Ecrire sur une feuille le resultat pour n = 685415111
  
  2) Ecrire le code R qui renvoie le tableau d'occurences des chiffres d'un nombre récupérer en entré grâce au code <font color = 'red'> INPUT-A1 </font>.
  
  3) Ecrire le code R qui renvoie le nombre créé à l'aide du nombre d'occurences des chiffres d'un nombre récupérer grâce au code <font color = 'red'> INPUT-A1 </font>.
  
  
# - Exercice Permutation

  Verifier si une suite de nombre est une permutation inverse d'une autre liste
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 2 3 4 5 1
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  5 1 2 3 4
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> TRUE
    
    1) Ecrire sur une feuille si la liste: 3 8 5 10 9 4 6 1 7 2 
    est permutation de la liste: 8 10 1 6 3 2 9 7 5 4
    
    2) Ecrire un code R qui recupere deux listes en entrée grâce au code  <font color = 'blue'> INPUT-A2 </font>
    et qui verifie si une liste l1 est la liste renversée l2.
    
    3) Ecrire un code R qui recupere deux listes en entrée grâce au code <font color = 'blue'> INPUT-A2 </font>
     et qui verifie si une liste l1 est la permutation inverse de la liste l2

<br/>

# - Exercice Moyenne Pondérée

  Calculer la moyenne pondéré à partir deux listes, celle des notes et celle des coefficients.
  <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 8 12 10 10 10
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  4 3 1 1 1
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 9.8
       
    1) Ecrire sur une feuille le calcul de la moyennes pondérées des notes : 18 18 12 11 7
    avec leur coefficients respectives : 6 2 4 4 1
    
    2) Ecrire un code R qui recupere une liste de notes en entrée grâce au code  <font color = 'red'> INPUT-A1 </font>
    et calcule sa moyenne non pondérées.
    
    3) Ecrire un code R qui recupere une liste de notes et une liste de coefficients en entrée 
    grâce au code  <font color = 'blue' INPUT-A2 </font> et calcule sa moyenne pondérées.
