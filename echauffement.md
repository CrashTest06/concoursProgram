# Equation du second degré

Réaliser un simple programme évaluant la fonction ax² + bx + c

L'idée est que vous récupériez en entrée quatres paramètres (a,b,c,x) et appliquiez l'équation.

+ **Exemple**:

  + **input** :
     
    ```1 2 4 6```

  + **output** :
  
    ```14``` => (2 * 1)² + (4 * 1) + 6

## Entrée & Sortie

+ **Entrée**

Pour récupérer les paramètres , employez ces lignes de code au debut de votre solution
```R
flux=file("stdin","r");
listeParametres=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
x <- listeParametres[1];
a <- listeParametres[2];
b <- listeParametres[3];
c <- listeParametres[4];
```

+ **Sortie**

Vous afficherez le résultat de votre solution avec l'instruction ``` cat ```
```R
#exemple

cat(resultat);
```

## - Exercices

+ **1) EQUA-1 - Réaliser un programme en R évaluant l'équation en fonction des paramètres mentionnés plus haut.**



Vous trouverez un fichier de test [sur ce lien](https://github.com/GRnice/concoursProgram/blob/master/ressources/testEquation1.in "test1") , cliquez droit dessus et enregistrez la cible sur le dossier d'où vous travaillez votre solution.


