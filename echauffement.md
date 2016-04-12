# Fonction carré

Réaliser un simple programme realisant la fonction ax² + bx + c

L'idée est que vous récupériez en entrée quatres paramètres (a,b,c,x) et appliquiez l'équation.

## - Exemple:

input : ```x = 1 ; a = 2 ; b = 4 ; c = 6```

output : ```14``` => (2 * 1)² + (4 * 1) + 6

## - Entrée & Sortie

+ Entrée

Pour récuperer les paramètres , employez ces lignes de code au debut de votre solution
```R
flux=file("stdin","r");
listeParametres=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
x <- listeParametres[1];
a <- listeParametres[2];
b <- listeParametres[3];
c <- listeParametres[4];
```

+ Sortie

Vous afficherez le résultat de votre solution avec l'instruction ``` cat ```
```R
#exemple

cat(resultat);
```

## - Exercices

+ 1) **Réaliser un programme en R résolvant l'équation en fonction des paramètres mentionnés plus haut.**
